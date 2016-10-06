###C
```
#include <stdio.h>

int main(){
	int vetor[30];
	int vetorAux[30];
	int i = 0;
	int marcador = 0;

	printf ("Preencha o vetor\n");

	for (i = 0; i < 30; i++){
		printf ("Insira um valor para a posicao [ %d ]: " ,i);
		scanf ("%d" ,&vetor[i]);
	}

	for (i = 0; i < 30; i++){
		if (vetor[i] == 30){
			vetorAux[marcador] = i;
			marcador++;			
		}
	}

	printf ("Indices do vetor iguais a 30: \n");

	for (i = 0; i < marcador; i++){
		printf("%d " ,vetorAux[i]);
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

int main(){
	vector<int> vetor;
	vector<int> vetorAux;
	int value;

	cout << "Preencha o vetor" << endl;

	for (int i = 0; i < 30; i++){
		cout << "Insira um valor para a posicao [ " << i << " ]: ";
		cin >> value;
		vetor.push_back(value);
	}

	for (int i = 0; i < 30; i++){
		if (vetor[i] == 30){
			vetorAux.push_back(i);
		}
	}

	cout << "Indices do vetor iguais a 30:" << endl;

	for (int i = 0; i < vetorAux.size(); i++){
		cout << vetorAux[i] << " ";
	}

	cout << endl;

	return 0;
}
```