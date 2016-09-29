# Exercícios de Repetição

As atividades devem usar apenas laço. Não use vetores para nenhuma delas. Nosso objetivo é aprimorar nosso domínio de laço.

Clique no título da questão para ver as respostas [C, C++, Python].

Sugestão: use o google-chrome.

---

## Controle Básico
**[0a20:](02_lacos/0a20.md)**
Faça um laço que mostre os números ímpares entre 0 e 20.

    1 3 5 ... 19

**[1a31:](02_lacos/1a31.md)**
Faça um laço para imprimir de 1 a 31, de 3 em 3

    1 4 7 10 ... 31


**[10a2neg:](02_lacos/10a2neg.md)**
Um laço para imprimir de 10 até 0 de 2 em 2

    10 8 6 4 2 0


**ij_alternado:** Com dois contadores, imprima 'i' indo de 0 até 10 enquanto 'j' vai de 10 até 0. Em um mesmo laço, a cada interação incremente 'i' e decremente 'j'. Imprima ambos.

    [0 10] [1 9] [2 8] ... [8 2] [9 1] [10 0]
[Respostas](02_lacos/ij_alternado.md)  

**so_i:** Faça o exercício anterior usando apenas um contador.

    dica: imprima << i << " " << (10 - i)
[Respostas](02_lacos/so_i.md)  

## Rand e Busca
**rand5:** Usando um laço, sorteie 5 números entre 0 e 100, imprima-os, e no final, mostre o menor.

    20 43 15 18 91 12
    12
[Respostas](02_lacos/rand5.md)  


**rand5mM:** Usando um laço apenas, sorteie 5 números e mostre ao final o menor e o maior.
    20 43 15 18 91 12
    12 43
[Respostas](02_lacos/rand5mM.md)  

---
**os_do_meio:** Usando um laço apenas, sorteie 5 números. Retire o maior e o menor e mostre a média dos que sobraram. Dica: some todos e depois subtraia do maior e do menor
[Respostas](02_lacos/os_do_meio.md)  


---
### Pegar números do usuários até ele digitar -1, depois imprima a média.

<details><summary>C</summary>
```c
    int qtd = 0;
    int soma = 0;
    int num;//o numero do usuario
    while(num != -1){
        puts("Digite um numero, -1 para sair");
        scanf("%d", &num);
        if(num == -1)
            break;
        total += num;
        qtd++;
    }
    printf("%f", (total/(float)qtd));
    return 0;
```
</details>

---

### Dado um número qualquer, imprima ao contrario.
    >> 574839
    << 938475

<details><summary>DICA</summary>
```DICA
    leia numero
    enquanto numero for diferente de zero
        unidade eh numero modulo 10
        imprima unidade
        divida o numero por 10
```
</details>

<details><summary>C</summary>
```c
    int num = 0;
    scanf("%d", num);
    while(num != 0){
        printf("%d", (num % 10));
        num = num / 10;
    }
```
</details>

---
### Dado um número e uma posição, retorne o dígito correspondente. 0 para unidade, 1 para dezena, 2 para centena, etc.
    >> 3652 2
    << 6

<details><summary>C</summary>
```c
    int num = 0;
    int digito;
    scanf("%d %d", num, digito);
    for(int i = 0; i < digito; i++)
        num = num / 10;
    printf("%d", (num % 10));
```
</details>




- **fatorial:** Escreva um programa que leia um número N, inteiro maior que zero, e calcule o fatorial desse número.  
[Respostas](02_lacos/fatorial.md)

- **potencia:** Sejam a e b dois números naturais. Determinar o valor da potência a b dados a e b como entrada.  
[Respostas](02_lacos/potencia.md)

- **juizes:** Numa competição de natação, oito juízes dão notas entre 0 e 10. Das notas recebidas, a menor e a maior são descartadas, e a nota do atleta é dada pela média entre as seis notas restantes. Faça um programa que receba as oito notas dos juízes e apresente a nota do atleta.  
[Respostas](02_lacos/juizes.md)

**500_impares:** Imprimir números naturais ímpares menores que 500.  
[Respostas](02_lacos/500_impares.md)

**500_pares:** Imprimir números naturais pares menores que 500 em ordem decrescente. Nesse caso não iremos considerar o zero.
[Respostas](02_lacos/500_pares.md)

**200_primeiros:** Determinar a soma dos primeiros 200 números naturais que sejam divisíveis por 3 mas que não sejam divisíveis por 7.  
[Respostas](02_lacos/200_primeiros.md)


**ate_negativo:** Escreva um programa que receba números inteiros do usuário até ele digitar um número negativo. Quando isso acontecer, o programa deve apresentar a quantidade, a soma e a média dos números positivos.
[Respostas](02_lacos/ate_negativo.md)

**trigo:** Elabore um programa que calcule o somatório do número de grãos de trigo que se pode obter num tabuleiro de xadrez, obedecendo a seguinte regra: colocar um grão de trigo no primeiro quadrado e nos quadrados seguintes o dobro do quadrado anterior. Ou seja, um no primeiro quadrado, dois no segundo, quatro no terceiro (até agora, a soma corresponde a sete grãos), até atingir o 64º quadro do tabuleiro. (Baseado no livro “O Homem que Calculava”, capítulo 16). Será que você consegue chegar ao valor correto sem estourar a capacidade da variável? (dica: teste com o tipo int, depois teste com long int )

**sequencia_1:** Faça um programa que escreva os N primeiros termos da seqüência abaixo, onde N é fornecido pelo usuário.
1, 3, 7, 15, 31, 63, 127...

**quadrado_perfeito:** Um quadrado perfeito é um número natural cuja raiz quadrada também pertence aos naturais. O conjunto dos quadrados perfeitos é {1, 4, 9, 16, 25, 36, 49, · · · }. Dado um inteiro de entrada determinar apenas com multiplicação e laço se este número é um quadrado perfeito.
[Respostas](02_lacos/quadrado_perfeito.md)



**dinheiro:** No Brasil existem notas de 2, 5, 10, 20, 50 e 100 reais. Faça um programa que, dado um valor inteiro em reais, mostre a menor combinação de notas existente para esse valor.
[Respostas](02_lacos/eh_primo.md)

## Primos

**eh_primo:** Desenvolva um programa que responda se um número é primo ou não. Um número é primo se for divisível apenas por ele e por um 1. 0 não é primo, trate como caso especial.  
[Respostas](02_lacos/eh_primo.md)

**briga_de_primos:** Dado um inteiro N como entrada, determinar no conjunto {1 · · · N} a soma de todos os não-primos subtraída da soma dos primos.
[Respostas](02_lacos/briga_de_primos.md)

**primo_maior:** Faça um programa que receba um número inteiro do usuário e exiba o maior número primo que seja menor do que o número digitado.
[Respostas](02_lacos/primo_maior.md)


## Matemática

**conversor:** Faça um conversor da base decimal para qualquer base entre 2 e 8. Mostre o resultado.

**mdc:** O máximo divisor comum, ou mdc, de dois números naturais a e b é o maior número inteiro não nulo menor que a e b e pelo qual ambos podem ser divididos (resto igual a zero). Calcule o mdc.

## Operações com inteiros

**pega_casa:** Dado um número e uma casa, retorne a casa decimal desse número. Casa 0 é unidade,
casa 1 é a dezena, casa 2 a centena, etc.

    in : 1452 2
    out: 4

**contrario:** O reverso de um número natural é o número obtido pela inversão da ordem de seus dígitos. Por exemplo, o reverso de 127 é 721. Determinar o reverso de um número natural dado como entrada.

    in : 1432
    out: 2341

**conta_digito:** Faça um programa que, dados um número inteiro n (n > 0) e um dígito d (0 ≤ d ≤ 9), determine quantas vezes d ocorre em n.

    in : 7283747 7
    out: 3

**rotacao:** A rotação de um número inteiro consiste na transferência de um dígito de uma extremidade deste número para a outra. A rotação à direita, ou RD, retira o dígito mais a esquerda e o coloca mais a direita. Por exemplo, RD(1234) = 2341. A rotação à esquerda, ou RE, retira o dígito mais a direita e o coloca mais à esquerda. Por exemplo, RE(1234) = 4123. Faça um código que dado um inteiro imprima sua rotação à direita
e sua rotação à esquerda.

    in :2341
    out:RE 3412, RD 1234

## Aleatoriedade

**palpite:** Faça um programa que apresente um palpite para um jogo da loteria. Nossa loteria consiste de seis números inteiros aleatórios entre 0 e 100.  
[Respostas](02_lacos/palpite.md)  

**adivinha:** Sorteie um número aleatório entre 0 e 100, e fique perguntando pro usuário pra ele chutar um valor e fique dizendo se é pra mais ou pra menos. Conte quantos chutes ele dá até acertar o número sorteado.
