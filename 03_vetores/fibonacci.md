###C
```

#include <stdio.h>

int main(){
	int nTermos, i;

	printf ("Digite o numero de termos\n");

	scanf ("%d" ,&nTermos);

	int vetor[nTermos];

	vetor[0] = 0;
	vetor[1] = 1;

	for (i = 2; i < nTermos; i++){
		vetor[i] = vetor[i-1] + vetor[i-2];
	}

	printf("Termos: ");

	for (i = 0; i < nTermos; i++){
		printf ("%d " ,vetor[i]);
	}

	printf ("\n");

	return 0;
}

```

###C++
```

#include <iostream>
#include <vector>

using namespace std;

int main(){
	int nTermos;

	cout << "Digite o numero de termos" << endl;

	cin >> nTermos;

	vector<int> termosFib;

	termosFib.push_back(0);
	termosFib.push_back(1);

	for (int i = 2; i < nTermos; i++){
		termosFib.push_back( termosFib[i-1] + termosFib[i-2] );
	}

	cout << "Termos: ";

	for (int i = 0; i < nTermos; i++){
		cout << termosFib[i] << " ";
	}

	cout << endl;

	return 0;
}
```
