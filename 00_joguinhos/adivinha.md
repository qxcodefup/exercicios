
# Python

```python
import random

def imprimir_mensagem(n_chutes):
    if n_chutes == 4:
        print "Chuck Noris"
    elif n_chutes < 10:
        print "Ninja"
    elif n_chutes < 15:
        print "da pro gasto"
    else:
        print "Muito muito muito lesado"


def imprimir_dica(chute, numero):
    if(chute == numero):
        print "Acertou"
    elif(chute > numero):
        print "Eh menor"
    else:
        print "Eh maior"


def pegar_chute():
    chute = 0
    deu_certo = False
    while(not deu_certo):
        chute = int(input("Digite seu chute: "))
        if(chute < 0 or chute > 100):
            print "Eh de 0 a 100 abestado!"
        else:
            deu_certo = True
    return chute


def main():
    n_chutes = 0;
    numero = random.randint(0, 100)
    chute = -1
    while(chute != numero):
        n_chutes += 1
        chute = pegar_chute()
        imprimir_dica(chute, numero)
    imprimir_mensagem(n_chutes)


main()
```

# C++

```c++
#include <iostream>
#include <cstdlib>
#include <ctime>

using namespace std;

void imprimir_mensagem(int n_chutes){
    if(n_chutes == 4)
        cout << "Chuck Noris" << endl;
    else if(n_chutes < 10)
        cout << "Ninja" << endl;
    else if(n_chutes < 15)
        cout << "da pro gasto" << endl;
    else
        cout << "Muito muito muito lesado" << endl;
}

void imprimir_dica(int chute, int numero){
    if(chute == numero)
        cout << "Acertou" << endl;
    else if(chute > numero)
        cout << "Eh menor" << endl;
    else
        cout << "Eh maior" << endl;
}
int pegar_chute() {
    int chute = 0;
    bool deu_certo = false;
    while(!deu_certo){
        cout << "Digite seu chute" << endl;
        cin >> chute;
        if(!cin){
            cin.clear();//desquebra a entrada que quebrou
            cin.ignore(1000, '\n');//limpa o que estava escrito
        }
        else if(chute < 0 || chute > 100){
            cout << "Eh de 0 a 100 abestado!" << endl;
        }else{
            deu_certo = true;
        }
    }
    return chute;
}

int main(){
    srand(time(NULL));
    int n_chutes = 0;
    int numero = rand() % 100;
    int chute = -1;
    while(chute != numero){
        n_chutes += 1;
        chute = pegar_chute();
        imprimir_dica(chute, numero);
    }
    imprimir_mensagem(n_chutes);
    return 0;
}
```

# C

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>


void imprimir_mensagem(int n_chutes){
    if(n_chutes == 4)
        puts("Chuck Noris");
    else if(n_chutes < 10)
        puts("Ninja");
    else if(n_chutes < 15)
        puts("da pro gasto");
    else
        puts("Muito muito muito lesado");
}

void imprimir_dica(int chute, int numero){
    if(chute == numero)
        puts("Acertou");
    else if(chute > numero)
        puts("Eh menor");
    else
        puts("Eh maior");
}
int pegar_chute() {
    int chute = 0;
    int deu_certo = 0;
    while(!deu_certo){
        puts("Digite seu chute entre 0 e 100");
        scanf("%d", &chute);
        if(chute < 0 || chute > 100){
            puts("Eh de 0 a 100 abestado!");
        }else{
            deu_certo = 1;
        }
    }
    return chute;
}

int main(){
    srand(time(NULL));
    int n_chutes = 0;
    int numero = rand() % 100;
    int chute = -1;
    while(chute != numero){
        n_chutes += 1;
        chute = pegar_chute();
        imprimir_dica(chute, numero);
    }
    imprimir_mensagem(n_chutes);
    return 0;
}
```
