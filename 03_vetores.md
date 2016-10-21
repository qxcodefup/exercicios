## EXERCÍCIOS DE VETORES

####Lembre-se, tenha o link de resposta como sua ultima opção!
####
```
Do or do not. There is no try.
- Yoda.
```

## FÁCEIS

**menor_vetor:** Leia um vetor de inteiros e imprima o menor valor.  
[Respostas](03_vetores/menor_vetor.md)
<details><summary>_Clique para a Dica_</summary>
```
	percorra o vetor usando uma variavel auxiliar para guardar o menor valor encontrado
	sempre que achar alguem menor atualize o valor da variavel auxiliar no final o menor
	valor estara armazenado na variavel auxilliar.
```
</details>

	>> 3 7 2 4 5
	<< 2


**fibonacci:** Crie uma função que receba a quantidade n de termos e imprima os n termos da sequência de fibonacci.
[Respostas](03_vetores/fibonacci.md)
<details><summary>_Clique para a Dica_</summary>
```
inicie as duas primeiras posicoes com 0, 1 respectivamente
depois é so fazer um loop somando a posicao vet[n-1] + vet[n-2] ate o enesimo termo
```
</details>

	>> 6
	<< 0 1 1 2 3 5

Curioso sobre a sequencia de fibbonaci? veja mais sobre https://en.wikipedia.org/wiki/Fibonacci_number

**busca_linear:** A Busca Linear é um processo de busca de um elemento x em um vetor L que testa sequencialmente cada elemento de L e encerra quando x é encontrado (busca com sucesso) ou quando o final de L é extrapolado(busca sem sucesso). Dados como
entrada um vetor de números L e um número x, determinar utilizando busca linear se x está ou não presente em L.
[Respostas](03_vetores/busca_linear.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	leia o numero
	de i <- 0 ate n-1
		se v[i] = numero
		retorne verdade
	retorne falso
```
</details>

	>> 3
	>> 2 4 3 2 5
	<< verdade

	>> 3
	>> 1 2 5 6 8
	>> falso

**maior_menor:** Faça um programa que leia 15 números inteiros e os armazene em um vetor A. Determine então qual o maior e o menor destes números e quantas vezes este maior e este menor ocorrem no vetor. No final, apresente esses valores.
[Respostas](03_vetores/maior_menor.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	uma das formas de fazer eh a seguinte
	faca menor = A[0], maior = A[0]
	percorra o vetor sempre que encontrar um valor menor que a variavel menor atualize a variavel
	da mesma forma para o maior, no final voce tera o maior e menor
	entao basta percorrer o vetor novamente contando o numero de vezes que cada uma delas aparece
```
</details>

	>> 1 3 4 5 5 2
	<< maior: 5
	<< apareceu: 2x
	<< menor 1:
	<< apareceu: 1x

**vetor_reverso:** Faça um programa que receba um vetor A de 10 elementos e construa um vetor B que possui os mesmos números de A, sendo que na ordem invertida.
[Respostas](03_vetores/vetor_reverso.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	depois de preencher o vetor A faca
	de i <- 0 até n-1 faca
		B[i] = A[n-1-i]
```
</details>

	>> 3 4 2 1 5
	<< 5 1 2 4 3

**vetor_primos:** Escreva um programa que determine os 30 primeiros números primos e armazene-os em um vetor chamado PRIMOS. No final, apresente o conteúdo do vetor.
[Respostas](03_vetores/vetor_primos.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	use uma funcao que determina se um numero eh primo
	se tiver duvidas com isto olhe esta resolucao que fizemos na secao de lacos [Resolucao eh_primo](02_lacos/eh_primo.md)
	depois disto basta fazer um laco indo de 2 ate 100 (ate la voce ja tera encontrado 30 primos)
	e sempre que encontra um numero primo atraves da funcao eh_primo adicione ao vetor, quando tiver 30 numeros pare o laco
```
</details>

	<< 2 3 5 7 11 13 17 19 23 29 31 37 41 43 47 53 59 61 67 71 73 79 83 89 97 101 103 107 109 113

**uniao_vetores:** Faça um programa que leia dois vetores A e B de 6 elementos. A só deverá aceitar valores pares enquanto que B só receberá valores ímpares. O programa deve alertar caso valores errados sejam passados e pedir pro usuário informar um valor correto. Apresentar um vetor C formado pela união dos elementos de A e B (C deverá ter 12 elementos).
[Respostas](03_vetores/uniao_vetores.md)

**iguaisa30:** Faça um programa que preencha um vetor com quinze elementos inteiros e verifique a existência de elementos iguais a 30, mostrando as posições em que apareceram.
[Respostas](03_vetores/iguaisa30.md)

**busca_rep:** Faça um programa que receba um vetor de 10 elementos positivos e que o usuário possa pesquisar se um determinado elemento existe no vetor. Caso exista o programa exibirá o índice no qual o valor está posicionado; caso contrário, mostrar que o elemento não existe no vetor. O programa deve possibilitar que o usuário faça quantas pesquisas ele quiser, só encerrando quando o usuário informar um número negativo.
[Respostas](03_vetores/busca_rep.md)

**vetor_semrep:** Faça um programa que receba 20 números do usuário e armazene-os em um vetor. O programa não pode aceitar valores repetidos, pedindo para o usuário informar outro número até que este apresente um número não repetido.
[Respostas](03_vetores/vetor_semrep.md)

## MÉDIAS

**somatorio_vetor:** Crie uma função que receba um vetor de números inteiros como parametro e retorne o somatório dos elementos. O valor deve ser mostrado na main.
[Respostas](03_vetores/somatorio_vetor.md)
<details><summary>_Clique para ver a dica_</summary>
```
	SOMATORIO(vetor, tamanho)
		para i <- 0 ate tamanho-1 faca
			somatotal = somatotal + vetor[i]

		retorne somatotal
```
</details>

	>> 5
	>> 5 10 15 20 30
	<< 80


**media_vetor:** Crie uma função que receba um vetor de números inteiros como parametro e retorne a media dos elementos.
O valor deve ser mostrado na main.
[Respostas](03_vetores/media_vetor.md)
<details><summary>_Clique para ver a dica_</summary>
```
	faca uso da funcao somatorio vista acima.
	depois disto é só dividir o somatorio pelo numero de elementos
```
</details>

	>> 4
	>> 2.0 5.0 2.5 2.5
	<< 3.0


**pares_menos_impares:** Crie uma funcao que recebar um vetor de inteiros como entrada e retorne a soma dos elementos pares subtraida da soma dos elementos impares.
O valor deve ser mostrado na main.
[Respostas](03_vetores/pares_menos_impares.md)
<details><summary>_Clique para ver a dica_</summary>
```
	SOMA_PARES(vetor, tamanho)
		para i <- 0 ate tamanho-1 faca
			se vetor[i] divido por 2 resta 0
				somapares = somapares + vetor[i]
			se nao
				somaimpares = somaimpares + vetor[i]
	retorne somapares - somaimpares

```
</details>

	>> 5
	>> 2 4 8 1 3
	<< 10

**rotacao_direita:** Crie a funcao que rotacione um vetor a direita, isso significa colocar seus elementos uma posição adiante com exceção do último elemento que é transferido para a primeira posição.
Depois de usar a função mostre o vetor na main.
[Respostas](03_vetores/rotacao_direita.md)

**uniao_vetores:** Faça um programa que preencha dois vetores A e B com 5 numeros inteiros cada e faça a união de A e B em um vetor C, tal que C não contem elementos repetidos.
[Respostas](03_vetores/uniao_semrep.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	percorra o vetor A, e para cada elemento de A chame a funcao auxiliar busca linear passando como o parametro o vetor C, se a busca retornar sucesso é porque o elemento é repetido, caso contrario basta inserir o valor no final de C (para isso use um marcador que guardara o indice da ultima posicao)
	faca o mesmo procedimento para o vetor B.
```
</details>

	>> 1 2 3 4 5
	>> 1 2 3 6 2
	<< 1 2 3 4 5 6

	>> 1 2 3 4 4
	>> 1 1 1 2 3
	<< 1 2 3 4

**intersecao_vetores:** Faça um programa que preencha dois vetores A e B com 5 numeros inteiros cada e faça a interseção de A e B em um vetor C, note que não pode haver elementos repetidos no vetor C.
[Respostas](03_vetores/intersecao_semrep.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	use uma variavel auxiliar para guardar onde deve se adicionar o proximo elemento no vetor C.
	use a busca_linear para facilitar.

	primeiro faca
		para i <- 0 ate 5 faca
			se busca_linear(B, A[i]) && !busca_linear(C, A[i]) = verdade faca
				C[marcador] = A[i]
				marcador++

	depois basta fazer o mesmo para o vetor B
		para i <- 0 ate 5 faca
			se busca_linear(A, B[i]) && !busca_linear(C, B[i]) = verdade faca
				C[marcador] = B[i]
				marcador++
```
</details>

	>> 1 2 3 4 5
	>> 5 4 3 9 9
	<< 3 4 5

**vetores_ordenados:** Faca um programa que receba dois vetores ordenados e faca um merge dos dois em um novo vetor C de forma que o vetor C continue ordenado.
[Respostas](03_vetores/vetores_ordenados.md)
<details><summary>_Clique para ver a Dica_</summary>
```
	use um marcador para o vetor A, outro para o vetor B.
	enquanto o vetor C nao for preenchido faca
		se marcador A = tamanho A (isto indica que o vetor A ja foi totalmente checado)
			coloque o restante do vetor B no vetor C.
		se marcador B = tamanho B
			coloque o restante do vetor A no vetor C.
		se nao faca
			se A[marcadorA] < B[marcadorB]
				C[i] = A[marcadorA]
				marcadorA++
				i++;
			se nao se A[marcadorA] > B[marcadorB]
				C[i] = B[marcadorB]
				marcadorB++
				i++;
			se nao (caso sejam iguais)
				C[i] = A[marcadorA]
				i++
				marcadorA++
				C[i] = B[marcadorB]
				i++
				marcadorB++

```

</details>

	>> 1 2 3 4 5
	>> 3 4 9 12 13
	<< 1 2 3 3 4 4 5 9 12 13

	>> 1 1 1 1 6
	>> 4 5 6 7 8
	<< 1 1 1 1 4 5 6 6 7 8


**selection_sort:** Implemente o algoritmo selection sort.
[Respostas](03_vetores/selection_sort.md)
<details><summary>_Clique para ver a Dica_</summary>
```
para i <- 0 ate n faca
	para j <- i+1 ate n faca
	 se vetor[i] > vetor[j]
	 	troque vetor[i] <-> vetor[j]
```

</details>

	>> 1 3 5 2 6 4
	<< 1 2 3 4 5 6

**mediana_vetor:** Dado um vetor de tamanho n determinar a mediana deste vetor, lembre-se que a mediana é o elemento que separa a metade superior e a metade inferior, note que o vetor deve estar ordenado para isto.
[Respostas](03_vetores/mediana_vetor.md)
<details><summary>_Clique para ver a Dica_</summary>
```
comece ordenando o vetor
voce pode usar a funcao selection_sort vista anteriormente
depois de ordenar basta olhar se o numero de elementos for impar pegue o elemento na posicao |_n/2_| + 1
caso seja par pegue os elementos na posicao n/2 e n/2 + 1 e faca a media destes elementos

```
</details>

	>> 1 4 2 3 5
	<< 3.0

	>> 1 2 9 3 5 4
	<< 3.5

24. Dado um vetor de números naturais, reorganizar seus elementos de forma que dois números pares não fiquem vizinhos. Informar quando não for possível.

25. O embaralhamento de vetor, ou shuffle, consiste em redispor seus elementos em ordem aleatória. Dado um vetor de inteiros de entrada, embaralhar seus elementos.

27. Uma representação dígito-vetorial de um número natural n é um vetor contendo os dígitos de n justificados à direita e complementados com zeros à esquerda quando necessário. Por exemplo, a representação dígito vetorial de 15867 pode ser o vetor [1, 5, 8, 6, 7]. Dado um número natural como entrada construir sua representação dígito-vetorial.


# DIFÍCEIS

30. Um número é dito pandigital se seus dígitos são todos distintos entre si. Construir função que determine se um número passado como argumento é ou não pandigital.

**busca_binaria:** Implemente a busca binária, note que você pode optar por retornar o indice ou um booleano.
[Respostas](03_vetores/busca_binaria.md)
<details><summary>_Clique para ver a Dica_</summary>
```
busca_binaria(A, n, elem)
	p <- 0
	r <- n + 1
	enquanto p <- r-1 faca
		q <- |_(p+r)/2_|
		se A[q] < x
			entao p <- q
			senao r <- q
	retorne r
```
</details>

	>> 1 2 3 4 10
	>> 3
	<< verdadeiro

	>> 1 2 3 4 10
	>> 7
	<< falso
