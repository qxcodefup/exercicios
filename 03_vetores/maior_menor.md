###C
```
#include <stdio.h>

int main(){
	int vetorA[15];
	int i;
	int nxMaior = 1;
	int nxMenor = 1;

	for (i = 0; i < 15; i++){
		printf ("Digite o numero na posicao [ %d ]: " ,i);
		scanf ("%d" ,&vetorA[i]);
	}

	int maior = vetorA[0];
	int menor = vetorA[0];

	for (i = 1; i < 15; i++){
		if (vetorA[i] == maior){
			nxMaior++;
		}
		if (vetorA[i] > maior){
			maior = vetorA[i];
			nxMaior = 1;
		}
		if (vetorA[i] == menor){
			nxMenor++;
		}
		if (vetorA[i] < menor){
			menor = vetorA[i];
			nxMenor = 1;
		}
	}

	printf( "Maior: %d\n"
			"Menor: %d\n"
			"Numero vezes que maior apareceu: %d\n"
			"Numero vezes que menor apareceu: %d\n" ,maior, menor, nxMaior, nxMenor);

	return 0;
}
```

###C++
```

#include <iostream>
#include <vector>

using namespace std;

int main(){
	vector<int> vetorA;
	int i;
	int nxMaior = 1;
	int nxMenor = 1;
	int value = 0;

	for (i = 0; i < 15; i++){
		cout << "Digite o numero na posicao [ " << i << " ]: ";
		cin >> value;
		vetorA.push_back(value);
	}

	int maior = vetorA[0];
	int menor = vetorA[0];

	for (i = 1; i < 15; i++){
		if (vetorA[i] == maior){
			nxMaior++;
		}
		if (vetorA[i] > maior){
			maior = vetorA[i];
			nxMaior = 1;
		}
		if (vetorA[i] == menor){
			nxMenor++;
		}
		if (vetorA[i] < menor){
			menor = vetorA[i];
			nxMenor = 1;
		}
	}

	cout << "Maior: " << maior << endl;
	cout << "Menor: " << menor << endl;
	cout << "Numero vezes que maior apareceu: " << nxMaior << endl;
	cout << "Numero vezes que menor apareceu: " << nxMenor << endl;

	return 0;
}
```
