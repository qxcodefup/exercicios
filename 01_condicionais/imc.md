_Exercicio extra: Crie duas funcoes uma para calcular o IMC e outra para classifica-lo_

```python

peso = float (input ("Digite o peso: "))
altura = float (input ("Digite a altura: "))

imc = peso / (altura ** 2)

if imc < 20:
  print "Magros"
elif imc > 25:
  print "Obesos"
else:
  print "Normal"

```
