_Exercicio extra: Tente fazer uma funcao quer retorna o maior valor_

### C
```c
#include <stdio.h>

int main (){
	int num_a, num_b, num_c;

  printf ("Digite um numero: ");
	scanf ("%d", &num_a);
	printf ("Digite um numero: ");
	scanf ("%d", &num_b);
  printf ("Digite um numero: ");
	scanf ("%d", &num_c);

	if (num_a > num_b && num_a > num_c)
			printf ("O maior valor é %d", num_a);
  else if (num_b > num_c)
    	printf ("O maior valor é %d", num_b);
	else
			printf ("O maior valor é %d", num_c);

	return 0;
}
```

### C++
```c++
#include <iostream>

using namespace std;

int main (){
	int num_a, num_b, num_c;

	cout << "Digite um numero: ";
	cin >> num_a;
	cout << "Digite um numero: ";
	cin >> num_b;
  cout << "Digite um numero: ";
  cin >> num_c;

	if (num_a > num_b && num_a > num_c)
		cout << "O maior valor é " <<  num_a << endl;
  else if (num_b > num_c)
		cout << "O maior valor é " <<  num_b << endl;
	else
		cout << "O maior valor é " <<  num_c << endl;

	return 0;
}
```
### Python
```python
#-*- coding=utf-8 -*-
num_a = int (input ("Digite um numero: "))
num_b = int (input ("Digite um numero: "))
num_c = int (input ("Digite um numero: "))

if num_a > num_b and num_a > num_c:
	print "O maior é %d" % num_a
elif num_b > num_c:
	print "O maior é %d" % num_b
else:
	print "O maior é %d" % num_c

```
