![UnB](../../img/unb.jpg)

# Árvores de Tarefas Concorrentes (CTT)

## Objetivos
<p align = "justify">Criado para auxiliar a avaliação e o design de avaliação de IHC de forma hierárquica, fazendo relações entre as tarefas, classificado entre:</p>

- **Tarefas de Usuário**: Feitas fora do sistema;
- **Tarefas do sistema**: Processo do sistema, sem interagir com o usuário;
- **Tarefas interativas**: Em que ocorrem os diálogos usuário-sistema;
- **Tarefas abstratas**: que não são tarefas em si, mas uma representação de tarefas que auxilie a decomposição.

<figure>
<img align=center width="700" src="../../../img/tiposctt.png">
<br>
<figcaption>Figura 2 - Tipos de tarefas CTT, retirado de [1].</a></figcaption>
</figure>

<p align = "justify">Para relacionar os tipos de tarefas utilizaremos as seguintes ferramentas:</p>

**Ativação**: Determina que uma tarefa só pode iniciar após uma tarefa dependente dela ter sido finalizada;</p>
**Ativação com passagem de informação**: Além da relação ser ativada, suas informações tem que ser passada para a próxima tarefa; </p>
**Escolha**: T1 [] T2 são tarefas e elas só podem ser ativadas quando a outra estiver desabilitada;</p>
**Tarefas concorrentes**: T1 ||| T2 são tarefas que podem ser realizadas em qualquer ordem ou tempo;</p>
**Tarefas concorrentes e comunicantes**: T1 |[]| T2 são tarefas concorrentes que podem trocar informações; </p>
**Tarefas independentes**: T1 |=| T2 são tarefas que podem ser feitas em qualquer ordem, mas quando uma delas são iniciadas, a outra não pode ser feita enquanto não for terminada;</p>
**Desativação**: T1[> T2 são tarefas onde T1 é interrompida por T2;</p>
**Suspenção/Retomada**: T1|>T2 especifica que T1 pode ser interrompida por T2 e é retomada do ponto em que parou assim que T2 Terminar.</p>

## Resultados
### Tarefa de consulta ao Dentran Veículos
<figure>
<img align=center width="700" src="../../../img/ctt.png">
<br>
<figcaption>Figura 1 - Diagrama CTT, feito no LucidChart por Deivid.</a></figcaption>
</figure>

## Referências Bibliográficas

[1] Livro: Barbosa, S.D.J.; Silva, B.S.; Silveira, M.S.; Gasparini, I.; Darin, T.; Barbosa, G.D.J.
(2021) Interação Humano-Computador e Experiência do Usuário.

## Versionamento
| Data |Versão|         Descrição          |       Autor      |
|:----:|:----:|:--------------------------:|:----------------:|
| 27/08/2021 |  2.0 | Criação da documento     | Deivid |