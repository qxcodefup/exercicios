_Exercicio extra: Crie uma funcao para o calculo_

### Python
```python
lado_1 = int(input ())
lado_2 = int(input ())
lado_3 = int(input ())

if (lado_1 + lado_2 < lado_3) || (lado_1 + lado_3 < lado_2) || (lado_2 + lado_3 < lado_1):
  print "Invalido!"
elif lado_1 == lado_2 and lado_1 == lado_3:
  print "Equilatero"
elif lado_1 != lado_2 and lado_1 != lado_3 and lado_2 != lado_3:
  print "Escaleno"
else:
  print "Isósceles"

```
