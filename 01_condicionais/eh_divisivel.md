_Exercicio extra: Crie uma funcao que retorna um valor booleano informando se é divisivel. No caso do C que nao possui valores booleanos defina uma constante para o valor de verdade e uma para o de falso._  

### C
```c
#include <stdio.h>

int main() {
  int num_a, num_b;
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_a);
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_b);

  if (num_a % num_b == 0)
    printf("SIM\n");
  else
    printf("NAO\n");

  return 0;
}
```
### C++
```c++
#include <iostream>

using namespace std;

int main() {
  int num_a, num_b;
  cout << "Digite um numero inteiro: ";
  cin >> num_a;
  cout << "Digite um numero inteiro: ";
  cin >> num_b;

  if (num_a % num_b == 0)
    cout << "SIM" << endl;
  else
    cout << "NAO" << endl;

  return 0;
}
```
### Python
```python
num_a = int (input ("Digite um numero: "))
num_b = int (input ("Digite um numero: "))

if num_a % num_b == 0:
  print "SIM"
else:
  print "NAO"
  
```
