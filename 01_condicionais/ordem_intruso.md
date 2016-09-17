```python
def ordenar_decrescente(num_1, num_2, num_3, num_4):
    if num_4 < num_1:
      print num_3, num_2, num_1, num_4
    elif num_4 < num_2:
      print num_3, num_2, num_4, num_1
    elif num_4 < num_3:
      print num_3, num_4, num_2, num_1
    else:
      print num_4, num_3, num_2, num_1

num_1 = int (input ("Digite um numero: "))
num_2 = int (input ("Digite um numero maior que o anterior: "))
num_3 = int (input ("Digite um numero maior que o anterior: "))
num_4 = int (input ("Digite um numero diferente: "))

ordenar_decrescente(num_1, num_2, num_3, num_4)

```
