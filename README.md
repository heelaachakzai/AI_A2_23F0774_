# Dynamic Pathfinding Agent

A **Tkinter GUI-based dynamic pathfinding agent** implemented in Python.  
The agent uses **A\*** and **Greedy Best-First Search (GBFS)** with **Manhattan and Euclidean heuristics** to find paths in a 2D grid environment. Dynamic obstacles can appear in real-time, allowing the agent to recalculate paths adaptively.

---

## Features

- Interactive 20×20 (default) grid with start & goal points
- Place walls manually or generate random mazes
- Choose between **A*** or **GBFS** algorithms
- Choose heuristic: **Manhattan** or **Euclidean**
- **Dynamic Mode**: Obstacles appear during path execution
- Real-time path animation
- Metrics displayed: Nodes Visited, Path Cost, Execution Time
- Final path highlighted in green

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/Dynamic-Pathfinding-Agent.git
cd Dynamic-Pathfinding-Agent
