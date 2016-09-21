_Exercicio extra: Crie uma funcao que calcula a distancia entre dois pontos e outra para o calculo da colisao. A formula da distancia entre dois pontos esta na imagem abaixo e para saber a raiz, use ``` sqrt ```, e para exponenciação use ``` pow ``` para C e C++ e ``` ** ``` para Python_

![Distancia entre dois pontos](formula_distancia.jpg)

### C
```c
#include <stdio.h>
#include <math.h>

int main() {}
  int pos_1_x, pos_1_y, raio_1, pos_2_x, pos_2_y, raio_2;

  distancia =  sqrt (pow((pos_2_x - pos_1_x), 2) + pow((pos_2_y - pos_1_y) , 2))

  if (distancia < (raio_1 + raio_2))
      printf  ("True");
  else
    printf ("False");

  return 0;
}
```

### C++
```c++
#include <iostream>
#include <cmath.h>

using namespace std;

int main() {}
  int pos_1_x, pos_1_y, raio_1, pos_2_x, pos_2_y, raio_2;

  distancia =  sqrt (pow((pos_2_x - pos_1_x), 2) + pow((pos_2_y - pos_1_y) , 2))

  if (distancia < (raio_1 + raio_2))
      cout << "True" << endl;
  else
    cout << "False" << endl;

  return 0;
}
```

### Python
```python
from math import sqrt

pos_1_x = int (input ())
pos_1_y = int (input ())
raio_1 = int (input ())

pos_2_x = int (input ())
pos_2_y = int (input ())
raio_2 = int (input ())

distancia =  sqrt (((pos_2_x - pos_1_x) ** 2) + ((pos_2_y - pos_1_y) ** 2))

if distancia < (raio_1 + raio_2):
    print True
else:
  print False

```
