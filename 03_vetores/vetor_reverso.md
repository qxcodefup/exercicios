###C
```
#include <stdio.h>

int main(){
	int vetorA[10];
	int vetorB[10];
	int i;

	printf ("Entre com os 10 elementos do vetor A: \n");

	for (i = 0; i < 10; i++){
		scanf ("%d" ,&vetorA[i]);
	}

	for (i = 0; i < 10; i++){
		vetorB[9 - i] = vetorA[i];
	}

	printf ("O vetor B eh: \n");

	for (i = 0; i < 10; i++){
		printf("%d " ,vetorB[i]);
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
	int i;
	int value;

	cout << "Entre com os 10 elementos do vetor A: " << endl;

	for (i = 0; i < 10; i++){
		cin >> value;
		vetorA.push_back(value);
	}

	for (i = 9; i >= 0; i--){
		vetorB.push_back(vetorA[i]);
	}

	cout << "O vetor B eh: " << endl;

	for (i = 0; i < 10; i++){
		cout << vetorB[i] << " ";
	}	

	cout << endl;

	return 0;
}
```
