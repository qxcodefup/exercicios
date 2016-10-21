###C
```
int busca_binaria(int vetor[], int n, int x){
	int p;
	int q;
	int r;

	p = 0;
	r = n + 1;

	while (p < r-1){
		q = (p + r) / 2;
		if (vetor[q] < x) {
			p = q;
		}
		else{
			r = q;
		}
	}

	if (r < n){
		return 1;
	}
	else{
		return 0;
	}

}
```
