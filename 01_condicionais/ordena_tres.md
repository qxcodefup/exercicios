```python
def ordenar(num_1, num_2, num_3):
    if num_1 > num_2 and num_1 > num_3:
      if num_2 > num_3:
        print num_1, num_2, num_3
      else:
        print num_1, num_3, num_2
    elif num_2 > num_1 and num_2 > num_3:
        if num_1 > num_3:
          print num_2, num_1, num_3
        else:
          print num_2, num_1, num_3
    else:
      if num_1 > num_2:
        print num_3, num_1, num_2
      else:
        print num_3, num_2, num_1

num_1 = int(input())
num_2 = int(input())
num_3 = int(input())

ordenar(num_1, num_2, num_3)

```
