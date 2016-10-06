###C
```

#include <stdio.h>

int main(){
	int vetor[10];
	int i = 0;
	int ler = 1;
	int elem;
	int encontrado = 0;
	int indice = -1;

	printf("Digite os 10 elementos positivos do vetor\n");

	for (i = 0; i < 10; i++){
		printf("Insira o valor na posicao [ %d ]: " ,i);
		scanf ("%d" ,&vetor[i]);
	}

	while(ler >= 0){

		printf("\nDigite o elem que deseja buscar\n");
		scanf ("%d" ,&elem);

		for (i = 0; i < 10; i++){
			if (vetor[i] == elem){
				encontrado = 1;
				indice = i;
				break;
			}
		}

		if (encontrado){
			printf("Elemento encontrado no indice [%d]\n" ,indice);
		}

		else{
			printf("Elemento nao encontrado!\n");
		}

		printf("\nDigite um numero negativo para sair, ou qualquer outro numero nao negativo para continuar procurando\n");
		scanf ("%d" ,&ler);

	}

	return 0;
}

```

###C++
```
#include <iostream>
#include <vector>

using namespace std;

int main(){
	vector<int> vetor;
	int ler = 1;
	int elem;
	bool encontrado;
	int indice = -1;
	int value;

	cout << "Digite os 10 elementos positivos do vetor" << endl;

	for (int i = 0; i < 10; i++){
		cout << "Insira o valor na posicao [ " << i << " ]: ";
		cin >> value;
		vetor.push_back(value);
	}

	while(ler >= 0){

		cout << endl << "Digite o elem que deseja buscar" << endl;
		cin >> elem;

		for (int i = 0; i < 10; i++){
			if (vetor[i] == elem){
				encontrado = true;
				indice = i;
				break;
			}
		}

		if (encontrado){
			cout << "Elemento encontrado no indice: " << indice << endl;
		}

		else{
			cout << "Elemento nao encontrado!" << endl;
		}

		cout << endl << "Digite um numero negativo para sair, ou qualquer outro numero nao negativo para continuar procurando" << endl;
		cin >> ler;

	}

	return 0;
}
```