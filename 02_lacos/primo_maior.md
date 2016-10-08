### C
```c
#include <stdio.h>
#include <math.h>

#define False 0
#define True 1

int eh_primo(numero){
    if (numero == 1 || (numero % 2 == 0 && numero != 2))
        return False;
    for (int i = 3; i < sqrt(numero) + 1; i += 2)
        if (numero % i == 0)
            return False;
    return True;
}

int main(){
    int num;
    scanf("%d", &num);
    if (num < 2)
        printf("Nao possui numero primo menor!");
    else if (num == 2)
        printf("%d\n", num);
    else
        for (int i = num-1; i >= 0; i--)
            if (eh_primo(i)){
                printf("%d\n", i);
                break;
             }

    return 0;
}
```

### Python
```py
from math import sqrt

def eh_primo(numero):
    if numero == 1 or (numero % 2 == 0 and numero != 2):
        return False
    for value in range(2, int (sqrt(numero) + 1)):
        if numero % value == 0:
            return False
    return True

num = int (input ())
if num < 2:
    print "Nao possui numero primo menor!"
elif num == 2:
      print value
else:
      for value in range(num-1, 1, -1):
          if eh_primo(value):
              print value
              break
```
