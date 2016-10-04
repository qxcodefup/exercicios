###C
```
#include <stdio.h>

int main(){
	int vetorA[6];
	int vetorB[6];
	int vetorC[12];
	int i = 0;
	int n;

	printf ("Preencha o vetor A\n");

	while (i < 6){
		printf ("Entre com um numero par: ");
		scanf ("%d" ,&n);

		if (n % 2 == 0){
			vetorA[i] = n;
			i++;
		}
		else{
			printf ("Digite somente valores pares para o vetor A!\n");
		}
	}

	i = 0;

	printf ("Preencha o vetor B\n");

	while (i < 6){
		printf ("Entre com um numero impar: ");
		scanf ("%d" ,&n);

		if (n % 2 != 0){
			vetorB[i] = n;
			i++;
		}
		else{
			printf ("Digite somente valores impares para o vetor B!\n");
		}
	}

	for (i = 0; i < 6; i++){
		vetorC[i] = vetorA[i];
	}

	int marcador = 0;

	for (i = 6; i <= 11; i++){
		vetorC[i] = vetorB[marcador];		
		marcador++;
	}

	printf ("A uniao do vetor A com o vetor B eh\n");

	for (i = 0; i < 12; i++){
		printf("%d " ,vetorC[i]);
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
	vector<int> vetorA;
	vector<int> vetorB;
	vector<int> vetorC;
	int i = 0;
	int n;

	cout << "Preencha o vetor A" << endl;

	while (i < 6){
		cout << "Entre com um numero par: " << endl;
		cin >> n;

		if (n % 2 == 0){
			vetorA.push_back(n);
			i++;
		}
		else{
			cout << "Digite somente valores pares para o vetor A!" << endl;
		}
	}

	i = 0;

	cout << "Preencha o vetor B" << endl;

	while (i < 6){
		cout << "Entre com um numero impar: " << endl;
		cin >> n;

		if (n % 2 != 0){
			vetorB.push_back(n);
			i++;
		}
		else{
			cout << "Digite somente valores pares para o vetor B!" << endl;
		}
	}

	for (i = 0; i < 6; i++){
		vetorC.push_back(vetorA[i]);
	}

	for (i = 0; i < 6; i++){
		vetorC.push_back(vetorB[i]);
	}

	cout << "A uniao do vetor A com o vetor B eh" << endl;

	for (i = 0; i < 12; i++){
		cout << vetorC[i] << " ";
	}

	cout << endl;

	return 0;
}
```