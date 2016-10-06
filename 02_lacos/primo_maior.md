### C
```c
#include <math.h>
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
    int num;
    scanf("%d", &num);

    for (int value = num - 1; value > 1; value -= 1)
        if eh_primo(value) == TRUE:
            printf("%d", value);
            break;

}
```

### Python
```py
def eh_primo(numero):
    if numero == 1 or (numero % 2 == 0 and numero != 2):
        return False
    for value in range(2, int(sqrt(numero) + 1)):
        if numero % value == 0:
            return False
    return True

num = int (input ())
for value in range(num - 1, 1, -1):
    if eh_primo(value):
        print value
        break
```
