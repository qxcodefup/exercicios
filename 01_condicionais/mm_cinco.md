### C
```c
#include <stdio.h>

int qual_o_maior(int numero, int old_maior){
  if (numero > old_maior) //Se o numero for maior retorna ele
    return numero;
  return old_maior;
}

int qual_o_menor(int numero, int old_menor){
  if (numero < old_menor) //Se o numero for menor retorna ele
    return numero;
  return old_menor;
}

int main() {
  int numero;

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //2
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //3
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //4
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  printf("Digite um numero inteiro: ");
  scanf("%d", &numero); //5
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  printf("O maior é %d e o menor é %d\n", maior, menor);

  return 0;
}

```

### C++
```c++
#include <iostream>

using namespace std;

int qual_o_maior(int numero, int old_maior){
  if (numero > old_maior) //Se o numero for maior retorna ele
    return numero;
  return old_maior;
}

int qual_o_menor(int numero, int old_menor){
  if (numero < old_menor) //Se o numero for menor retorna ele
    return numero;
  return old_menor;
}

int main() {
  int numero;

  cout << "Digite um numero inteiro: ";
  cin >> numero; //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  cout << "Digite um numero inteiro: ";
  cin >> numero; //2
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cout << "Digite um numero inteiro: ";
  cin >> numero; //3
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cout << "Digite um numero inteiro: ";
  cin >> numero; //4
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cout << "Digite um numero inteiro: ";
  cin >> numero; //5
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cout << "O maior é " << maior << " e o menor é " << menor << endl;

  return 0;
}
```
### Python

```python
#-*- coding=utf-8 -*-
def qual_o_maior(numero, old_maior):
  if numero > old_maior: #Se o numero for maior retorna ele
    return numero
  return old_maior

def qual_o_menor(numero, old_menor):
  if numero < old_menor: #Se o numero for menor retorna ele
    return numero
  return old_menor

numero = int(input("Digite um numero inteiro: ")) #1

maior = numero #O primeiro numero ja sera o maior
menor = numero #Assim como o primeiro, o numero tambem sera o menor
numero = int(input("Digite um numero inteiro: ")) #2
maior = qual_o_maior(numero, maior)
menor = qual_o_menor(numero, menor)

numero = int(input("Digite um numero inteiro: ")) #3
maior = qual_o_maior(numero, maior)
menor = qual_o_menor(numero, menor)

numero = int(input("Digite um numero inteiro: ")) #4
maior = qual_o_maior(numero, maior)
menor = qual_o_menor(numero, menor)

numero = int(input("Digite um numero inteiro: ")) #5
maior = qual_o_maior(numero, maior)
menor = qual_o_menor(numero, menor)

print "O maior é %d e o menor é %d" % (maior, menor)

```
