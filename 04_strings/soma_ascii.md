### C++
```c++
#include <iostream>

using namespace std;

int main()
{
    int soma = 0;
    string palavra;
    cin >> palavra;

    for (int i = 0; i < (int)palavra.length(); ++i)
        soma += (int)palavra[i];

    cout << soma << endl;

    return 0;
}
```

### Python
```py
soma = 0
palavra = raw_input('Digite uma palavra: ')

for caractere in palavra:
    soma += ord(caractere)

print soma
```
