### C
```c
int valor;
scanf("%d", &valor);

valor %= 20;
if (valor < 0)
	puts( "Valor inválido!");
else{
	int qtd = valor / 100;
	if (qtd > 0)
		printf ("Nota de 100: %d", qtd);
	valor %= 100;

	qtd = valor / 50;
	if (qtd > 0)
		printf ("Nota de 50: %d", qtd);
	valor %= 50;

	qtd = valor / 20;
	if (qtd > 0)
		printf ("Nota de 20: %d", qtd);

	qtd = valor / 10;
	if (qtd > 0)
		printf ("Nota de 10: %d", qtd);
	valor %= 10;

	qtd = valor / 5;
	if (qtd > 0)
		printf ("Nota de 5: %d", qtd);
	valor %= 5;

	qtd = valor / 2;
	if (qtd > 0)
		printf ("Nota de 2: %d", qtd);
	valor %= 2;

	if (valor > 0)
		printf ("Restaram R$ %lf", valor);
}
```

### Python
```py
#-*- coding=utf-8 -*-
valor = int (input ("Digite um valor inteiro: "))

if valor < 0:
	print "Valor inválido!"
else:
	qtd = valor / 100
	if qtd > 0:
		print 'Nota de 100: ', qtd
	valor %= 100

	qtd = valor / 50
	if qtd > 0:
		print 'Nota de 50: ', qtd
	valor %= 50

	qtd = valor / 20
	if qtd > 0:
		print 'Nota de 20: ', qtd
	valor %= 20

	qtd = valor / 10
	if qtd > 0:
		print 'Nota de 10: ', qtd
	valor %= 10

	qtd = valor / 5
	if qtd > 0:
		print 'Nota de 5: ', qtd
	valor %= 5

	qtd = valor / 2
	if qtd > 0:
		print 'Nota de 2: ', qtd
	valor %= 2

	if valor > 0:
		print "Restaram R$", valor
```
