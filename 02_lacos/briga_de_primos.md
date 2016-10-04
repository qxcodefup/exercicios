Dado um inteiro N como entrada, determinar no conjunto {1 · · · N} a soma de todos os não-primos subtraída da soma dos primos.
### C
```c

```

### Python
```py
#opcao 1
def eh_primo(numero):
    if numero == 1:
        return False
    for value in range(2, sqrt(numero) + 1):
        if numero % value == 0 and numero != 2:
            return False
    return True
#opcao 2
def is_prime_number(numero):
    if numero == 1:
        return False
    return  len(filter(lambda x: n % x == 0, range(2, n))) == 0

numero = int (input ())
soma_primo = 0
soma_n_primo = 0

for value in range(1, numero + 1):
      if eh_primo(value):
            soma_primo += value
      else:
            soma_n_primo += value

print soma_n_primo - soma_primo
```
