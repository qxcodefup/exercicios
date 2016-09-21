_Exercicio extra: Crie uma funcao para o calculo_

### C
```c
#include <stdio.h>

int main() {
  int lado_1, lado_2, lado_3;
  scanf("%d %d %d", &lado_1, &lado_2, %lado_3);

  if ( (lado_1 + lado_2 < lado_3) || (lado_1 + lado_3 < lado_2) || (lado_2 + lado_3 < lado_1))
    printf ("Invalido!");
  else if (lado_1 == lado_2 and lado_1 == lado_3)
    printf("Equilatero");
  else if() lado_1 != lado_2 and lado_1 != lado_3 and lado_2 != lado_3)
    printf ("Escaleno");
  else
    printf ("Isósceles");

  return 0;
}
```

### C++
```c++
#include <iostream>

using namespace std;

int main() {
  int lado_1, lado_2, lado_3;
  cin >> lado_1 >> lado_2 >> lado_3);

  if ( (lado_1 + lado_2 < lado_3) || (lado_1 + lado_3 < lado_2) || (lado_2 + lado_3 < lado_1))
    cout << "Invalido!";
  else if (lado_1 == lado_2 and lado_1 == lado_3)
    cout << "Equilatero";
  else if() lado_1 != lado_2 and lado_1 != lado_3 and lado_2 != lado_3)
    cout << "Escaleno";
  else
    cout << "Isósceles";

  return 0;
}
```
### Python
```python
lado_1 = int(input ())
lado_2 = int(input ())
lado_3 = int(input ())

if (lado_1 + lado_2 < lado_3) || (lado_1 + lado_3 < lado_2) || (lado_2 + lado_3 < lado_1):
  print "Invalido!"
elif lado_1 == lado_2 and lado_1 == lado_3:
  print "Equilatero"
elif lado_1 != lado_2 and lado_1 != lado_3 and lado_2 != lado_3:
  print "Escaleno"
else:
  print "Isósceles"

```
