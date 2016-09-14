### C++

```c++
#include<iostream>

using namespace std;

void par_ou_impar(int numero){
  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      cout << "Par" << endl;
  else
      cout << "Impar" << endl;
}

int main() {
  int numero;
  cout << "Digite um numero inteiro: ";
  cin >> numero;

  par_ou_impar(numero);

  return 0;
}

```

### C

```c
#include <stdio.h>

void par_ou_impar(int numero){
  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      printf("Par\n");
  else
      printf("Impar\n");
}

int main() {
  int numero;
  printf("Digite um numero inteiro: ");
  scanf("%d", &numero);

  par_ou_impar(numero);

  return 0;
}
```

### Python

```python
def par_ou_impar(numero):
  #Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if numero % 2 == 0:
    print "Par"
  else
    print "Impar"

numero = int(input("Digite um numero inteiro: "))

par_ou_impar(numero)

```
