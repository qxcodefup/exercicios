### C
```c
int soma_pares = 0, soma_impares = 0;
while (1){  //Qualquer valor diferente de zero é tratado como verdade em C
    int numero;
    scanf("%d", &numero);
    if (numero == -1)
        break;
    if (numero % 2 == 0)
        soma_pares += numero;
    else
        soma_impares += numero;
}

printf ("%d", soma_pares - soma_impares);
```

### Python
  ```py
def is_par(numero):
      if numero % 2 == 0:
          return True
      return False

soma_pares = 0
soma_impares = 0
while True:
    numero = int (input  ())
    if numero == -1:
        break
    if is_par(numero):
        soma_pares += numero
    else:
        soma_impares += numero
print soma_pares - soma_impares    
  ```
