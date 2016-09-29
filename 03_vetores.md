## EXERCÍCIOS DE VETORES

## FÁCEIS

- **menor_vetor:** Leia um vetor de inteiros e imprima o menor valor.  
[Respostas](03_vetores/menor_vetor.md)
<details><summary>_Clique para Dica_</summary>
```
percorra o vetor usando uma variavel auxiliar para guardar o menor valor encontradro
sempre que achar alguem menor atualize o valor da variavel auxiliar no final o menor
valor estara armazenado na variavel auxilliar.
```
<\details>
	>> 3 7 2 4 5
	<< 2


- **fibonacci:** Crie uma função que receba a quantidade n de termos e imprima os n termos da sequência de fibonacci.
[Respostas](03_vetores/fibonacci.md)

- **busca_linear:** A Busca Linear é um processo de busca de um elemento x em um vetor L que testa sequencialmente cada elemento de L e encerra quando x é encontrado (busca com sucesso) ou quando o final de L é extrapolado(busca sem sucesso). Dados como 
entrada um vetor de números L e um número x, determinar utilizando busca linear se x está ou não presente em L.
[Respostas](03_vetores/busca_linear.md)

- **maior_menor:** Faça um programa que leia 15 números inteiros e os armazene em um vetor A. Determine então qual o maior e o menor destes números e quantas vezes este maior e este menor ocorrem no vetor. No final, apresente esses valores.
[Respostas](03_vetores/maior_menor.md)

- **vetor_reverso:** Faça um programa que receba um vetor A de 10 elementos e construa um vetor B que possui os mesmos números de A, sendo que na ordem invertida.
[Respostas](03_vetores/vetor_reverso.md)

- **vetor_primos:** Escreva um programa que determine os 30 primeiros números primos e armazene-os em um vetor chamado PRIMOS. No final, apresente o conteúdo do vetor.
[Respostas](03_vetores/vetor_primos.md)

- **uniao_vetores:** Faça um programa que leia dois vetores A e B de 6 elementos. A só deverá aceitar valores pares enquanto que B só receberá valores ímpares. O programa deve alertar caso valores errados sejam passados e pedir pro usuário informar um valor correto. Apresentar um vetor C formado pela união dos elementos de A e B (C deverá ter 12 elementos).
[Respostas](03_vetores/uniao_vetores.md)

- **iguaisa30:** Faça um programa que preencha um vetor com quinze elementos inteiros e verifique a existência de elementos iguais a 30, mostrando as posições em que apareceram.
[Respostas](03_vetores/iguaisa30.md)

- **busca_rep:** Faça um programa que receba um vetor de 10 elementos positivos e que o usuário possa pesquisar se um determinado elemento existe no vetor. Caso exista o programa exibirá o índice no qual o valor está posicionado; caso contrário, mostrar que o elemento não existe no vetor. O programa deve possibilitar que o usuário faça quantas pesquisas ele quiser, só encerrando quando o usuário informar um número negativo.
[Respostas](03_vetores/busca_rep.md)

- **vetor_semrep:** Faça um programa que receba 20 números do usuário e armazene-os em um vetor. O programa não pode aceitar valores repetidos, pedindo para o usuário informar outro número até que este apresente um número não repetido.
[Respostas](03_vetores/vetor_semrep.md)

## MÉDIAS

11. Faça um programa que preencha um vetor de dez números inteiros e um segundo vetor com cinco números inteiros, calcule e mostre dois vetores resultantes. O primeiro vetor resultante será composto pela soma dos números pares do primeiro vetor somado a cada elemento do segundo vetor. O segundo vetor resultante será composto pela soma de números impares do primeiro vetor somado com cada elemento do segundo vetor.

12. Faça um programa que leia um conjunto de quinze valores e armazene-os em um vetor. A seguir, separe-os em dois outros vetores (P e I) com cinco posições cada. O vetor P armazena números pares e o vetor I, números ímpares. Como o tamanho dos vetores pode não ser suficiente para armazenar todos os números, deve-se sempre verificar se já estão cheios. Caso P ou I estejam cheios, deve-se mostrá-los e recomeçar o preenchimento da primeira posição.
Terminado o processamento, mostre o conteúdo restante dentro dos vetores P e I.

13. Dado um vetor de números inteiros, determinar,
(a) A soma dos elementos.
(b) A média dos elementos.
(c) A soma dos elementos pares subtraída da soma dos elementos ímpares.
(d) Os valores máximo e mínimo entre seus elementos.
(e) Os dois elementos de maior valor presentes.

14. Rotacionar à direita um vetor significa colocar seus elementos uma posição adiante com exceção do último elemento que é transferido para a primeira posição. Rotacionar à esquerda um vetor significa colocar seus elementos uma posição para trás com exceção do primeiro elemento que é transferido para a última posição. Construir separadamente as rotações à direita e à esquerda para um vetor de inteiros dado como entrada.

15. Faça um programa que preencha dois vetores, X e Y com dez números inteiros cada. Calcule e mostre os seguintes vetores resultantes:
a) A união de X com Y(todos os elementos de X e de Y sem repetições);
b) A diferença entre X e Y (todos os elementos de X que não existam em Y, sem repetições);
c) A soma entre X e Y (soma de cada elemento de X com o elemento de mesma posição de em Y);
d) O produto entre X e Y (Multiplicação de cada elemento de X com o elemento de mesma posição em Y);
e) Interseção entre X e Y (Apenas os elementos que aparecem nos dois vetores, sem repetições);

17. Escreva um programa para receber 10 números reais e armazená-los em um vetor. Depois disso,  mostre  o  somatório  dos  números,  através  do  uso  da  função  somatório,  que  não recebe  parâmetro  nenhum,  acessa  o  vetor  definido  globalmente  e  retorna  o  somatório dos elementos do vetor.

18. Faça uma  função  que  receba  como  parâmetro  um  vetor  A  de  dez  elementos  inteiros  já populado  como  parâmetro.  Ao final  dessa  função,  deverá  ter  sido  gerado  um  vetor  B contendo o fatorial de cada elementos de A. O vetor B deverá ser mostrado no main.

20. Faça um programa que receba dois vetores de inteiros ordenados e imprima os valores dos vetores de maneira que eles continuem ordenados.

22. Implemente o selection sort.

23. A mediana de um conjunto finito de números é um elemento deste conjunto cuja quantidade de elementos menores ou iguais a ele é no máximo uma unidade a menos que os elementos maiores que ele. Dado um conjunto de entrada Q em forma de vetor, determinar sua mediana.

24. Dado um vetor de números naturais, reorganizar seus elementos de forma que dois números pares não fiquem vizinhos. Informar quando não for possível.

25. O embaralhamento de vetor, ou shuffle, consiste em redispor seus elementos em ordem aleatória. Dado um vetor de inteiros de entrada, embaralhar seus elementos.

27. Uma representação dígito-vetorial de um número natural n é um vetor contendo os dígitos de n justificados à direita e complementados com zeros à esquerda quando necessário. Por exemplo, a representação dígito vetorial de 15867 pode ser o vetor [1, 5, 8, 6, 7]. Dado um número natural como entrada construir sua representação dígito-vetorial.


# DIFÍCEIS

30. Um número é dito pandigital se seus dígitos são todos distintos entre si. Construir função que determine se um número passado como argumento é ou não pandigital.

35. Implemente a busca binária.
