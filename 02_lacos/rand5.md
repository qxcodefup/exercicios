### C
```c
#include <stdlib.h>
#include <time.h>
#include <stdio.h>

int main(){
    srand(time(NULL));//inicializando a aleatoriedade
    int min = rand() % 101;
    //A melhor maneira  é definir um numero base, para fazer isso é so gerar um numero aleatorio antes de iniciar o laço com os proximos
    for(int i = 0; i < 4; i++){
        int num = rand() % 101; //Sao gerados numeros de 0 até 100
        printf("%d ", num);
        if(num < min)
            min = num;
    }
    printf("\n%d", min);
    return 0;
}
```

### Python
```python
value = int (input ())
minimo = value # O menor valor sera o primeiro que for digitado
print value,
for i in range(4):
    value = int (input ())
    print value,
    if value < minimo
        minimo = value
print minimo
```
