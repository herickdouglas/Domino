# Domino

Classe Peca

A classe Peca, contém os 2 números da peça de dominó, no programa, irão existir
28 peças. A classe tem 2 atributos do tipo inteiro, o n1 e o n2.

Classe Node

A classe Node é o nó da lista, por ser uma lista duplamente encadeada, possui 3
atributos: a informação do nó (Peca peca, a peça atribuída ao nó), dois atributos do
tipo Node, que contém o próximo nó, e outro que contém o nó anterior.

Classe List

A classe List é a classe que comporta a lista.
Possui 5 atributos, 2 deles serão utilizados somente na lista das peças jogadas.

Classe Main

O programa começa com as 28 peças sendo criadas e armazenadas em uma
ArrayList com o nome lista. Depois as peças são distribuídas aleatoriamente
entre as 2 listas duplamente encadeadas, a lista de peças do Player e a lista de
peças do Bot.
