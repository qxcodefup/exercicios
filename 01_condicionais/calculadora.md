```python

def calculadora(value_1, operador, value_2):
  if operador == '+':
    return value_1 + value_2
  elif operador == '-':
    return value_1 - value_2
  elif operador == '*':
    return value_1 * value_2
  elif operador == '/':
    if value_2 == 0:
      return 0
    return value_1 / value_2
  else:
    return "Entrada Invalida!"

value_1 = int (input ("Digite um valor: "))
operador = raw_input ("Digite um operador: + - * / ")
value_2 = int (input ("Digite um valor: "))

print calculadora(value_1, operador, value_2)
```
