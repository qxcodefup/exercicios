### ufc
# Exercícios de Repetição

As atividades devem usar apenas laço. Não use vetores para nenhuma delas. Nosso objetivo é aprimorar nosso domínio de laço. Nossas questões seguem um modelo que contém
- nome,
- descrição breve,
- respostas,
- modelo de entrada e saída[às vezes] e
- dicas[às vezes].

Se o modelo de clicar nas dicas não funcionar com você, atualize seu browser.
No chrome e firefox atualizados elas funcionam direitinho.

**esse_eh_o_nome_da_questao:** Aqui vai a descrição da questão.
[Aqui vai a Resposta](02_lacos/esse_eh_o_nome_da_questao.md)

    >> símbolos que representam a ENTRADA de dados.
    >> A entrada pode ter mais de uma linha.
    << símbolos que representam a SAÍDA para sua questão.

<details><summary> _Clique para ver a Dica_ </summary>
Quando tiver uma dica, que você **SÓ** deve **VER** se estiver com dificuldades para fazer a questão, ela estará dentro desse bloco.

```
    se ela for um pseudocodigo:
        entao ela estará em um bloco assim
    senão
        return 0;
```
</details>

---
## Controle Básico
**0a20:** Faça um laço que mostre os números ímpares entre 0 e 20.
[Respostas](02_lacos/0a20.md)

    << 1 3 5 ... 19

**1a31:** Faça um laço para imprimir de 1 a 31, de 3 em 3.
[Respostas](02_lacos/1a31.md)

    << 1 4 7 10 ... 31

**10a2neg:** Um laço para imprimir de 10 até 0 de 2 em 2.
[Respostas](02_lacos/10a2neg.md)

    << 10 8 6 4 2 0

**ij_alternado:** Com dois contadores, imprima 'i' indo de 0 até 10 enquanto 'j' vai de 10 até 0. Em um mesmo laço, a cada interação incremente 'i' e decremente 'j'. Imprima ambos.
[Respostas](02_lacos/ij_alternado.md)

    << [0 10] [1 9] [2 8] ... [8 2] [9 1] [10 0]

**so_i:** Gere a mesma saída do exercício anterior usando apenas um contador.
[Respostas](02_lacos/so_i.md)  

<details><summary>_Clique para ver Dica_</summary>
imprima `i e (10 - i)`
</details>

    << [0 10] [1 9] [2 8] ... [8 2] [9 1] [10 0]

**sequencia_1:** Faça um programa que escreva os 10 primeiros termos da seqüência abaixo.
[Respostas](01_lacos/sequencia_1.md)
<details><summary>_Clique para ver Dica_</summary>
Formula da sequencia é 2^k - 1
</details>

    << 1, 3, 7, 15, 31, 63, 127...

**maior_pot_2:** Utilizando um laço, descubra qual a maior potência de dois que cabe em um `int`. Depois teste com `unsigned int` e com `unsigned long int`.
[Respostas](02_lacos/maior_pot_2.md)

<details><summary>_Clique para ver Dica_</summary>
Com um laço, começe n com 1 e vá multiplicando por 2 e mostrando o resultado. Observe quando a variável chega ao seu limite.
</details>


## While

**10_primeiros:** Determinar a soma dos primeiros 10 números naturais que sejam divisíveis por 7 mas que não sejam divisíveis por 3. Observe que você precisa encontrar 10 números e não que você vai de um até 10.
[Respostas](02_lacos/10_primeiros.md)

## Maior Menor Média
**rand5:** Usando um laço, sorteie ou leia do usuário 5 números entre 0 e 100, imprima-os, e no final, mostre o menor.
[Respostas](02_lacos/rand5.md)  

    >> 20 43 15 18 91 12
    << 12

**rand5mM:** Usando um laço apenas, sorteie ou leia do usuário 5 números e mostre ao final o menor e o maior.
[Respostas](02_lacos/rand5mM.md)  

    >> 20 43 15 18 91 12
    << 12 43

**os_do_meio:** Usando um laço apenas, sorteie ou leia do usuário 5 números. Retire o maior e o menor e mostre a média dos que sobraram.
[Respostas](02_lacos/os_do_meio.md)
<details><summary>_Clique para ver Dica_</summary>
`Dica: some todos e depois subtraia o maior e o menor.`
</details>

    >> 1 3 7 9 2
    << 4

## Interação Usuário

**ate_menos_1:** Pegar números do usuários até ele digitar -1, depois imprima a média.
[Respostas](02_lacos/ate_menos_1.md)
<details><summary>_Clique para ver Dica_</summary>
```
soma pares é zero
soma impares é zero
executar ate parar
     leia um numero
     se numero for igual a -1
         parar
     se numero for par
         soma pares recebe numero
     senao
         soma impares recebe numero
 mostre soma pares menos soma impares
```
</details>  

    >> 2 8 6 4 5 -1
    << 5

**pares_menos_impares:** Pegar números do usuários até ele digitar -1, depois imprima a soma dos pares menos a soma dos impares.
[Respostas](02_lacos/pares_menos_impares.md)
<details><summary>_Clique para ver Dica_</summary>
```
 soma pares é zero
 soma impares é zero
 executar ate encontrar -1
      leia um numero
      se numero for par
          soma pares recebe numero
      senao
          soma impares recebe numero
  mostre soma pares menos soma impares
```
</details>

     >> 2 5 9 9 8 10 3 -1
     << -6

## Primos

**eh_primo:** Desenvolva um programa que responda se um número positivo é primo ou não. Um número é primo se for divisível apenas por ele e por um 1. 1 não é primo, trate como caso especial.  
[Respostas](02_lacos/eh_primo.md)
<details><summary>_Clique para ver Dica_</summary>
Cuidado com dividir por 0 no laço. Observe que para saber se é primo, você só preciso ir até a raiz quadrada do número.
```
    leia numero
    para 'i' de 1 ate raiz quadrada de N
        se resto da divisao de N por 'i' for 0
            entao não é primo
    se não foi divisivel por ninguém
        é primo
```
</details>

    >> 2
    << sim


**briga_de_primos:** Dado um inteiro N como entrada, determinar no conjunto {1 · · · N} a soma de todos os não-primos subtraída da soma dos primos.
[Respostas](02_lacos/briga_de_primos.md)

    >>  4
    <<  0

**primo_maior:** Faça um programa que receba um número inteiro do usuário e exiba o maior número primo que seja menor do que o número digitado.
[Respostas](02_lacos/primo_maior.md)

    >> 10
    << 7

## Matemática Geral

**potencia:** Sejam a e b dois números naturais. Determinar o valor da potência a ^ b dados a e b como entrada.  
[Respostas](02_lacos/potencia.md)

    >>  2 3
    << 8

**fatorial:** Escreva um programa que leia um número N, inteiro maior que zero, e calcule o fatorial desse número.  
[Respostas](02_lacos/fatorial.md)

    >> 5
    << 120

**fatorial_duplo:** O fatorial duplo de um número natural n é o produto de todos os números de 1 (ou 2)
até n, contados de 2 em 2. Dado um numero natural n calcule seu fatorial duplo. Exemplo: fatorial duplo de 8 é 8 × 6 × 4 × 2 = 384.
[Respostas](02_lacos/fatorial_duplo.md)

    >> 3
    << 3

**conversor:** Faça um conversor da base decimal para qualquer base entre 2 e 8. Mostre o resultado.
[Respostas](02_lacos/conversor.md)

**quadrado_perfeito:** Um quadrado perfeito é um número natural cuja raiz quadrada também pertence aos naturais. O conjunto dos quadrados perfeitos é {1, 4, 9, 16, 25, 36, 49, · · · }. Dado um inteiro de entrada determinar apenas com multiplicação e laço se este número é um quadrado perfeito.
[Respostas](02_lacos/quadrado_perfeito.md)

**mdc:** O máximo divisor comum, ou mdc, de dois números naturais a e b é o maior número inteiro não nulo menor que a e b e pelo qual ambos podem ser divididos (resto igual a zero). Calcule o mdc.
[Respostas](02_lacos/mdc.md)

## Operações de módulo e divisão com inteiros

**pega_casa:** Dado um número e uma casa, retorne a casa decimal desse número. Casa 0 é unidade,
casa 1 é a dezena, casa 2 a centena, etc.
[Respostas](02_lacos/pega_casa.md)

    >> 1452 2
    << 4

**contrario:** O reverso de um número natural é o número obtido pela inversão da ordem de seus dígitos. Por exemplo, o reverso de 127 é 721. Determinar o reverso de um número natural dado como entrada.
[Respostas](02_lacos/contrario.md)
<details><summary>_Clique para Dica_</summary>
```
leia numero
enquanto numero for diferente de zero
    unidade eh numero modulo 10
    imprima unidade
    divida o numero por 10
```
</details>

    >> 1432
    << 2341

**conta_digito:** Faça um programa que, dados um número inteiro n (n > 0) e um dígito d (0 ≤ d ≤ 9), determine quantas vezes d ocorre em n.
[Respostas](02_lacos/conta_digito.md)

    >> 7283747 7
    << 3

**rotacao:** A rotação de um número inteiro consiste na transferência de um dígito de uma extremidade deste número para a outra. A rotação à direita, ou RD, retira o dígito mais a esquerda e o coloca mais a direita. Por exemplo, RD(1234) = 2341. A rotação à esquerda, ou RE, retira o dígito mais a direita e o coloca mais à esquerda. Por exemplo, RE(1234) = 4123. Faça um código que dado um inteiro imprima sua rotação à direita
e sua rotação à esquerda.
[Respostas](02_lacos/rotacao.md)

    >> 2341
    << RE 3412, RD 1234

**rotacoes:** Gere todas as rotações de um número até voltar a ele mesmo.
    [Respostas](02_lacos/rotacoes.md)

    >> 43651
    << 36514 65143 51436 14365 43651

## Joguinhos

**palpite:** Faça um programa que apresente um palpite para um jogo da loteria. Nossa loteria consiste de seis números inteiros aleatórios entre 0 e 100. Será que você consegue garantir que serão seis número diferentes sem usar vetores. Provavelmente vai ter que usar 6 laços e testar manualmente se o número gerado não é igual a nenhum dos anteriores.
[Respostas](02_lacos/palpite.md)  

**advinha:** Faça o jogo da adivinhação. Sorteie um número aleatoriamente e peça para o jogador adivinhar o número. A cada chute que ele der, informe se o número correto é maior ou menor. Não permita que ele digite números fora do intervalo entre 0 e 100. Após ele acertar imprima uma mensagem de acordo com a quantidade de chutes que ele precisou. Se ele acertou com poucos chutes dê os parabéns. Se foram mais de 15, esculhambe ele. :) Brincadeira!
[Respostas](02_lacos/adivinha.md)  
