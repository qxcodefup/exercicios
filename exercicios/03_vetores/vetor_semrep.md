###C
```
#include <stdio.h>

int busca_linear(int vetor[], int n, int tamanho){
	int i;

	for (i = 0; i < tamanho; i++){
		if (vetor[i] == n){
			return 1;
		}
	}

	return 0;
}

int main(){
	int vetor[20];
	int i = 0;
	int value;

	while(i < 20){
		scanf ("%d" ,&value);
		if (!busca_linear(vetor, value, 20)){
			vetor[i] = value;
			i++;
		}
		else{
			printf("Elemento ja inserido, o vetor não deve ter repeticoes\n");
		}
	}

	printf("Elementos do vetor: ");
	
	for (i = 0; i < 20; i++){
		printf("%d " ,vetor[i]);
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

bool busca_linear(vector<int> vetor, int n){
	int i;

	for (i = 0; i < vetor.size(); i++){
		if (vetor[i] == n){
			return true;
		}
	}

	return false;
}

int main(){
	vector<int> vetor;
	int i = 0;
	int value;

	while(i < 20){
		cin >> value;
		if (!busca_linear(vetor, value)){
			vetor.push_back(value);
			i++;
		}
		else{
			cout << "Elemento ja inserido, o vetor não deve ter repeticoes" << endl;
		}
	}

	cout << "Elementos do vetor: "; 
	
	for (i = 0; i < 20; i++){
		cout << vetor[i] << " ";
	}

	cout << endl;

	return 0;

}
```