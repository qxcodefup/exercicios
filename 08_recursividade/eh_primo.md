### Python
``` python
def eh_primo_aux(numero, comparador):
	if (numero % comparador) == 0: return False
	if comparador == 1: return True

	return eh_primo_aux(numero, comparador-1)


def eh_primo(n):
	if n == 1: return False
	return e_primo_aux(n,n-1)

print eh_primo(int(raw_input()))
```
### C

```c

#include <stdio.h>
#define False 0
#define True 1

int  eh_primo_aux(int numero, int comparador){
	if ((numero % comparador) == 0) return False;
	if (comparador == 1) return True;

	return eh_primo_aux(numero,comparador-1);
}

int  eh_primo(int numero){
	if (comparador == 1) return False;

	return eh_primo_aux(numero,numero-1);
}

int main(int argc, char const *argv[]) {

	int numero;
	scanf("%d\n", &numero );

	printf("%d\n", eh_primo(numero));

	return 0;
}
```
