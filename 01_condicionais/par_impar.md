### C++

```c++
#include<iostream>

using namespace std;

void par_ou_impar(int numero){
  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      cout << "Par";
  else
      cout << "Impar";
}

int main() {
  int numero;
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
      printf("Par");
  else
      printf("Impar");
}

int main() {
  int numero;
  scanf("%d", &numero);

  par_ou_impar(numero);

  return 0;
}
```

### Python

```python
numero = int(input())

def par_ou_impar(numero):
  #Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if numero % 2 == 0:
    print "Par"
  else
    print "Impar"

par_ou_impar(numero)

```
