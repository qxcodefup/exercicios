```c

```

```c++

```

```python
def compara(num_1, num_2, num_3):
    if num_1 < num_2 and num_1 < num_3:
        return "P"
    if num_1 > num_2 and num_1 > num_3:
        return "G"
    else:
        return "M"

num_1 = int(input())
num_2 = int(input())
num_3 = int(input())

print compara(num_1, num_2, num_3), compara(num_2, num_1, num_3), compara(num_3, num_1, num_2)

```
