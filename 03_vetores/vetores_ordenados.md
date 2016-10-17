###C

```
void merge_vetores(int A[], int B[], int C[], int tamanhoA, int tamanhoB){
int tamanhoC = tamanhoA + tamanhoB;

int i = 0;
int j = 0;

int marcadorA = 0;
int marcadorB = 0;


while (i < tamanhoC){
  if (marcadorA == tamanhoA){
    for(j = marcadorB; j < tamanhoB; j++){
      C[i] = B[j];
      i++;
    }
    break;
  }
  if (marcadorB == tamanhoB){
    for(j = marcadorA; j < tamanhoA; j++){
      C[i] = A[j];
      i++;
    }
    break;
  }
  if (A[marcadorA] < B[marcadorB]){
    C[i] = A[marcadorA];
    marcadorA++;
    i++;
  }
  else if(A[marcadorA] > B[marcadorB]){
    C[i] = B[marcadorB];
    marcadorB++;
    i++;
  }
  else{
    C[i] = A[marcadorA];
    i++;
    marcadorA++;
    C[i] = B[marcadorB];
    i++;
    marcadorB++;
  }
}

}


```
