### C
```c
    int num = 0;
    int digito;
    scanf("%d %d", num, digito);
    for(int i = 0; i < digito; i++)
        num = num / 10;
    printf("%d", (num % 10));
```

### Python
```py
num = int (input ())
digito = int (input ())
for i in range(digito):
      num /= 10
print (num % 10)
```
