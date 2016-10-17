###C

```
//a variavel marcador pode ser uma variavel global

void intersecao_vetor(int A[], int B[], int C[]){

	int i;
	int j;

	for (i = 0; i < 5; i++){
		if (busca_linear(B, A[i])){
			if (!busca_linear(C, A[i])){
			C[marcador] = A[i];
			marcador++;
			}
		}
	}

	for (i = 0; i < 5; i++){
		if (busca_linear(A, B[i])){
			if (!busca_linear(C, B[i])){
			C[marcador] = B[i];
			marcador++;
			}
		}
	}
	
}

```
