
### Python
```python
def Potencia_De_2(E):
	if E == 1 : return 2
	if E == 0 : return 1
	return 2 * Potencia_De_2(E-1)

print Potencia_De_2(int(raw_input())

```
### C
```c

#include <stdio.h>

int Potencia_De_2(int e){
	if (e == 1) return 2;
	if (e == 0) return 1;
	return 2 * Potencia_De_2(e-1);
}

int main(int argc, char const *argv[]){

	int e;
	scanf("%d", &e );

	printf("%d\n", Potencia_De_2(e));

	return 0;
}
```
