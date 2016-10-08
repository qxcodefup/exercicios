### C
```c
int mdc(int num_a, int num_b){
    int resto = 0;
    while (num_b != 0)
          resto = num_a % num_b;
          num_a = num_b;
          num_b = resto;
    return num_a
  }
```
### Python
```py
def mdc(num_a,num_b):
    resto = 0
    while num_b != 0:
          resto = num_a % num_b
          num_a = num_b
          num_b = resto
    return num_a
```
