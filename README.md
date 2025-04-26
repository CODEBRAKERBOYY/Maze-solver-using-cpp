# MazeSolver

MazeSolver is a C++ project for solving mazes using popular pathfinding algorithms such as:

- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Dijkstra's Algorithm
- A* (A-Star) Algorithm

This repository demonstrates the implementation and visualization of these algorithms on text-based maze inputs.

---

## 📁 Project Structure

```
MazeSolver/
├── example/                      # Example drivers and test cases
│   ├── driver.cpp                # Main example to run maze solver
│   ├── animate.cpp              # Optional animation logic
│   ├── MazePrint.h
│   ├── MazeStringReader.h
│   ├── test cases/              # Input maze files
│   └── Modified Path/           # Alternate algorithm implementations
│       ├── BreadthFirstSearch.h
│       ├── DepthFirstSearch.h
│       ├── Dijkstra.h
│       ├── AStar.h
│       ├── Path.h
│       └── Modified_Path.h
├── src/                         # Core source code
│   ├── Maze.h
│   ├── MazeSolver.h
│   ├── IMazeReader.h
│   ├── Vertex.h
│   └── Path/
│       ├── BreadthFirstSearch.h
│       ├── DepthFirstSearch.h
│       ├── Dijkstra.h
│       ├── AStar.h
│       └── Path.h
├── LICENSE

             # Sample image (not required to run)
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

- C++11 or later
- A C++ compiler like `g++`
- Basic knowledge of C++ and graph traversal

### 🧪 Compiling Example

```bash
cd MazeSolver/example
g++ driver.cpp -o maze_solver
./maze_solver
```

> Make sure the test input files (e.g., `one.in`, `two.in`) are in the same folder or path as required.

---

## 🧠 Algorithms Implemented

- **BFS**: Explores all neighbors at the present depth before moving deeper.
- **DFS**: Explores as far as possible along one branch before backtracking.
- **Dijkstra**: Finds the shortest path by accumulating path weights.
- **A\***: Uses heuristics to find the shortest path more efficiently.

---

## 🧾 License

This project is licensed under the terms of the LICENSE file provided.

---

## ✍️ Author

Developed by **codebrakerboy**.# Maze-solver-using-cpp
