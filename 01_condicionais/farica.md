```python
def adicional(qtd_pecas):
  if qtd_pecas < 500:
    return 0
  elif qtd_pecas <= 750:
    return 0.5 * (qtd_pecas - 500)
  else:
    return 550 + 0.75 * (qtd_pecas - 750)

def calc_salario(qtd_pecas):
  base = 440.00
  return base + adicional(qtd_pecas)

qtd_pecas = int (input ("Digite o numero de pecas: "))

print "O salario é %.f" % calc_salario(qtd_pecas)

```
