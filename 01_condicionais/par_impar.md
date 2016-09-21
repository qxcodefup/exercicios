_Exercicio extra: Tente criar uma função que verifica se um numero é par ou impar_

### C
```c
#include <stdio.h>

int main() {
  int numero;
  printf("Digite um numero inteiro: ");
  scanf("%d", &numero);

  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      printf("Par\n");
  else
      printf("Impar\n");

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
  cin >> numero;

  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      cout << "Par" << endl;
  else
      cout << "Impar" << endl;

  return 0;
}
```

### Python
```python
numero = int(input("Digite um numero inteiro: "))

#Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
if numero % 2 == 0:
  print "Par"
else
  print "Impar"

```
