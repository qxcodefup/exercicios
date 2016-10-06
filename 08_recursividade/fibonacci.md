### Python
```python
def fibonacci(n):
	if n == 1 : return 1
	if n == 0 : return 0
	return fibonacci(n-1) + fibonacci(n-2)

print fibonacci(int(raw_input()) - 1)
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

	printf("%d\n",fibonacci(n-1));
	return 0;
}
```
