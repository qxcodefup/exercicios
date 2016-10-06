###C
```
#include <stdio.h>

int ehPrimo(int n){
	int i;
	int nDivisores = 0;

	for (i = 2; i < n; i++){
		if (n % i == 0){
			nDivisores++;
		}
	}

	if (nDivisores == 0){
		return 1;
	}
	else{
		return 0;
	}
}

int main(){
	int vetor[30];
	int i = 0;
	int j;


	for (j = 2; i < 30; j++){
		if (ehPrimo(j) == 1){
			vetor[i] = j;
			i++;
		}
	}

	printf ("A lista de primo eh: ");

	for (j = 0; j < 30; j++){
		printf ("%d " ,vetor[j]);
	}

	printf("\n");

	return 0;
}
```

###C++
```
#include <iostream>
#include <vector>

using namespace std;

bool ehPrimo(int n){
	int i;
	int nDivisores = 0;

	for (i = 2; i < n; i++){
		if (n % i == 0){
			nDivisores++;
		}
	}

	if (nDivisores == 0){
		return true;
	}
	else{
		return false;
	}
}

int main(){
	vector<int> vet;
	int i = 0;
	int j;


	for (j = 2; i < 30; j++){
		if (ehPrimo(j) == 1){
			vet.push_back(j);
			i++;
		}
	}

	cout << "A lista de primo eh: ";

	for (j = 0; j < 30; j++){
		cout << vet[j] << " ";
	}

	cout << endl;

	return 0;
}
```
