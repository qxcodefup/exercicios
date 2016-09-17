_Exercicio extra: Criar uma funcao que retorna o resto da divisao_

### C
```c
#include <stdio.h>

//unsigned int sao os numeros inteiros sem sinal, no caso nao tem valores negativos
int main() {
  unsigned int num_1, num_2;
  printf("Digte um numero natural: ");
  scanf("%d", &num_1);
  printf("Digte um numero natural: ");
  scanf("%d", &num_2);

  if (num_1 > num_2)
    printf("O resto é %d\n", num_1 % num_2);
  else
    printf("O resto é %d\n", num_2 % num_1);

  return 0;
}

```
### C++
```c++
#include <stdio.h>

//unsigned int sao os numeros inteiros sem sinal, no caso nao tem valores negativos

int main() {
  unsigned int num_1, num_2;
  printf("Digte um numero natural: ");
  cin >> num_1;
  printf("Digte um numero natural: ");
  cin >> num_2;

  if (num_1 > num_2)
    cout << "O resto é " <<  num_1 % num_2 << endl;
  else
    cout << "O resto é " <<  num_2 % num_1 << endl;

  return 0;
}
```
### Python
```python
# abs é uma funcao do python que retorna o modulo de um numero
num_1 = abs (int (input ("Digite um numero: ")))
num_2 = abs (int (input ("Digite um numero: ")))

if num_1 > num_2:
  print "O resto da divisao é %.2f" % (num_1 % num_2)
else:
  print "O resto da divisao é %.2f" % (num_1 % num_2)

```
