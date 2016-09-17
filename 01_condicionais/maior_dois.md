_Exercicio extra: Tente criar uma funcao que retorna o maior valor_

### C
```c
#include <stdio.h>

int main (){
	float num_a, num_b;

	printf ("Digite um numero: ");
	scanf ("%f", &num_a);
	printf ("Digite um numero: ");
	scanf ("%f", &num_b);

	if (num_a > num_b)
		printf ("O maior valor é %.2f", num_a);
	else
		printf ("O maior valor é %.2f", num_b);

	return 0;
}

```
### C++
```c++
#include <iostream>

using namespace std;

int main (){
	float num_a, num_b, maior;

	cout << "Digite um numero: ";
	cin >> num_a;
	cout << "Digite um numero: ";
	cin >> num_b;

	cout.precision(3); // Mostrar os primeiros 3 numeros independente se sao decimais
	if (num_a > num_b)
		cout << "O maior valor é " <<  num_a << endl;
	else
		cout << "O maior valor é " <<  num_b << endl;

	return 0;
}
```
### Python
```python
num_a = float (input ("Digite um numero: "))
num_b = float (input ("Digite um numero: "))

if num_a > num_b:
	print "O maior é %.2f" % num_a
else:
	print "O maior é %.2f" % num_b

```
