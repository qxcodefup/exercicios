
### Python
```python
#-*- coding=utf-8 -*-
from math import sqrt

def eh_primo(numero):
  if numero == 1: # 1 nao é primo
    return False
  for value in range(2, int(sqrt(numero)) + 1, 1): # nao existe numero primo par e para economizer vamos percorrer ate a metade
    if numero % value == 0:
      return False
  return True

numero = int (input ("Digite um numero: "))

if eh_primo(numero):
  print "Sim"
else:
  print "Nao"

```
