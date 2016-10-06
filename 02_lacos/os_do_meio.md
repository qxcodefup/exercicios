## DICA
```
    inicialize maior e menor
    inicialize total com 0
    faca 5 vezes:
        sorteie um numero
        se numero maior que maior
            ele sera o novo maior
        se numero menor que menor
            ele sera o novo menor
        aumente total do valor de numero
    retire do total o maior e o menor
    divida o total por 3
    imprima a media
}
```

### C
```c
    int min = 101;
    int max = 0;
    int total = 0;
    for(int i = 0; i < 5; i++){
        int num = rand() % 101;
        printf("%d ", num);
        if(num < min)
            min = num;
        if(num > max)
            max = num;
        total += num;
    }
    total = total - max - min;
    float media = total / 3;
    printf("\n%f", media);
    return 0;

```

### Python
```python
from random import randint
value = randint(0,100) #zera numero de 0 ate 100, inclusive o 100
print value,
minimo = value
maximo = value
total = value
for i in range(4):
    value = randint(0,100)
    print value,
    if value > maximo:
        maximo = value
    if value < minimo:
        minimo = value
    total += value
media = (total - minimo - maximo) / 3
print media
```
