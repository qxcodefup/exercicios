_Exercicio extra: Crie uma funcao para o calculo_

### C
```c
#include<stdio.h>

int main() {
  int lado_1, lado_2, lado_3;
  scanf("%d %d %d", &lado_1, &lado_2, &lado_3);

  if ( lado_1 > abs(lado_2 - lado_3) and lado_1 < (lado_2 + lado_3))
    printf ("SIM");
  else
    printf ("NAO");
  return 0;
}
```

### C++
```c++
#include<iostream>

using namespace std;

int main() {
  int lado_1, lado_2, lado_3;
  cin >> lado_1 >> lado_2 >> lado_3;

  if ( lado_1 > abs(lado_2 - lado_3) and lado_1 < (lado_2 + lado_3))
    cout << "SIM";
  else
    cout << "NAO";
  return 0;
}
```

### Python
```python
lado_1 = int (input ("Digite um lado: "))
lado_2 = int (input ("Digite um lado: "))
lado_3 = int (input ("Digite um lado: "))

if lado_1 > abs(lado_2 - lado_3) and lado_1 < (lado_2 + lado_3)
  print "SIM"
else:
  print "NAO"
```
