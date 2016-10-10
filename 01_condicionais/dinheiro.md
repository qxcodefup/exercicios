### Python
```py
#-*- coding=utf-8 -*-
valor = int (input ("Digite um valor inteiro: "))

if valor < 0:
	print "Valor inválido!"
else:
	qtd_100 = valor / 100
	if qtd_100 > 0:
		print 'Nota de 100: ', qtd_100
	valor %= 100

	qtd_50 = valor / 50
	if qtd_50 > 0:
		print 'Nota de 50: ', qtd_50
	valor %= 50

	qtd_20 = valor / 20
	if qtd_20 > 0:
		print 'Nota de 20: ', qtd_20
	valor %= 20

	qtd_10 = valor / 10
	if qtd_10 > 0:
		print 'Nota de 10: ', qtd_10
	valor %= 10

	qtd_5 = valor / 5
	if qtd_5 > 0:
		print 'Nota de 5: ', qtd_5
	valor %= 5

	qtd_2 = valor / 2
	if qtd_2 > 0:
		print 'Nota de 2: ', qtd_2
	valor %= 2

	if valor > 0:
		print "Restaram R$", valor
```
