ChainReactionAutomata

Developed by NIT Surathkal

A multiplayer chain reaction game developed using HTML, CSS, JS Framework. Additionally a Non Deterministic Finite Automata has been developed to facilitate future development of a heuristic. 

Chain reaction is a simple strategic board game for two or more players. The game has primarily 2
components: an m x n grid of cells and a set of balls to be placed into them. All cells are initially
empty. The players take turns to place balls of their corresponding colors into the cells. The player
can either place his ball in an empty cell or in one containing balls of the same colour as the
player's. When two or more balls of same color are placed in the same cell, they cohere together.
For each cell in the board, we define a critical mass. The critical mass is equal to the number of
orthogonally adjacent cells. That would be 4 for usual cells, 3 for cells at the edge and 2 for cells in
the corner. When a cell is loaded with a number of balls equal to its critical mass, the group of balls
immediately explodes. As a result of the explosion, to each of the orthogonally adjacent cells, an
ball is added and the initial cell loses as many balls as it's critical mass. The explosions might result
in overloading of an adjacent cell and the chain reaction of explosions continues until every cell is
stable. When a group of balls explode and move into the adjacent cells, they convert all the balls in
the adjacent cells to their colour.
The objective of the game is to remove all of the opponent's pieces from the board by causing a
chain reaction of explosions.
The project aims at developing a heuristic for the game progress by modelling the game as a finite
state automata for a 2 player system.
