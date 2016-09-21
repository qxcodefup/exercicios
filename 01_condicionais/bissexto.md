_Exercicio extra: Crie uma funcao para o calculo_

### C
```c
#include <stdio.h>

int main() {
  int ano;
  scanf("%d", &ano );

  if (ano % 4 == 0  && (ano % 100 != 0 or ano % 400 == 0))
    printf ("SIM");
  else
    printf ("NAO");

  return 0;
}

```

### C++
```c++
#include <stdio.h>

int main() {
  int ano;
  cin >> ano;

  if (ano % 4 == 0  && (ano % 100 != 0 or ano % 400 == 0))
    cout << "SIM";
  else
    cout << "NAO";

  return 0;
}
```

### Python
```python
ano = int (input ("Digite um ano: "))

if ano % 4 == 0  and (ano % 100 != 0 or ano % 400 == 0):
  print "SIM"
else
  print "NAO"
```
