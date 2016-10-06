### Python
```
def Fibonacci(n):
	if n == 1: return 1
	if n <= 0: return 0
	return Fibonacci(n-1) + Fibonacci (n-2)

print Fibonacci(int(raw_input()))
```
### C

```c
#include <stdio.h>

int fibonacci(int n){
	if (n == 1 ) return 1;
	if (n == 0 ) return 0;
	return fibonacci(n-1) + fibonacci(n-2);
}

int main(int argc, char const *argv[]) {

	int n;
	scanf("%d\n",&n );

	printf("%d\n",fibonacci(n));
	return 0;
}
```
