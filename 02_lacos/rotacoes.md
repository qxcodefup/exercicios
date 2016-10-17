### C
```c
#include <math.h>

int qtd_digitos(int numero){
	int cont = 0;
	while (numero != 0) {
		numero /= 10;
		cont ++;
	}
	return cont;
}

int RD(int numero){
	int qtd = qtd_digitos(numero);
	//Encontra o primeiro digito.
	int primeiro = numero /  pow(10, (qtd - 1)); //Retiro os ultimos numeros menos o primeiro
	int novo = numero % pow (10, (qtd - 1));  // Agora com o % pego os ultimos numeros menos o primeiro
	novo *= 10; //redimensiona para caber mais um digito
	novo += primeiro; //add o digito novo
	return novo;
}

int numero;
scanf("%d", &numero);

int convertido = RD(numero);
printf("%d", convertido);

while (numero != convertido){
	int outro = convertido;
	convertido = RD(outro);
	printf("%d",  convertido);
}
```
### Python
```py
#-*- coding=utf-8 -*-
def qtd_digitos(numero):
	cont = 0
	while numero != 0:
		numero /= 10
		cont += 1
	return cont

def RD(numero):
	qtd = qtd_digitos(numero)
	# Encontra o primeiro digito.
	primeiro = numero / (10 ** (qtd - 1)) # Retiro os ultimos numeros menos o primeiro
	novo = numero % (10 ** (qtd - 1)) # Agora com o % pego os ultimos numeros menos o primeiro
	novo *= 10 # redimensiona para caber mais um digito
	novo += primeiro # add o digito novo
	return novo

numero = int (input ())

convertido = RD(numero)
print convertido

while numero != convertido:
	outro = convertido
	convertido = RD(outro)
	print convertido
```
