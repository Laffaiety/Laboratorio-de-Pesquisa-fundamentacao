# Laboratorio de Pesquisa fundamentacao
T1 - primeiro ciclo iterativo
Neste presente documento será apresentado o relatório do primeiro ciclo iterativo do desenvolvimento ágil de um software de jogo educacional.
onde nele terá:
# Planejamento.

A ideia inicial para esse trabalho é criar um jogo que tem como objetivo além de ensinar o alfabeto no estágio de português e a calcular no estágio de matemática, 
motivar o estímulo cognitivo dos jogadores. 
Em português esse estímulo é feito através da formação de palavras, onde em algumas fases o jogador terá que montar o alfabeto e escrever o nome da figura que ele estará vendo.
Em matemática na resolução de cálculos de soma e subtração.
O jogo será feito na plataforma da Unreal Engine 4.

## Objetivo:

O objetivo do jogo é abrir as portas que bloqueiam a passagem do personagem principal para a próxima fase. Cada estágio terá 5 fases, para cada fase concluída o jogador é recompensado com moedas.
As moedas vão variar a quantidade de acordo com o tempo gasto para completar cada fase. 
As moedas podem ser gastas para liberar novos personagens.

## Desafios:

Os estágios foram divididos em duas matérias português e matemática;
## 1 - Português:
Em português o jogador deve acertar as ordens das letras do alfabeto ou escrever o nome do desenho que será mostrado em um painel no jogo para liberar a passagem para a próxima fase. 
As variações desse estagio foram divididos em 5 fases.
**Fase 1:** O jogador tem que acertar quais são as 13 primeiras letras do alfabeto
**Fase 2:** O jogador tem que escrever o nome do desenho que aparecerá na parede.
**Fase 3:** O jogador deverá acertar as posições corretas de cada letra do alfabeto. Dividida em quatro paredes as variantes do desafio.
**Fase 4:** O jogador tem que acertar quais são as 13 últimas letras do alfabeto.
**Fase 5:** O jogador deverá montar todo o alfabeto, escrever o nome de 2 desenhos e colocar as letras que estão faltando no alfabeto.

## 2 - Matemática
Em matemática o jogador deverá realizar cálculos de soma e subtração para avançar nas fases:
**Fase 1:** O jogador deverá montar a tabuada de soma dos números de 1 a 5
**Fase 2:** O jogador deverá montar a tabuada de subtração dos números de 1 a 5
**Fase 3:** O jogador deverá montar a tabuada de soma dos números de 6 a 10
**Fase 4:** O jogador deverá montar a tabuada de subtração dos números de 6 a 10
**Fase 5:** O jogador deverá realizar somas e subtrações que aparecerão aleatoriamente nos painéis.
## O que já foi implementado?

Foi implementado a criação do personagem principal, com logica de movimentação e salto.
Foi implementado alguns blocos para teste de física.
Foi implementado o menu inicial do game
Foi implementado uma porta para teste
Foi implementado um Golem que será um enfeite no mapa

# Projeto ("Designing")
## Tela do menu principal
![Tela de menu](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao/blob/main/menu.png)
## Tela da opção (sobre) do jogo, onde nela contém algumas informações sobre o jogo.
![Tela Sobre](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao/blob/main/sobre.png)
## Fase principal de testes, com o personagem principal um Golem e uma porta para teste.
![Fase principal](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao/blob/main/mapa.png)
## Codificação.
A codificação do game é feita por blocos de programação
## No menu foi aplicada a seguinte logica:
![Logica Menu](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao/blob/main/logica_Menu.png)
## Na porta foi aplicado a seguinte logica:
![Logica porta](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao/blob/main/logica_Door.png)
Como a lógica para abrir a porta será feita através de puzzles, ela ainda não está funcionando.
## Testes. 
O vídeo a seguir mostra o teste do jogo no seu estado atual:
