### C
```c
#include <math.h>
#define  TRUE 1
#define FALSE 0

int eh_primo(int numero){
    if (numero == 1 || (numero % 2 == 0 && numero != 2))
        return FALSE; //1 e os numeros pares não são primos, com exceção do 2
    for (int i = 2; i < (int)sqrt(numero) + 1; i++)
        if (numero % i == 0)
            return FALSE;
    return TRUE;
}

int numero;
scanf("%d", &numero);

if (eh_primo(numero) == TRUE)
    printf("SIM\n" );
else  
    printf("NAO\n" );
```

### Python
```python
#-*- coding=utf-8 -*-
from math import sqrt

def eh_primo(numero):
    if numero == 1 or  (numero % 2 == 0 and numero != 2): # 1 nao é primo
      return False # nao existe numero primo par com exceção do 2
    #para economizer vamos percorrer ate a a raiz do numero
    for value in range(2, int(sqrt(numero)) + 1, 1):
        if numero % value == 0:
            return False
    return True

numero = int (input ("Digite um numero: "))

if eh_primo(numero):
  print "Sim"
else:
  print "Nao"
```
