Compartilho com vocês um projeto que desenvolvi para aprofundar meus estudos em inteligência artificial. Desenvolvi uma rede neural capaz de jogar o famoso jogo do Flappy Bird. Para isso, criei uma cópia do jogo do zero usando a biblioteca P5js do JavaScript e implementei o algoritmo genético para treinar a rede neural.

A ideia era fazer com que o pássaro do jogo aprendesse a passar pelos obstáculos e chegasse o mais longe possível. Para isso, utilizei quatro parâmetros de entrada: distância do teto, distância do chão e as distâncias euclidianas dos canos superior e inferior. A rede neural é composta por três camadas, sendo a primeira com as quatro entradas, a segunda com cinco neurônios na camada oculta e a terceira com um neurônio de saída, que é responsável por decidir se o pássaro deve pular ou não.

Na primeira geração de pássaros, utilizei 31 parâmetros aleatórios com valores entre -1 e 1. Para as gerações seguintes, utilizei uma seleção artificial dos dois melhores pássaros de cada geração e fiz um crossover para cruzar os parâmetros e criar a próxima geração. A função de ativação RELU foi utilizada na rede e na decisão de pular.

O objetivo desse projeto foi fixar os conhecimentos adquiridos na pós-graduação em inteligência artificial e machine learning, além de aprofundar meus conhecimentos em JavaScript. Foi uma experiência muito enriquecedora e desafiadora, que me permitiu aplicar na prática conceitos teóricos da área.