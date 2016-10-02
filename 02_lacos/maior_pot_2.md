## C++
```c++
#include <iostream>

using namespace std;
int main()
{
    int n = 1;
    for(int i = 1; i < 64; i++){
        n *= 2;
        cout << i << " " << n << endl;
    }

    unsigned int un = 1;
    for(int i = 1; i < 64; i++){
        un *= 2;
        cout << i << " " << un << endl;
    }

    unsigned long int lint = 1;
    for(int i = 1; i < 100; i++){
        lint *= 2;
        cout << i << " " << lint << endl;
    }
    return 0;
}
```
