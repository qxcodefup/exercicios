### C++
```c++
//Para fazer em C so mudar os 'cout' por printf("%d", valor);
    int n = 1;
    for (int i = 1; i < 64; i++){
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
```

### Python
```python
n = 1
for i in range(1, 64):
    n *= 2
    print i, n
```
