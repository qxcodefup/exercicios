# C
```c++
#include <stdlib.h>
#include <time.h>
#include <stdio.h>

int main(){
    srand(time(NULL));//inicializando a aleatoriedade
    int min = 101;//precisa ser maior que o máximo
    for(int i = 0; i < 5; i++){
        int num = rand() % 101;
        printf("%d ", num);
        if(num < min)
            min = num;
    }
    printf("\n%d", min);
    return 0;
}
```
