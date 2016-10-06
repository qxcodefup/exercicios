## Python
``` python
def e_par(n):
	if n == 0: return True
	if n < 0: return False
	return e_par(n-2)

print e_par(int(raw_input()))
```

### C
``` c

#include <stdio.h>
#define True 1
#define False 0


int e_par(int n){
	if(n == 0) return True;
	if(n < 0) return False;
	return e_par(n-2);
}

int main(int argc, char const *argv[]){
	int n;
	scanf("%d", &n);
	printf("%d\n",e_par(n));
	return 0;
}
```
