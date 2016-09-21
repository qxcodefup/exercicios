_Exercicio extra: Crie duas funcoes uma para calcular o IMC e outra para classifica-lo_

### C
```c
#include <stdio.h>
#include <math.h>

int main() {
  float peso, altura, imc;
  scanf("%f %f", &peso , &altura);

  imc = peso / pow(altura, 2);

  if (imc < 20)
    printf ( "Magros");
  else if (imc > 25)
    printf ("Obesos");
  else
    printf ("Normal");

  return 0;
}
```

### C++
```c++
#include <iostream>
#include <cmath.h>

using namespace std;

int main() {
  float peso, altura, imc;
  cin >> peso >> altura;

  imc = peso / pow(altura, 2);

  if (imc < 20)
    cout <<  "Magros";
  else if (imc > 25)
    cout << "Obesos";
  else
    cout << "Normal";

  return 0;
}
```

### Python
```python

peso = float (input ("Digite o peso: "))
altura = float (input ("Digite a altura: "))

imc = peso / (altura ** 2)

if imc < 20:
  print "Magros"
elif imc > 25:
  print "Obesos"
else:
  print "Normal"

```
