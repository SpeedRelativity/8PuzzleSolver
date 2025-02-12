# 8-Puzzle Solver Using BFS & IDDFS

This project implements an **8-Puzzle Solver** using **Breadth-First Search (BFS)** and **Iterative Deepening Depth-First Search (IDDFS)**. It efficiently finds the shortest path to solve the puzzle while showcasing fundamental search algorithms in artificial intelligence.

## 📜 Overview

- **Algorithms Used:** BFS (Shortest Path), IDDFS (Iterative Deepening)
- **Data Structures:** Queue (Frontier for BFS), Recursion with Depth Limit for IDDFS
- **Performance Optimization:** Visited state tracking using sets
- **Goal:** Transform a given **3×3 sliding puzzle** into the solved state:

Solution of the first Scenario using BFS:
XXX
XXX
XXX

to
XXX
XXX
XXX

to
123
456
780

Solution of the first Scenario using IDS:
Searching at depth: X
Searching at depth: XX
...
Solution found!
XXX
XXX
XXX

to
XXX
XXX
XXX

to
123
456
780
