### C
```c
#include <stdio.h>

#define TRUE 1
#define FALSE 0

int is_divisible(int num_a, int num_b){
  if (num_a % num_b == 0)
    return TRUE;
  return FALSE;
}

int main() {
  int num_a, num_b;
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_a);
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_b);

  if (is_divisible(num_a, num_b) == TRUE)
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

bool is_divisible(int num_a, int num_b){
  if (num_a % num_b == 0)
    return true;
  return false;
}

int main() {
  int num_a, num_b;
  cout << "Digite um numero inteiro: ";
  cin >> num_a;
  cout << "Digite um numero inteiro: ";
  cin >> num_b;

  //Utilizando operador ternario para formatar saida
  cout << is_divisible(num_a, num_b) == TRUE ? "SIM":"NAO" << endl;

  return 0;
}
```
### Python
```python

def is_divisible(num_a, num_b):
 if num_a % num_b == 0:
   return True
 return False

num_a = int (input ("Digite um numero: "))
num_b = int (input ("Digite um numero: "))

print "SIM" if is_divisible (num_a, num_b) else "NAO" # É assim que se usa operador ternario em python

```
