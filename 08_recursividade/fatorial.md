### Python
``` python
def fatorial(n):
	if n <= 1 : return 1
	return n * fatorial(n-1)

print fatorial(int(raw_input()))
```

### C
``` c
#include <stadio.h>

int fatorial(int n){
	if (n <= 1) return 1;
	return n * fatorial(n-1);
}

int main(int argc, char const *argv[]) {
	int n;
	scanf("%d\n", &n );

	printf("%d\n", fatorial(n));

	return 0;
}
```
