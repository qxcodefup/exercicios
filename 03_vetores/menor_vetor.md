
Exercício extra: você não precisa de um vetor pra isso. Basta ler e durante o laço de leitura, guardar o menor.

### C++
```c++
#include <iostream>
#include <vector>
using namespace std;

int main(){
    cout << "Digite valores inteiros e -1 para sair" << endl;
    int value = 0;
    vector<int> valores;
    while(true){
        cin >> value;
        if(value == -1)
            break;
        valores.push_back(value);
    }
    int menor = valores[0];
    for(auto valor : valores){
        if(valor < menor){
            menor = valor;
        }
    }
    cout << "O menor eh " << menor << endl;
    return 0;
}
```

### C
```c
#include <iostream>
#include <vector>
using namespace std;

int main(){
    cout << "Digite valores inteiros e -1 para sair" << endl;
    int value = 0;
    vector<int> valores;
    while(true){
        cin >> value;
        if(value == -1)
            break;
        valores.push_back(value);
    }
    int menor = valores[0];
    for(auto valor : valores){
        if(valor < menor){
            menor = valor;
        }
    }
    cout << "O menor eh " << menor << endl;
    return 0;
}
```

###Python

```python
valores = []

while(True): #laço infinito
  value = int (input ("Digite valores inteiros e -1 para sair: "))
  if value == -1: #condicao de parada do laço
    break
  valores.append(value)

menor = valores[0]
for valor in valores:
  if valor < menor:
    menor = valor

print "O menor eh %d" % menor
```
