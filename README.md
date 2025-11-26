# NFP106: Intelligence artificielle

Works realized in the context of the CNAM Paris [NFP106 class](https://formation.cnam.fr/rechercher-par-discipline/intelligence-artificielle-208617.kjsp) 'Intelligence artificielle'

---

## Table of Contents

- [NFP106: Intelligence artificielle](#nfp106-intelligence-artificielle)
  - [Table of Contents](#table-of-contents)
  - [1. Classical Search Problems](#1-classical-search-problems)
    - [1.1. Cannibals \& Missionaries Problem](#11-cannibals--missionaries-problem)
    - [1.2. Water Pouring Puzzle](#12-water-pouring-puzzle)
    - [1.3. Wolf, Goat, and Cabbage Problem](#13-wolf-goat-and-cabbage-problem)
  - [2. Informed Search \& Local Search](#2-informed-search--local-search)
    - [2.1. 8 Puzzle (Sliding Tile)](#21-8-puzzle-sliding-tile)
    - [2.2. Eight Queens Puzzle](#22-eight-queens-puzzle)

---

## 1. Classical Search Problems

These projects explore **Uninformed Search** algorithms, focusing on the fundamental principles of traversing a state space graph.

### 1.1. Cannibals & Missionaries Problem

- **Goal:** Three missionaries and three cannibals must cross a river using a boat that can carry at most two people. The cannibals must never outnumber the missionaries on either side of the river.  
- **Approach:** Solved using a **Breadth-First Search (BFS)** algorithm because of the limited size of the search graph.
- **Code:** [Cannibals missionaries problem](./cannibals_missionaries_problem/)
- **Wikipedia:** [Missionaries and cannibals problem](https://en.wikipedia.org/wiki/Missionaries_and_cannibals_problem)

### 1.2. Water Pouring Puzzle

- **Goal:** Given three jugs with capacities of 12L, 8L, and 3L, that we can empty and refill at anytime, determine the sequence of operations (fill, empty, pour) needed to fill a jug with exactly 1L.
- **Approach:** Solved using a **Breadth-First Search (BFS)** algorithm because of the limited size of the search graph.
- **Code:** [Water pouring puzzle](./water_pouring_puzzle/)
- **Wikipedia:** [Water pouring puzzle](https://en.wikipedia.org/wiki/Water_pouring_puzzle)

### 1.3. Wolf, Goat, and Cabbage Problem

- **Goal:** A farmer must transport a wolf, a goat, and a cabbage across a river. The boat can only carry the farmer and one item at a time. The wolf cannot be left alone with the goat, and the goat cannot be left alone with the cabbage.  
- **Approach:** Solved using a **Breadth-First Search (BFS)** algorithm because of the limited size of the search graph.
- **Code:** [Wolf, goat and cabbage problem](./wolf_goat_cabbage_problem/)
- **Wikipedia:** [Wolf, goat and cabbage problem](https://en.wikipedia.org/wiki/Wolf,_goat_and_cabbage_problem)

---

## 2. Informed Search & Local Search

These projects utilize both uninformed and informed, as well as local search methods to solve complex problems.

### 2.1. 8 Puzzle (Sliding Tile)

- **Problem:** The classical 3x3 sliding tile puzzle.
- Solved using a variety of search algorithms:
  - **Uninformed:** BFS, DFS, Depth Limited Search, Iterative Deepening Search, Bidirectional Breadth-First Search.
  - **Informed (Heuristic):** Greedy Search, A\*, Weighted A\*, Beam Search, and Bidirectional A\*.
- **Code:** [8 puzzle](./8_puzzle/8_puzzle.ipynb)
- **Wikipedia:** [15 puzzle](https://en.wikipedia.org/wiki/15_puzzle)

### 2.2. Eight Queens Puzzle

- **Problem:** Place eight chess queens on an 8×8 chessboard such that no two queens threaten each other (no two queens can share the same row, column, or diagonal).
- Solved using different local search algorithms:
  - Hill Climbing/Gradient Descent algorithms.
  - Simulated Annealing.
  - Local Beam Search.
- **Code:** [Eight queens puzzle](./8_queens_problem/8_queens.ipynb)
- **Wikipedia:** [Eight queens puzzle](https://en.wikipedia.org/wiki/Eight_queens_puzzle)
