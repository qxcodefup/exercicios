### Python
```python

def SomaDig(n):
	if n == 0: return 0
	return (n%10) + SomaDig(n/10) #retira o final e chama recursivo
								  #para o numero deslocado 1 casa

print SomaDig(int(raw_input()))
```
### C
```c
#include<stdio.h>

int SomaDig(n){
	if n == 0: return 0
	return (n%10) + SomaDig(n/10)
}

int main(int argc, char const *argv[]) {
	int n;
	scanf("%d\n", &n );

	printf("%d\n", SomaDig(n));

	return 0;
}
```
