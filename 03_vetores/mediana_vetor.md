###C
```
float mediana_vetor(int vetor[], int n){
  selection_sort(vetor, n);
  float mediana = 0;
  int meio = n/2;
  if (n % 2 == 0){
    mediana = vetor[meio] + vetor[meio+1];
  }
  else{
    mediana = vetor[meio];
  }

  return mediana;
}

```
