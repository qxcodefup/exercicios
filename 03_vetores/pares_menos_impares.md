###C
```
int pares_menos_impares(int vetor[], int tamanho){
  int somapares = 0;
  int somaimpares = 0;

  int i;

  for (i = 0; i < tamanho; i++){
    if(vetor[i] % 2 == 0){
      somapares = somapares + vetor[i];
    }
    else{
      somaimpares = somaimpares + vetor[i];
    }
  }

  return somapares - somaimpares;
}
```
