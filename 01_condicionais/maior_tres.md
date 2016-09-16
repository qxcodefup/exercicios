
```c
#include <stdio.h>

int maximo (int, int, int);

int main (){
	int num_a, num_b, num_c, maior;

  printf ("Digite um numero: ");
	scanf ("%d", &num_a);
	printf ("Digite um numero: ");
	scanf ("%d", &num_b);
  printf ("Digite um numero: ");
	scanf ("%d", &num_c);

	maior = maximo (num_a, num_b, num_c);

	printf ("O maior valor é %d", maior);

	return 0;
}

int maximo (int num_a,  int num_b, int num_c){
	if (num_a > num_b && num_a > num_c)
		return num_a;
  else if (num_b > num_c)
    return num_b;
	return num_c;
}

```

```c++
#include <iostream>

using namespace std;

int maximo (int,  int, int);

int main (){
	int num_a, num_b, num_c, maior;

	cout << "Digite um numero: ";
	cin >> num_a;
	cout << "Digite um numero: ";
	cin >> num_b;
  cout << "Digite um numero: ";
  cin >> num_c;

	maior  = maximo (num_a, num_b, num_c);

	cout << "O maior valor é " << maior << endl;

	return 0;
}

int maximo (int num_a,  int num_b, int num_c){
	if (num_a > num_b && num_a > num_c)
		return num_a;
  else if (num_b > num_c)
    return num_b;
	return num_c;
}

```

```python
#-*- coding=utf-8 -*-

def maior (num_a, num_b, num_c):
  if num_a > num_b and num_a > num_c:
    return num_a
  elif num_b > num_c:
    return num_b  
  return num_c

num_a = int (input ("Digite um numero: "))
num_b = int (input ("Digite um numero: "))
num_c = int (input ("Digite um numero: "))

print "O maior é %d" % maior (num_a, num_b, num_c)

```
