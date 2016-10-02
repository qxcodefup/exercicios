# EXERCÍCIOS DE ESTRUTURA DE DECISÃO

- **par_impar:** Elabore um programa que receba um número inteiro do usuário e informe se é par ou ímpar.  
[Respostas](01_condicionais/par_impar.md)

<details><summary>**C**</summary>

```c
#include <stdio.h>

int main() {
  int numero;
  printf("Digite um numero inteiro: ");
  scanf("%d", &numero);

  //Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
  if (numero % 2 == 0)
      printf("Par\n");
  else
      printf("Impar\n");

  return 0;
}
```

</details>

<details><summary>**Python**</summary>()

```python
numero = int(input("Digite um numero inteiro: "))
#Se um numero qualquer dividido por 2 tiver resto zero sera PAR  
if numero % 2 == 0:
  print "Par"
else
  print "Impar"
```

</details>

- **maior_dois:** Determinar o valor máximo de dois números A e B dados como entrada.  
[Respostas](01_condicionais/maior_dois.md)  

- **maior_tres:** Determinar o maior de três números inteiros dados como entrada.  
[Respostas](01_condicionais/maior_tres.md)  

- **mm_cinco:** Escreva um programa que leia cinco números inteiros e informa qual o maior e qual o menor número dentre eles.  
[Respostas](01_condicionais/mm_cinco.md)

- **resto_mm:** Dados dois números naturais como entrada, determinar o resto da divisão do maior pelo menor quando possível.  
[Respostas](01_condicionais/resto_mm.md)  

- **eh_divisivel:** Faça um algoritmo que determine se um número é divisível ou não por outro.  
[Respostas](01_condicionais/eh_divisivel.md)

- **ordena_tres:** Faça um programa que ordene três números informados pelo usuário.  
[Respostas](01_condicionais/ordena_tres.md)  

- **ordem_intruso:** Faça um programa que receba três números obrigatoriamente em ordem crescente e
um quarto número que não siga essa regra. Mostre, em seguida, os quatro números em
ordem decrescente. Suponha que o usuário digitará quatro números diferentes.  
[Respostas](01_condicionais/ordem_intruso.md)  

- **rendimento_alunos:** Dois alunos fizeram três provas. Dadas estas notas como entrada, determinar qual dos
dois alunos apresentou melhor rendimento.  
[Respostas](01_condicionais/rendimento_alunos.md)  OK

- **aposentados** Crie um sistema que receba a dezena da idade de uma pessoa e classifique quanto à
 tabela abaixo:

Idade | Categoria
------|----------
0     | Criança
10    | Adolescente
20    | Jovem
30    | Adulto
40+   | Maduro

[Respostas](01_condicionais/aposentados.md)

- **imc:** Faça um algoritmo que determina o IMC (índice da massa corpórea) de uma pessoa e indique se ela esta magra, normal ou obesa. O IMC é calculado com o peso em kg, dividido pelo quadrado da altura, em metros, IMC = Peso/Altura^2. Se o IMC é menor que 20 estamos magros. Se o IMC está acima de 25 estamos obesos. Se o IMC estiver entre 20 e 25 estamos normais.  
[Respostas](01_condicionais/imc.md)

- **fabrica:** Desenvolva um programa que permita entrar com o número de peças fabricadas por um operário e imprima seu salário. Nesta fábrica de peças, o salário base de um operário da linha de fabricação é de R$
440,00. Além do salário base, o operário tem um adicional de produtividade baseado na quantidade de peças que ele fabrica por mês que é pago segundo o critério:

Número de peças | adicional
----------------|----------
menor igual a 500| apenas o salário base;
maior que 500 mas <= 750 | R$ 0,50 por peça fabricada acima das 500;
maior que 750| recebe R$ 550,00 (fixo) mais R$ 0,75 por peça fabricada acima das 750.  
[Respostas](01_condicionais/fabrica.md)

- **calculadora** Crie uma calculadora que receba o primeiro valor, depois o operador e depois o
segundo valor. No final exiba o resultado.  
[Respostas](01_condicionais/calculadora.md)

23.  **triangulo:** O critério de existência de um triângulo é definido por,
```
| b – c | < a < b + c
```
onde a, b, c são os lados (em qualquer ordem) do triângulo analisado. Determinar se um triângulo existe ou não dados seus lados como entrada.  
[Respostas](01_condicionais/triangulo.md)

- **escaleno:** Escreva um programa que lê três números correspondentes aos comprimentos dos lados de um triângulo e decide (imprime) se o triângulo é equilátero, isósceles ou escaleno.

Tipo | Definição | Exemplo
-----|-----------|--------
Equilátero | Três lados iguais | 4, 4, 4
Isósceles | Um lado diferente dos demais | 5, 4, 4
Escaleno | Três lados diferentes | 4, 5, 6
Não é triângulo | A soma de dois lados é menor que o terceiro | 1, 1, 10

[Respostas](01_condicionais/escaleno.md)

- **bissexto:** Escreva um programa para verificar se um ano é bissexto. Um ano é bissexto se for divisível por 4 e não for divisível por 100, a não ser que seja também divisível por 400. Por exemplo, 1984 é bissexto, 1100 não é, e 2000 é bissexto.  
[Respostas](01_condicionais/bissexto.md)

- **esferas_batidas:** O tratamento de colisão é um dos principais campos de estudo em jogos eletrônicos.
Uma forma muito simples de calcular uma colisão de duas esferas é pensar na distância entre os centros. Se a distância entre os centros for menor que a soma do raio das duas então elas estão em colisão. Faça um código que receba as posições x e y de ambas as esferas e seus raios e imprima se estão ou não em colisão.  
[Respostas](01_condicionais/esferas_batidas.md)  
