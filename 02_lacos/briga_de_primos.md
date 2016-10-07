Dado um inteiro N como entrada, determinar no conjunto {1 · · · N} a soma de todos os não-primos subtraída da soma dos primos.
### C
```c
#include <stdio.h>
#define TRUE 1
#define FALSE 0

int eh_primo(int numero){
    int i;
    if (numero == 1 || (numero % 2 == 0 && numero != 2))
        return FALSE; // 1 e os numeros pares não são primos, com exceção do 2
    for (i = 2; i < (int)sqrt(numero) + 1; i++)
        if (numero % i == 0)
            return FALSE;
    return TRUE;
}

int main(){
    int num, soma_primo = 0, soma_n_primo = 0;
    scanf("%d", &num);

    for (value = 1, value < numero + 1; value ++){
      if (eh_primo(value) == TRUE)
            soma_primo += value;
      else
            soma_n_primo += value;
    }

    printf("%d", (soma_n_primo - soma_primo));

    return 0;
}
```

### Python
```py
from math import sqrt
#opcao 1
def eh_primo(numero):
    if numero == 1 or (numero % 2 == 0 and numero != 2):
        return False
    for value in range(2, sqrt(numero) + 1):
        if numero % value == 0:
            return False
    return True
#opcao 2
def is_prime_number(numero):
    if numero == 1:
        return False
    return  len(filter(lambda x: n % x == 0, range(2, n))) == 0

numero = int (input ())
soma_primo = 0
soma_n_primo = 0

for value in range(1, numero + 1):
      if eh_primo(value):
            soma_primo += value
      else:
            soma_n_primo += value

print soma_n_primo - soma_primo
```
