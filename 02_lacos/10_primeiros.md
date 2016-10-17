### C
```c
int contador  = 1, numero = 0, soma = 0;
while (contador <= 10){
      if (numero % 7 == 0 && numero % 3 != 0){
            soma += numero;
            contador++;
      }
      numero++;
}
```

###Python
```Python
contador = 1; numero = 0; soma = 0
while contador <= 10:
    if numero % 7 == 0 and not numero % 3 == 0:
        soma += numero
        contador += 1
    numero += 1
print soma
```
