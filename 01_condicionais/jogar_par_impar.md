#C++
```c++
#include <iostream>
#include <cstdlib>
#include <ctime>
#include <cstdio>

using namespace std;

const int PAR = 0;
const int IMPAR = 1;

int main(){
    int op_jog = 0;
    int valor_jog = 0;
    int valor_maq = 0;
    int nvit_jog = 0;
    int nvit_maq = 0;
    while(nvit_jog < 3 && nvit_maq < 3){
        cout << "Digite 0 para Par e 1 para Impar" << endl;
        cin >> op_jog;
        cout << "Mostre os dedos" << endl;
        cin >> valor_jog;
        valor_maq = rand() % 11;
        cout << "A maquina escolheu " << valor_maq << endl;
        if((valor_maq + valor_jog) % 2 == op_jog){
            nvit_jog++;
            cout << "Jogador ganhou\n";
        }else{
            nvit_maq++;
            cout << "Maquina ganhou\n";
        }
        cout << "Jog: " << nvit_jog << "   Maq: " << nvit_maq << endl;
    }
    if(nvit_jog == 3)
        puts("Jogador foi o grande campeao");
    else
        puts("Maquina foi a grande campea");
    return 0;
}
```
