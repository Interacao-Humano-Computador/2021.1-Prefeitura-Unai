![UnB](../../img/unb.jpg)

# Keystroke-Level Method (GOMS-KLM)

## Definição
<p align = "justify">O KLM (Keystroke Level Model) é a técnica mais simples de GOMS, limitada a um conjunto predefinido de operadores primitivos e serve para modelar interações ao nível físico do dispositivo.
Esse modelo consegue prever o desempenho dos usuários na execução das suas tarefas e aplica-se poucos comandos.(BARBOSA e SILVA, 2010) 
</p>

<p align = "justify">Os operadores primitivos do KLM são:</p>

| Operador |  Descrição |                    
|:----------:|:--------:|
|K |Pressionar uma tecla|
|B |Pressionar botão mouse|
|P |Apontar, mover mouse|
|H |Localizar mouse/teclado|
|M |Preparação mental para uma ação|
|R |Resposta do sistema|

## Motivo da escolha

<p align = "justify">Foi decidido a utilização do KLM, pois ele é uma técnica mais simples e pode ser usado para prever a performance da tarefa e tambémm para substituir testes de usuário empíricos necessários para chegar a um design que é tanto funcional quando utilizável. Dessa forma análise é executável, qualquer exigência da tarefa pode ser simulada seguindo caminhos diferentes, dependendo de cada tarefa (Barbosa e Silva, 2010).</p>

## Resultados

Tarefa IPTU – por contribuinte.
<b> Método: Clicar em Iptu </b>

| Preparação | Operador |  Tempo(s) |                    
|:----------:|:--------:|:---------:|
| Preparação |    M     |   1,20    |  
| Levar a mão do teclado ao mouse | H |  0,4  |
| levar o curso até o botão IPTU |  P  |  1,10   |
| Soltar botão do mouse            | B   | 0,1    |
| Esperar página carregar            |  R  |  1,20   |  
| Tempo        | | 4,15s   |     

<b> Método: Acessar o botão “emitir guia online”.</b>

| Preparação | Operador |  Tempo(s) |                    
|:----------:|:--------:|:---------:|
| Preparação| M |1,20|  
| Levar a mão do teclado ao mouse | H |  0,4  |
| levar o curso até o botão emitir guia online |  P  |  1,10   |
| Pressionar o botão do mouse | B   | 0,15   |
| Soltar botão do mouse            | B   | 0,1    |
| Esperar página carregar            |  R  |  1,20   |  
| Tempo       | | 7,95s   |   


<b> Método: Preencher os dados do usuário .</b>

| Preparação | Operador |  Tempo(s) |                    
|:----------:|:--------:|:---------:|
|PREPARAÇÃO |M | 5,00|
|levar  cursor até o tipo de pessoa|  P| 1,10|
|Pressionar o botão do mouse|  B | 0,15|
|Soltar botão do mouse | B | 0,1|
|levar a mão do mouse da teclado|  H|  0,4|
|Digitação do CPF| T(11)|  4,00 |
|Levar a mão do teclado ao mouse |  H |  0,4|
|Levar cursor até a opção IPTU | P | 1,10|
|Pressionar o botão do mouse|  B | 0,15|
|Soltar botão do mouse| B |0,1|
|Levar cursor até o recaptcha “Não sou um Robô”|  P|  1,10|
|Pressionar o botão do mouse|  B | 0,15|
|Soltar botão do mouse|  B  |0,1|
|Esperar validação do recaptcha “Não sou um Robô|  P|  1,10|
|Pressionar o botão do mouse|  B  |0,15|
|Soltar botão do mouse|  B |  0,1|
|Esperar página carregar|  R  |9,00|
| Tempo      | | 24,2s   | 

Tempo total:  36,3s   

## Referências Bibliográficas
Livro: Barbosa, S.D.J.; Silva, B.S.; Silveira, M.S.; Gasparini, I.; Darin, T.; Barbosa, G.D.J.
(2021) Interação Humano-Computador e Experiência do Usuário.

## Versionamento

| Data |Versão|         Descrição          |       Autor      |
|:----:|:----:|:--------------------------:|:----------------:|
| 26/08/2021 |  1.0 | Criação da página     | Victor, Paulo Vitor |
