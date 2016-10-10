### C
```c
int numero, digito;
scanf("%d %d",  &numero, &digito);

int contador = 0;
while (numero != 0) {
    int resto = numero % 10;
    if (resto == digito)
        contador ++;
    numero /= 10
}
printf("%d\n", contador);
```
### Python
```py
num = int (input ())
digito = int (input ())
contador = 0
while num ! = 0:
      resto = num % 10 # pego o ultimo digito
      if resto == digito:
          contador += 1
      num /= 10    #removo o ultimo digito pois nao necessito mais dele
print contador
```
