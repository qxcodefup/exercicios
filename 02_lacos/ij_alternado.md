## C
```c++
//opcao 1
for(int i = 0, j = 10; i <= 10; i++, j--)
    cout << i << " " << j << " ";
//opcao 2
int j = 10;
for(int i = 0; i <= 10; i++){
    cout << i << " " << j << " ";
    j--;
}
