```python

def bissexto(ano):
  if ano % 4 == 0:
    if ano % 100 == 0 and ano % 400 != 0:
      return False
    return True
  return False

ano = int (input ("Digite um ano: "))

print bissexto(ano)
```
