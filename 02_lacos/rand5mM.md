### C
```c
    int min = 101;
    int max = 0;
    for(int i = 0; i < 5; i++){
        int num = rand() % 101;
        printf("%d ", num);
        if(num < min)
            min = num;
        if(num > max)
            max = num;
    }
    printf("\n%d %d", min, max);
    return 0;
}
```
### Python
```python
from random import randint
value = randint(0,100) #zera numero de 0 ate 100, inclusive o 100
print value,
minimo = value
maximo = value
for i in range(4):
    value = randint(0,100)
    print value,
    if value > maximo:
        maximo = value
    if value < minimo:
        minimo = value
print minimo
print maximo
```
