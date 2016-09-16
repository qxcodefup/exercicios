```c
#include <stdio.h>

//unsigned int sao os numeros inteiros sem sinal, no caso nao tem valores negativos
int resto(unsigned int num_1, unsigned int num_2){
  if (num_1 > num_2)
    return num_1 % num_2;
  return num_2 % num_1;
}

int main() {
  unsigned int num_1, num_2;
  printf("Digte um numero natural: ");
  scanf("%d", &num_1);
  printf("Digte um numero natural: ");
  scanf("%d", &num_2);

  printf("O resto é %d\n", resto(num_1, num_2));

  return 0;
}

```

```c++
#include <stdio.h>

//unsigned int sao os numeros inteiros sem sinal, no caso nao tem valores negativos
int resto(unsigned int num_1, unsigned int num_2){
  if (num_1 > num_2)
    return num_1 % num_2;
  return num_2 % num_1;
}

int main() {
  unsigned int num_1, num_2;
  printf("Digte um numero natural: ");
  cin >> num_1;
  printf("Digte um numero natural: ");
  cin >> num_2;

  cout << "O resto é " << resto(num_1, num_2) << endl;

  return 0;
}
```

```python
def resto (num_1, num_2):
	if num_1 > num_2:
		return num_1 % num_2
	return num_2 % num_1

# abs é uma funcao do python que retorna o modulo de um numero
num_1 = abs (int (input ("Digite um numero: ")))
num_2 = abs (int (input ("Digite um numero: ")))

print "O resto da divisao é %.2f" % resto (num_1, num_2)

```
