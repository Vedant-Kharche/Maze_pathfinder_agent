# Maze Solver using BFS and DFS 🧭

This Python project demonstrates **Breadth-First Search (BFS)** and **Depth-First Search (DFS)** algorithms to navigate through a maze. The maze is represented as a 2D grid where the goal is to find a path from a starting point (S) to an endpoint (E), avoiding walls and dead ends. The solver visually displays each step and marks the final path once found.

## 🚀 Features

- Maze traversal using:
  - **Breadth-First Search (BFS)** – for shortest path
  - **Depth-First Search (DFS)** – for deeper, more exploratory path
- Visualization of each algorithm’s progress through the maze
- Highlights the final path with markers (`P`) on the maze
- Simple CLI interface for choosing BFS or DFS

## 🧩 Maze Representation

- `1` – Wall
- `0` – Open path
- `2` – Start (`S`)
- `3` – End (`E`)
- `C` – Current position during search
- `P` – Path taken to reach the end (marked after completion)

