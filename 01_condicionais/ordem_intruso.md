_Exercicion extra: Tente fazer uma funcao para realizar a ordenacao de forma decrescente_

### C
```c
#include <stdio.h>

int main() {
  int num_1, num_2, num_3, num_4;
  printf("Digite um numero inteiro: ");
  scanf("%d", &num_1);
  printf("Digite um numero maior que o anterior: ");
  scanf("%d", &num_2);
  printf("Digite um numero maior que o anterior: ");
  scanf("%d", &num_3);
  printf("Digite um numero inteiro diferente: ");
  scanf("%d", &num_4);

  if (num_4 < num_1)
    printf("%d %d %d %d\n", num_3, num_2, num_1, num_4);
  else if (num_4 < num_2)
    printf("%d %d %d %d\n", num_3, num_2, num_4, num_1);
  else if (num_4 < num_3)
    printf("%d %d %d %d\n", num_3, num_4, num_2, num_1);
  else
    printf("%d %d %d %d\n", num_4, num_3, num_2, num_1);

  return 0;
}
```

### C++
```c++
#include <stdio.h>

int main() {
  int num_1, num_2, num_3, num_4;
  cout << "Digite um numero inteiro: ";
  cin >> num_1;
  cout << "Digite um numero maior que o anterior: ";
  cin >> num_2;
  cout << "Digite um numero maior que o anterior: ";
  cin >> num_3;
  cout << "Digite um numero inteiro diferente: ";
  cin >> num_4;

  if (num_4 < num_1)
    cout << num_3 << " " <<  num_2 << " " <<  num_1 << " " << num_4 << endl;
  else if (num_4 < num_2)
    cout << num_ 3<< " " <<  num_2 << " " <<  num_4 << " " << num_1 << endl;
  else if (num_4 < num_3)
    cout << num_3 << " " <<  num_4 << " " <<  num_2 << " " << num_1 << endl;
  else
    cout << num_4 << " " <<  num_3 << " " <<  num_2 << " " << num_1 << endl;

  return 0;
}
```

### Python
```python
num_1 = int (input ("Digite um numero: "))
num_2 = int (input ("Digite um numero maior que o anterior: "))
num_3 = int (input ("Digite um numero maior que o anterior: "))
num_4 = int (input ("Digite um numero inteiro diferente: "))

if num_4 < num_1:
  print num_3, num_2, num_1, num_4
elif num_4 < num_2:
  print num_3, num_2, num_4, num_1
elif num_4 < num_3:
  print num_3, num_4, num_2, num_1
else:
  print num_4, num_3, num_2, num_1

```
