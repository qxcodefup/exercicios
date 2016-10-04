__

### C
```

```

### C++
```

```

### Python
```python
QUANTIDADE = 6
nota = int (input ('Digite uma nota: '))
soma = nota
menor = nota
maior = nota

for i in range(1, 8):
  nota = int (input ('Digite uma nota: '))
  soma += nota
  if nota  > maior:
    maior = nota
  if nota < menor:
    menor = nota

soma -= menor
soma -= maior

media = soma / QUANTIDADE

print media

```
