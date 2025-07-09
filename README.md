# 15 Puzzle Solver

An AI-based solver for the classic **15-Puzzle Game** using both **uninformed** (BFS, DFS) and **informed** (A* with Manhattan Distance & Misplaced Tiles heuristic) search algorithms. Implemented in Python with object-oriented design and clear modular structure.

---

## Project Overview

This project is a part of the *Artificial Intelligence* course at **National Textile University, Faisalabad**, demonstrating various search techniques applied to a classic combinatorial problem: the 15-puzzle.

The puzzle consists of a 4x4 grid of numbered tiles (1–15) and one empty space. The objective is to slide the tiles into the correct order using valid moves.

---

## Group Members

- *Muhammad Hassaan Raza*  
- *Kanza Kashaf*

---

## Algorithms Implemented

### Uninformed Search

- **Breadth-First Search (BFS)**  
  Explores all nodes at the current depth before moving deeper. Ensures the shortest solution path. Uses a FIFO Queue.

- **Depth-First Search (DFS)**  
  Explores as deep as possible down one path before backtracking. May not find optimal solutions. Uses a LIFO Stack.

### Informed Search

- **A\* Search Algorithm**  
  Combines path cost and heuristic estimation to find optimal paths.

  #### Heuristics Used:
  - *Manhattan Distance*: Sum of tile distances from their goal positions.
  - *Misplaced Tiles*: Counts tiles not in their correct position.

---

## Features

- Object-Oriented `Puzzle` class
- Random solvable puzzle generator
- Multiple search strategies with tracking
- Optimal path finding and backtracking
- Heuristic-based informed search

---

## Technologies Used

- Python 3
- Standard Libraries:
  - `queue`
  - `random`
  - `PriorityQueue`
- Jupyter Notebook

---

## Sample Output

```
Initial State:
[5, 1, 2, 3]
[6, 0, 7, 4]
[9, 10, 11, 8]
[13, 14, 15, 12]

Solution using A* (Manhattan Distance):
→ D → R → U → ...

Total steps: 36
Time taken: 0.15s
```

---

## 📂Project Structure

```
15_Puzzle_Solver/
├── 15_PUZZLE_GroupTask_final.ipynb       # Main Notebook
├── README.md                             # Project Documentation
```

---

## How to Run

1. Open `15_PUZZLE_GroupTask_final.ipynb` in Jupyter Notebook.
2. Run each section to test BFS, DFS, or A* with heuristics.
3. Modify the initial state if desired.

---

## Acknowledgments

- AI Coursework – NTU Faisalabad  
- AIMA textbook for heuristic inspiration  
- Python Docs and StackOverflow for optimization ideas

---

## Contact

- **Muhammad Hassaan Raza**  
  hassaanxhk11@gmail.com | +92 320 0096255 | [GitHub](https://github.com/HassaanRazaX)

- **Kanza Kashaf**  
  kanzakashaf56@gmail.com | +92 324 0497445 | [GitHub](https://github.com/KanzaKashaf)

---
