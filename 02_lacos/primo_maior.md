### Python
```py
def eh_primo(numero):
    if numero == 1:
        return False
    for value in range(2, sqrt(numero) + 1):
        if numero % value == 0 and numero != 2:
            return False
    return True

num = int (input ())
for value in range(num - 1, 1, -1):
    if eh_primo(value):
        print value
        break
```
