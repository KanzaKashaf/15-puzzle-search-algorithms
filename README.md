
# 15 Puzzle Game Solver

An Artificial Intelligence-based solver for the classic 15 Puzzle Game, utilizing both **uninformed** and **informed search algorithms**. The goal of the game is to arrange tiles in ascending order with minimal moves by sliding them into an empty space.

---

## Project Overview

This project demonstrates the application of search strategies from AI to solve the 15 Puzzle Game. It was developed as a group assignment for the **Artificial Intelligence** course at **National Textile University, Faisalabad**.

---

## Group Members

- **Hassaan Raza**  
- **Kanza Kashaf**  
- **Subaina Norab**  

---

## Game Objective

Arrange the tiles in **ascending order** from 1 to 15 by sliding tiles into the empty space.

---

## Search Strategies Used

### Uninformed Search

These strategies explore the state space **without domain-specific knowledge**.

#### Breadth-First Search (BFS)
- Explores all nodes at the current depth before moving to the next level.
- Uses a **queue**.
- Guarantees optimal solution but may be slow for large depths.

#### Depth-First Search (DFS)
- Explores as far down a branch as possible before backtracking.
- Uses a **stack** (recursion or manually).
- May find a solution quickly but not guaranteed to be optimal.

### Informed Search

These use **heuristics** to guide the search toward the goal more efficiently.

#### A* Algorithm
- Combines actual cost (`g(n)`) and heuristic cost (`h(n)`) to compute `f(n) = g(n) + h(n)`.
- Uses a **priority queue** for node selection.

##### Heuristic 1: **Tiles Out of Place**
- Counts how many tiles are not in the correct position.
- Simple but less informative than Manhattan Distance.

##### Heuristic 2: **Manhattan Distance**
- Sum of horizontal and vertical distances of each tile from its goal position.
- More accurate and commonly used.

---

## Technologies

- Python 3
- Jupyter Notebook (`.ipynb`)
- Standard libraries: `queue`, `heapq`, `copy`

---

## How to Run

1. Open the Jupyter Notebook file:  
   `15_PUZZLE_GroupTask_final.ipynb`

2. Run each cell sequentially to:
   - Initialize puzzle state
   - Apply BFS/DFS/A* algorithm
   - View step-by-step solution and performance metrics

---

## Learning Outcomes

- Understanding and implementing classical search algorithms.
- Applying heuristic functions in problem-solving.
- Visualizing and analyzing performance differences between strategies.

---
