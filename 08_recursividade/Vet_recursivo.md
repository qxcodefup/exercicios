### Python
```python
def somar_print_vet_aux(index,vet):
	print vet[index]

	if (index == 9):
		return vet[index]

	return vet[index] + somar_print_vet_aux(index + 1, vet)

def soma_print_vet(vet):
	print somar_print_vet_aux(0,vet)

entrada = raw_input().split()
vet = []

for elem in entrada:
	vet.append(int(elem))

soma_print_vet(vet)
```
### C
```c
#include <stdio.h>

int somar_print_vet_aux(int index,int vet[]){
	printf("%d/n", vet[index]);

	if (index == 9)
		return vet[index];

	return vet[index] + somar_print_vet_aux(index + 1, vet)
}

int soma_print_vet(int vet[]){
	printf("%d/n", somar_print_vet_aux(0,vet));
}

int main(){

	int vet = [10],i;

	for (i = 0; i < 10; i++)
		scanf ("%d", vet[i]);

	soma_print_vet(vet);

	return 0;
}
```
