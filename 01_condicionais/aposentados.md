```python
def calcular_media(nota_1, nota_2, nota_3):
  return (nota_1 + nota_2 + nota_3) / 3

def rec_notas_e_calc_media():
  nota_1 = int (input ("Digite a nota 1: "))
  nota_2 = int (input ("Digite a nota 2: "))
  nota_3 = int (input ("Digite a nota 3: "))

  return calcular_media(nota_1, nota_2, nota_3)

aluno_1 = rec_notas_e_calc_media()
aluno_2 = rec_notas_e_calc_media()

if aluno_1 > aluno_2:
  print "Aluno 1 teve um melhor rendimento!"
else:
  print "Aluno 2 teve um melhor rendimento!"

```
