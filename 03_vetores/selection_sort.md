###C
```
void selection_sort(int vetor[], int n){
	int i, j;
	int aux;

	for (i = 0; i < n; i++){
		for (j = i+1; j < n; j++){
			if (vetor[i] > vetor[j]){
				aux = vetor[i];
				vetor[i] = vetor[j];
				vetor[j] = aux;
			}
		}
	}
}

```
