###C
```c
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
```cpp
#include <iostream>

using namespace std;

void ler(int vet[], int tam){
    for (int i = 0; i < tam; ++i)
        cin >> vet[i];
}

void mostrar(int vet[], int tam){
    for (int i = 0; i < tam; ++i)
        cout << vet[i] << endl;
}

void sswap(int &value, int &value2){
    int aux = value;
    value = value2;
    value2 = aux;
}

int main()
{
    int tam;
    cin >> tam;

    int vet[];
    ler(vet, tam);

    for (int i = 0; i < tam/2; ++i)
        sswap(vet[i], vet[(tam - 1) - i]);

    mostrar(vet, tam);

    return 0;
}
```

### Python
```py
tam = int (input ())
numeros = []
for i in range(tam):
	num = int (input ())
	numeros.append(num)

numeros = numeros[::-1]

for value in numeros:
	print value,
```
