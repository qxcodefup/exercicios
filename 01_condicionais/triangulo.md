```python
def triangulo_exist(lado_1, lado_2, lado_3):
  if lado_1 > abs(lado_2 - lado_3) and lado_1 < (lado_2 + lado_3)
    return True
  return False

lado_1 = int (input ("Digite um lado: "))
lado_2 = int (input ("Digite um lado: "))
lado_3 = int (input ("Digite um lado: "))

print "Sim" if triangulo_exist(lado_1, lado_2, lado_3) else "Nao"
```
