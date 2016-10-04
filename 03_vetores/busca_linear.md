###C
```
#include <stdio.h>

int main(){
	int x;
	int tamanho;
	int i;

	printf ("Digite o tamanho do vetor\n");

	scanf ("%d" ,&tamanho);

	int vetorL[tamanho];

	for (i = 0; i < tamanho; i++){
		printf("Digite o valor do vetor na posicao [ %d ]: ", i);
		scanf ("%d" ,&vetorL[i]);
	}

	printf("\nDigite o elemento a ser buscado no vetor\n");

	scanf ("%d" ,&x);

	for (i = 0; i < tamanho; i++){
		if (vetorL[i] == x){
			printf("Encontrado!\n");
			return 0;
		}
	}

	printf("Não encontrado\n");

	return 0;
}
```

###C++
```
#include <iostream>
#include <vector>

using namespace std;

int main(){
	int x;
	int tamanho;
	int i;
	int value = 0;

	cout << "Digite o tamanho do vetor" << endl;

	cin >> tamanho;

	vector<int> vetorL;

	for (i = 0; i < tamanho; i++){
		cout << "Digite o valor do vetor na posicao [ " << i << " ]: ";
		cin >> value;
		vetorL.push_back(value);
	}

	cout << endl << "Digite o elemento a ser buscado no vetor" << endl;

	cin >> x;

	for (i = 0; i < tamanho; i++){
		if (vetorL[i] == x){
			cout << "Encontrado!" << endl;
			return 0;
		}
	}

	cout << "Nao encontrado!" << endl;

	return 0;
}
```
