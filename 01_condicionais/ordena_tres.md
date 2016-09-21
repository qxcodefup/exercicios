_Exercicio extra: Tente fazer uma funcao para ordenar os tres valores_

### C
```c
#include <stdio.h>

int main() {
  int num_1, num_2, num_3;
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_1);
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_1);
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_1);

  if (num_1 > num_2 && num_1 > num_3) {
    if (num_2 > num_3)
      printf("%d %d %d\n", num_1, num_2, num_3);
    else
      printf("%d %d %d\n", num_1, num_3, num_2);
  }else if (num_2 > num_1 and num_2 > num_3) {
      if (num_1 > num_3)
        printf("%d %d %d\n", num_2, num_1, num_3);
      else
        printf("%d %d %d\n", num_2, num_3, num_1);
  }else {
    if (num_1 > num_2)
      printf("%d %d %d\n", num_3, num_1, num_2);
    else
      printf("%d %d %d\n", num_3, num_2, num_1);
  }

  return 0;
}

```
### C++
```c++
#include <iostream>

using namespace std;

int main() {
  int num_1, num_2, num_3;
  cout << "Digite um numero inteiro: ");
  cin >> num_1;
  cout << "Digite um numero inteiro: ");
  cin >> num_2;
  cout << "Digite um numero inteiro: ");
  cin >> num_3;

  if (num_1 > num_2 && num_1 > num_3) {
    if (num_2 > num_3)
      cout << num_1 << " " << num_2 << " " << num_3 << endl;
    else
      cout << num_1 << " " << num_3 << " " << num_2 << endl;
  }else if (num_2 > num_1 and num_2 > num_3) {
      if (num_1 > num_3)
        cout << num_2 << " " << num_1 << " " << num_3 << endl;
      else
        cout << num_2 << " " << num_3 << " " << num_1 << endl;
  }else {
    if (num_1 > num_2)
      cout << num_3 << " " << num_1 << " " << num_2 << endl;
    else
      cout << num_3 << " " << num_2 << " " << num_1 << endl;
  }

  return 0;
}

```
### Python
```python

num_1 = int(input("Digite um numero inteiro: "))
num_2 = int(input("Digite um numero inteiro: "))
num_3 = int(input("Digite um numero inteiro: "))

if num_1 > num_2 && num_1 > num_3:
  if num_2 > num_3:
    print num_1, num_2, num_3
  else:
    print num_1, num_3, num_2
elif num_2 > num_1 and num_2 > num_3:
    if num_1 > num_3:
      print num_2, num_1, num_3
    else:
      print num_2, num_1, num_3
else:
  if num_1 > num_2:
    print num_3, num_1, num_2
  else:
    print num_3, num_2, num_1

```
