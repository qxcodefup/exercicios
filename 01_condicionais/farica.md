_Exercicio extra: Crie duas funcoes uma para calcular o salario total e outra para o adicional._

```python  
qtd_pecas = int (input ("Digite o numero de pecas: "))

base = 440.00
adicional = 0.0

if qtd_pecas < 500:
  adicional = 0
elif qtd_pecas <= 750:
  adicional = 0.5 * (qtd_pecas - 500)
else:
  adicional = 550 + 0.75 * (qtd_pecas - 750)

salario = base + adicional

print "O salario é %.f" % salario

```
