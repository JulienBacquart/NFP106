# NFP106: Intelligence artificielle

Works realized in the context of the CNAM Paris [NFP106 class](https://formation.cnam.fr/rechercher-par-discipline/intelligence-artificielle-208617.kjsp) 'Intelligence artificielle'

- [Cannibals missionaries problem](./cannibals_missionaries_problem/): Three missionaries and three cannibals must cross a river using a boat that can carry at most two people. The cannibals must never outnumber the missionaries on either side of the river.  
For more details see the [Missionaries and cannibals problem](https://en.wikipedia.org/wiki/Missionaries_and_cannibals_problem) wikipedia page.  
Implemented using a Breadth-first search algorithm, because of the limited size of the search graph.

- [Water pouring puzzle](./water_pouring_puzzle/) : Given three jugs with capacities of 12L, 8L, and 3L, determine the sequence of operations (fill, empty, pour) needed to fill a jug with exactly 1L.  
  See the [Water pouring puzzle](https://en.wikipedia.org/wiki/Water_pouring_puzzle) wikipedia page for more details, but in this instance we use three jugs filled with a capacity of respectively 12L, 8L and 3L, that we can empty and refill at anytime.  
  Implemented using a Breadth-first search algorithm, because of the limited size of the search graph.

- [Wolf, goat and cabbage problem](./wolf_goat_cabbage_problem/) : A farmer must transport a wolf, a goat, and a cabbage across a river. The boat can only carry the farmer and one item at a time. The wolf cannot be left alone with the goat, and the goat cannot be left alone with the cabbage.  
See the [Wolf, goat and cabbage problem](https://en.wikipedia.org/wiki/Wolf,_goat_and_cabbage_problem) wikipedia page for more details.  
Implemented using a Breadth-first search algorithm, because of the limited size of the search graph.

- [Eight queens puzzle](./8_queens_problem/) : Place eight chess queens on an 8×8 chessboard such that no two queens threaten each other (no two queens share the same row, column, or diagonal).  
See the [Eight queens puzzle](https://en.wikipedia.org/wiki/Eight_queens_puzzle) wikipedia page for more details.  
Solved using different Hill Climbing/Gradient Descent algorithms and Simulated Annealing.
