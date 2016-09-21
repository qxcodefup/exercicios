_Exercicio extra: Crie duas funcoes uma para calcular o salario total e outra para o adicional com duas casas decimais_

### C
```c
#include <stdio.h>

int main() {
  int qtd_pecas, base = 440;
  float adicional = 0, salario = 0 ;
  scanf("%d", &qtd_pecas );

  if (qtd_pecas < 500)
    adicional = 0;
  else if (qtd_pecas <= 750)
    adicional = 0.5 * (qtd_pecas - 500);
  else
    adicional = 550 + 0.75 * (qtd_pecas - 750);

  salario = base + adicional;

  printf ("O salario é %.2f", salario);

  return 0;
}
```

### C++
```c++
#include <iostream>

 using namespace std;

int main() {
  int qtd_pecas, base = 440;
  float adicional = 0, salario = 0 ;
  cin >> qtd_pecas;

  if (qtd_pecas < 500)
    adicional = 0;
  else if (qtd_pecas <= 750)
    adicional = 0.5 * (qtd_pecas - 500);
  else
    adicional = 550 + 0.75 * (qtd_pecas - 750);

  salario = base + adicional;

  cout.precision(3);
  cout << "O salario é " <<  salario;

  return 0;
}
```
### Python
```python  
qtd_pecas = int (input ("Digite o numero de pecas: "))

base = 440.00
adicional = 0.0

if qtd_pecas < 500:
  adicional = 0
elif qtd_pecas <= 750:
  adicional = 0.5 * (qtd_pecas - 500)
else:
  adicional = 550 + 0.75 * (qtd_pecas - 750)

salario = base + adicional

print "O salario é %.2f" % salario

```
