###C
```
#include <stdio.h>

int busca_linear(int vetor[], int elem, int n){
	int i;
	for (i = 0; i < n; i++){
		if (vetor[i] == elem){
			return 1;
		}
	}
	return 0;
}

int uniao_vetores(int A[], int B[], int C[]){
	int i;
	int marcador = 0;

	for (i = 0; i < 5; i++){
		if (!busca_linear(C, A[i], 5)){
			C[marcador] = A[i];
			marcador++;
		}
	}


	for (i = 0; i < 5; i++){
		if (!busca_linear(C, B[i], 5)){
			C[marcador] = B[i];
			marcador++;
		}
	}

	return marcador;
}

int main(){
	int A[5];
	int B[5];
	int C[10];

	int i;
	int marcador = 0;

	for (i = 0; i < 5; i++){
		scanf ("%d" ,&A[i]);
	}

	for (i = 0; i < 5; i++){
		scanf ("%d" ,&B[i]);
	}

	printf("Uniao: ");

	marcador = uniao_vetores(A, B, C);

	for (int i = 0; i < marcador; i++){
		printf("%d " ,C[i]);
	}

	printf("\n");

	return 0;
}

```
