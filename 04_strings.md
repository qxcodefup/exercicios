### ufc
# Exercicios sobre Strings
## Nivel fácil

Nas atividades a seguir, podem utilizar de todo o seu conhecimento. Nosso objetivo é aprimorar nosso domínio de Strings. Nossas questões seguem um modelo que contém
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
    << A saida pode ter mais de uma linha

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

* Dada uma string como entrada determinar a soma do código ascii de seus caracteres.

*  Escreva um programa que solicita dois números ponto flutuante do usuário e uma operação (caractere) que ele deseja realizar. O programa deve realizar a operação selecionada pelo usuário e apresentar na tela. Cuidado com divisões por zero.

* Faça um programa que receba palavras separadas por vários espaços em branco e apresente essas palavras separadas por somente um espaço.

      >> LABORATORIO        DE          PROGRAMACAO
      << LABORATORIO DE PROGRAMACAO

* Faça um programa que receba uma frase, calcule e mostre a quantidade de vogais da frase digitada. Também deve ser calculado e exibido a quantidade de palavras.

* Faça um programa para criptografar uma frase, trocando as consoantes por # e invertendo a frase.

      >> Sua casa
      << a#a# au#

* Faça um programa que receba um caractere e informe se ele é letra maiúscula, letra minúscula ou não é uma letra. Lembre-se que caracteres são representados internamente por números.

* Converter em caixa alta (caracteres alfabéticos em maiúsculo) uma string dada como entrada.

## Nivel Médio

* Faça um programa que receba uma frase e imprima a mesma frase com as palavras escritas ao contrário.

* Dada uma string ascii como entrada, substituir todos os caracteres que não sejam letras pelo caractere "#".

* Faça um programa que receba uma frase e imprima a mesma frase com as palavras repetidas.

      >> PROGRAMAR EH LEGAL
      << PROGRAMAR PROGRAMAR EH EH LEGAL LEGAL

* Faça um programa que receba palavras e separe suas silabas levando em consideração o seguinte critério: se após uma vogal existir uma não-vogal, deve-se separar a sílaba.

Exemplos | Saídas
---------|-------
Entradas   | Saídas
LABORATORIO | LA-BO-RA-TO-RIO
PIAUI | PIAUI
SOUZA | SOU-ZA
QUIPROQUO | QUI-PRO-QUO

* Faça um programa que receba uma frase e altere esta frase trocando as posições de duas letras consecutivas em uma palavra. Caso a palavra tenha número ímpar de letras, a última não será alterada.

      >> ESTA FRASE FICARA UMA BAGUNÇA SO
      << SEAT RFSAE IFACAR MUA ABUGÇNA OS

* Faça o programa do Jogo da Forca. Para cada letra que ainda não foi decifrada, o programa imprime a letra X. Caso o usuário acerte uma letra, o programa deve apresentar na palavra as ocorrências da letra e as demais permanecem com X. Se o usuário acertar a palavra, o programa apresenta “Parabéns!”, caso o usuário erre 10 vezes, o programa apresenta “Você Perdeu!” e a palavra original. (Inicie a palavra em código).

*  Uma string é um palíndromo se a sequência dos caracteres da esquerda para direita é igual à seqüência da direita para a esquerda. Por exemplo,são palíndromos "ARARA", "RADAR", "AKASAKA" e "ANA". Determinar se uma string de entrada é ou não um palíndromo.

* Um número é um palíndromo quando a ordem natural e reversa de dígitos revela o mesmo número. Por exemplo, 121, 234432. O número 585 é palíndromo nas bases 10 e base 2 (1001001001). Determinar a soma de todos os números com esta propriedade que sejam menores que um milhão.

* Dadas duas strings de entrada S e X, determinar quantas vezes X ocorre dentro de S. Por exemplo, se S = ”zzabaxdcabasabaqwertabar” e X = ”aba” então a saída deverá ser 4.
