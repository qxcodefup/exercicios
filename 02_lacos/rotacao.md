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

int RE(int numero){
	int novo = numero % 10; //pega o ultimo numero
	numero /= 10; # Retira o ultimo digito
	espaco_para_novo_numero = pow(10, qtd_digitos(numero));
	novo *= espaco_para_novo_numero; //redimensiona
	novo += numero; //Add os numeros restantes
	return novo;
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

def RE(numero):
	novo = numero % 10 #pega o ultimo numero
	numero /= 10 # Retira o ultimo digito
	espaco_para_novo_numero = 10 ** qtd_digitos(numero)
	novo *= espaco_para_novo_numero # redimensiona
	novo += numero #Add os numeros restantes
	return novo

num = int (input ())

print 'RE', RE(num)

print 'RD', RD(num)

''' ABAIXO ESTA UMA VERSAO GAMBIARROSA E COM BAIXA LEGIBILIDADE '''
''' 	POR FAVOR NAO UTILIZE DESSA FORMA EM SEUS ALGORITMOS	'''
#Versao modo gamb
def rd(numero):
	qtd = qtd_digitos(numero)
	return ((numero % (10 ** (qtd - 1))) * 10) + numero / (10 ** (qtd - 1))

#Versao modo gamb
def re(numero):
	qtd = qtd_digitos(numero)
	return ((numero % 10) * (10 ** (qtd - 1))) + ((numero / 10) % (10 ** (qtd - 1)))
```
