###C
```
#include <stdio.h>

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
  float media = somatorio / tamanho;

	printf ("A media eh: %f\n" ,media);


	return 0;
}

```
