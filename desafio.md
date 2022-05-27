Seu amigo o aconselhou a ver uma nova apresentação no teatro mais popular da cidade. Ele sabe muito sobre arte e seus conselhos geralmente são bons, mas não desta vez: a performance acabou sendo muito monótona. É tão ruim que você queira fugir, o que é bastante simples, especialmente porque a saída está localizada logo atrás de sua fileira à esquerda. Tudo que você precisa fazer é subir em seu assento e fazer o seu caminho até a saída.

O principal problema é sua timidez: você tem medo de acabar bloqueando a visão (mesmo que apenas por alguns segundos) de todas as pessoas que se sentam atrás de você e em sua coluna ou nas colunas à sua esquerda. Para ganhar coragem, você decide calcular o número dessas pessoas e ver se consegue chegar à saída sem incomodar muitas pessoas.

Dado o número total de linhas e colunas no teatro (`nRows` e `nCols`, respectivamente), e a `linha` e a `coluna` em que você está sentado, retorne o número de pessoas que se sentam estritamente atrás de você ** e** em sua coluna ou à esquerda, supondo que todos os assentos estejam ocupados.

Exemplo

For `nCols = 16`, `nRows = 11`, `col = 5`, and `row = 3`, the output should be
`solution(nCols, nRows, col, row) = 96`.

Veja como é o teatro:
![img](https://codesignal.s3.amazonaws.com/tasks/seatsInTheater/img/example.png?_tm=1618309568091)

- Entrada/Saída

  - **[limite de tempo de execução] 4 segundos (js)**

  - **[input] inteiro nCols**

    Um número inteiro, o número de colunas do teatro.

    *Restrições garantidas:*
    `1 ≤ nCols ≤ 1000`.

  - **[input] inteiro nRows**

    Um número inteiro, o número de linhas do teatro.

    *Restrições garantidas:*
    `1 ≤ nLinhas ≤ 1000`.

  - **[input] inteiro col**

    Um número inteiro, o número da coluna do seu próprio assento (baseado em 1).

    *Restrições garantidas:*
    `1 ≤ col ≤ nCols`.

  - **[input] linha inteira**

    Um número inteiro, o número da linha do seu próprio assento (baseado em 1).

    *Restrições garantidas:*
    `1 ≤ linha ≤ nLinhas`.

  - **[saída] inteiro**

    O número de pessoas que se sentam estritamente atrás de você **e** na sua coluna ou à esquerda.