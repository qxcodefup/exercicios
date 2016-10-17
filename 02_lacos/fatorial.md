_Exercicio extra: Tente fazer sem usar laços. Use recursão para fazer isso_

### C
```c    
int numero; //Sera digitado pelo usuario
int fatorial = 1;
for (int value = numero; value > 0; value--)
    fatorial *= value; //O mesmo que: fatorial = fatorial * value
```

### Python
```python
numero = 0
while numero <= 0: # enquanto nao digitar um numero valido, no caso maior que zero continuara solicitando
  numero = int (input ('Digite um numero maior que zero: '))

fatorial = 1
for valor in range(numero, 1, -1):
  fatorial *= valor
print fatorial

```
