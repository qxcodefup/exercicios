### C
```c

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
