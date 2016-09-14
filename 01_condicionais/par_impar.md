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
