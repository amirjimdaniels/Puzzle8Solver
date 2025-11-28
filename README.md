# 8-Puzzle Solver (Java)

This is a simple **8-puzzle** solver written in Java that supports:

- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS, depth-limited)**
- **A\* Search (Manhattan distance heuristic)**

It runs in the console and prints out the sequence of moves from the start state to the goal state, along with some stats.

---

## Problem Description

The **8-puzzle** is a sliding tile puzzle on a 3×3 board:

- Tiles are numbered `1` to `8`
- `0` represents the blank space
- You can slide any tile adjacent to the blank into the blank space
- The goal is to transform a given **start state** into a **goal state** using valid moves

By default this app uses the classic goal:

```text
1 2 3
4 5 6
7 8 0

