###C
```
#include <stdio.h>

int somatorio_vetor(int vetor[], int tam){
	int i;
	int somatorio = 0;

	for (i = 0; i < tam; i++){
		somatorio = somatorio + vetor[i];
	}

	return somatorio;
}

int main(){
	int tamanho;

	printf ("Digite o tamanho do vetor\n");
	scanf ("%d" ,&tamanho);

	int vetor[tamanho];

	printf ("Preencha o vetor\n");

	int i;

	for (i = 0; i < tamanho; i++){
		scanf ("%d" ,&vetor[i]);
	}

	int somatorio;

	somatorio = somatorio_vetor(vetor, tamanho);

	printf ("O somatorio eh: %d\n" ,somatorio);


	return 0;
}

```
