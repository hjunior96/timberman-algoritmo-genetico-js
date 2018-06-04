# timberman-algoritmo-genetico-js
## O que é?
Esse projeto faz parte de uma tese de TCC do curso de ciência da computação na Universidade Presbiteriana Mackenzie. Consiste em um algoritmo em JavaScript que aprende sozinho a jogar o jogo mobile Timberman utilizando algoritmos genéticos.

## Como funciona? 
O algoritmo toma como base as distâncias que o lenhador está de um tronco pela direita e pela esquerda. Inicialmente são gerados 5 cromossomos com valores aleatórios para a direita e a esquerda. Após gerar os 5 cromossomos iniciais, são gerados 4 cromossomos usando os como base valores de dois cromossomos iniciais. O décimo e último cromossomo é gerado usando o valor de um cromossomo escolhido aleatoriamente e um valor entre 1 e 5. O programa então entra em loop e começa a testar o comportamento de cada cromossomo, guardando a pontuação máxima que cada um chegou. Após isso, o vetor que guardava os cromossomos é ordenado de maneira decrescente e o ciclo reinicia a partir do Crossover com os novos cromossomos.
O processo é executado infinitamente até que o algoritmo encontre a solução para não falhar no jogo.

## O que é necessário para executar o algoritmo?
Para poder testar e ver o algorimo, é necessário apenas o navegador Google Chrome.

## Como executar?
Para executar, basta entrar nas ferramentas de desenvolvedor do Chrome(F12), abrir o console e digitar "iniciar()" e o algorimo irá começar a rodar. 

### Algoritmo do jogo encontrado em: https://github.com/falsam/Timberman-JS
