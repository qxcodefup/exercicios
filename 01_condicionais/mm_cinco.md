_Exercicio extra: Tente fazer duas funcoes, uma para calcular o maior valor e outra para o menor valor_

### C
```c
#include <stdio.h>

int main() {
  int numero;
 
  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //2

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
      menor = numero;

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //3

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //4

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //5

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  printf("O maior é %d e o menor é %d\n", maior, menor);

  return 0;
}

```

### C++
```c++
#include <iostream>

using namespace std;

int main() {
  int numero;

  cout << "Digite um numero inteiro: ";
  cin >> numero; //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  cout << "Digite um numero inteiro: ";
  cin >> numero; //2

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  cout << "Digite um numero inteiro: ";
  cin >> numero; //3

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  cout << "Digite um numero inteiro: ";
  cin >> numero; //4

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  cout << "Digite um numero inteiro: ";
  cin >> numero; //5

  if (numero > maior) //Se o numero for maior retorna ele
    maior = numero;

  if (numero < menor) //Se o numero for menor retorna ele
    menor = numero;

  cout << "O maior é " << maior << " e o menor é " << menor << endl;

  return 0;
}
```
### Python

```python
#-*- coding=utf-8 -*-

numero = int(input("Digite um numero inteiro: ")) #1

maior = numero #O primeiro numero ja sera o maior
menor = numero #Assim como o primeiro, o numero tambem sera o menor
numero = int(input("Digite um numero inteiro: ")) #2

if numero > old_maior: #Se o numero for maior retorna ele
  maior = numero

if numero < menor: #Se o numero for menor retorna ele
  menor = numero

numero = int(input("Digite um numero inteiro: ")) #3

if numero > old_maior: #Se o numero for maior retorna ele
  maior = numero

if numero < menor: #Se o numero for menor retorna ele
  menor = numero

numero = int(input("Digite um numero inteiro: ")) #4

if numero > old_maior: #Se o numero for maior retorna ele
  maior = numero

if numero < menor: #Se o numero for menor retorna ele
  menor = numero

numero = int(input("Digite um numero inteiro: ")) #5

if numero > old_maior: #Se o numero for maior retorna ele
  maior = numero

if numero < menor: #Se o numero for menor retorna ele
  menor = numero

print "O maior é %d e o menor é %d" % (maior, menor)

```
