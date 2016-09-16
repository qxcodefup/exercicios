### C
```c
#include <stdio.h>

float maximo (float,  float);

int main (){
	float num_a, num_b, maior;

	printf ("Digite um numero: ");
	scanf ("%f", &num_a);
	printf ("Digite um numero: ");
	scanf ("%f", &num_b);

	maior  = maximo (num_a, num_b);

	printf ("O maior valor é %.2f", maior);

	return 0;
}

float maximo (float num_a,  float num_b){
	if (num_a > num_b)
		return num_a;
	return num_b;
}

```
### C++
```c++
#include <iostream>

using namespace std;

float maximo (float,  float);

int main (){
	float num_a, num_b, maior;

	cout << "Digite um numero: ";
	cin >> num_a;
	cout << "Digite um numero: ";
	cin >> num_b;

	maior  = maximo (num_a, num_b);

	cout.precision(3); // Mostrar os primeiros 3 numeros independente se sao decimais
	cout << "O maior valor é " << maior << endl;

	return 0;
}

float maximo (float num_a,  float num_b){
	if (num_a > num_b)
		return num_a;
	return num_b;
}

```
### Python
```python

def maior (num_a, num_b):
	if num_a > num_b:
		return num_a
	else:
		return num_b

num_a = float (input ("Digite um numero: "))
num_b = float (input ("Digite um numero: "))

print "O maior é %.2f" % maior (num_a, num_b)

```
