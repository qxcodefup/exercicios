_Exercicio extra: Cria funcao para realizar o calculo_

### C
```c
#include <stdio.h>

int main( ){
  int value_1, value_2;
  char operador;

  scanf("%d", &value_1);
  scanf("%c", &operador);
  scanf("%d", &value_2);

  if (operador == '+')
    printf ("%d", value_1 + value_2);
  else if (operador == '-')
    printf ("%d", value_1 - value_2);
  else if (operador == '*')
    print f ("%d", value_1 *  value_2);
  else if (operador == '/' && value_2 != 0)
    printf ("%d", value_1 / value_2);
  else
    printf  ("Entrada Invalida!");

  printf("\n");
  return 0;
}
```
### C++
```c++
#include <iostream>

using namespace std;

int main( ){
  int value_1, value_2;
  char operador;

  cin >> value_1 >>  operador >> value_2;

  if (operador == '+')
    cout << value_1 + value_2;
  else if (operador == '-')
    cout << value_1 - value_2;
  else if (operador == '*')
    cout <<  value_1 *  value_2;
  else if (operador == '/' && value_2 != 0)
    cout << value_1 / value_2;
  else
    cout << "Entrada Invalida!";

  cout << endl;
  return 0;
}
```

### Python
```python
value_1 = int (input ("Digite um valor: "))
operador = raw_input ("Digite um operador: + - * / ")
value_2 = int (input ("Digite um valor: "))

if operador == '+':
  print value_1 + value_2
elif operador == '-':
  print value_1 - value_2
elif operador == '*':
  print value_1 * value_2
elif operador == '/' and value_2 != 0:
  print value_1 / value_2
else:
  print "Entrada Invalida!"

```
