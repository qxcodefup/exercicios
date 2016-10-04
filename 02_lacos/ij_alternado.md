## C
```c
//opcao 1
for(int i = 0, j = 10; i <= 10; i++, j--)
    printf("%d %d ", i, j);
//opcao 2
int j = 10;
for(int i = 0; i <= 10; i++){
    printf("%d %d ", i, j);
    j--;
}
```

## Python
```python
#opcao 1
j = 10
for i in range(11): # range gera um  numero de 0 até 11, mas não inclui o 11
    print i , j
    j - = 1

#opcao 2
i = 0; j = 10
while i <= 10:
    print i, j
    j -= 1
    i += 1
```
