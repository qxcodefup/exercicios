Determinar a soma dos primeiros 200 números naturais que sejam divisíveis por 3 mas que não sejam divisíveis por 7.  

### C
```

```

### C++
```

```

### Python
```python
soma = 0
for num in range(200 + 1):
  if num % 3 == 0 and num % 7 != 0:
    som += num

print soma

```
