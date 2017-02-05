## Python

```python
# 1 solucao, para abrir a mente, complexidade O(n²)
def fibonacci_recursivo(n):
	if n < 0:
		return 0
	if n < 2:
		return n
	return fibonacci_recursivo(n - 1) + fibonacci_recursivo(n - 2)

# 2 solucao, mais eficiente que recursao, complexidade O(n)
def fibonacci_iterativo(n):
	i = 1
	j = 0
	for k in range(1, n + 1):
		t = i + j
		i = j
		j = t
	return j

# 3 solucao, mais rapida que as anteriores, complexidade O(log n)
def fibonacci_dividido(n):
	if n <= 0:
		return 0
	i = n - 1
	(a, b) = (1, 0)
	(c, d) = (0, 1)
	while i > 0:
		if not i % 2 == 0:
			(a, b) = (d * b + c * a, d * (b + a) + c * b)
		(c, d) = (c ** 2 + d ** 2, d * (2 * c + d))
		i = i / 2
	return a + b

```
