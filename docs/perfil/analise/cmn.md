![UnB](../../img/unb.jpg)

# Card, Moran and Newell GOMS (CMN-GOMS)

## Definição

<p align="justify">
O CMN-GOMS é a técnica original de GOMS, onde há uma hierarquia de objetivos e os operadores são executados sequencialmente, representados como um pseudocódigo, com submétodos e condicionais (Barbosa, 2021).
</p>

<p align="justify">
O resultado dos modelos CMN-GOMS apontam a sequência de operadores, o tempo de execução e os métodos para alcançar objetivos.
</p>

<p align="justify">
A diferença para o KLM é que o CMN-GOMS é representado na forma de um programa.
</p>

## Análise

<p align="justify">
Essa análise busca mapear a sequência, operações e os métodos para o usuário realizar a tarefa de <strong>copiar o número da ambulância</strong>.
</p>

```
Goal 0: Copiar número de ambulância
  Goal 1: Encontrar o número
    OP: Levar o cursor até o botão "INFORMAÇÕES ÚTEIS"
    OP: Levar o cursor até o botão "Telefones Úteis"
    OP: Clicar com o botão esquerdo do mouse
  Goal 2: Copiar o número
    OP: Levar o cursor até o início do número da ambulância
    OP: Clicar com botão esquerdo do mouse
    OP: Levar o cursor até o final do número
    OP: Soltar o botão do mouse
    OP: Levar o cursor até a seleção
    OP: Clicar com o botão direito do mouse
    OP: Clicar em copiar
```

## Referências Bibliográficas

Livro: Barbosa, S.D.J.; Silva, B.S.; Silveira, M.S.; Gasparini, I.; Darin, T.; Barbosa, G.D.J.
(2021) Interação Humano-Computador e Experiência do Usuário.

## Versionamento

|    Data    | Versão |      Descrição      |     Autor     |
| :--------: | :----: | :-----------------: | :-----------: |
| 27/08/2021 |  1.0   | Criação do conteúdo | Irwin Schmitt |
