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

  scanf("%d", numero); //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  scanf("%d", numero); //2
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  scanf("%d", numero); //3
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  scanf("%d", numero); //4
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  scanf("%d", numero); //5
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  printf("%d\n", maior);
  printf("%d\n", menor);

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

  cin >> numero; //1
  int maior = numero; //O primeiro numero ja sera o maior
  int menor = numero; // Assim como o primeiro, o menor tambem sera ele

  cin >> numero; //2
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cin >> numero; //3
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cin >> numero; //4
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cin >> numero; //5
  maior = qual_o_maior(numero, maior);
  menor = qual_o_menor(numero, menor);

  cout << maior << endl;
  cout << menor << endl;

  return 0;
}
```
### Python

```python

```
