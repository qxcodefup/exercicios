_Exercicio extra: Cria funcao para realizar o calculo_

```python
value_1 = int (input ("Digite um valor: "))
operador = raw_input ("Digite um operador: + - * / ")
value_2 = int (input ("Digite um valor: "))

if operador == '+':
  print value_1 + value_2
elif operador == '-':
  print value_1 - value_2
elif operador == '*':
  print value_1 * value_2
elif operador == '/' and value_2 != 0:
  print value_1 / value_2
else:
  print "Entrada Invalida!"

```
