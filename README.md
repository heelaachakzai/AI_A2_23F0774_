# Dynamic Pathfinding Agent 



A **Tkinter GUI based dynamic pathfinding agent** in Python.  
The agent demonstrates **A\*** and **Greedy Best-First Search (GBFS)** algorithms with **Manhattan and Euclidean heuristics**, capable of navigating through **static and dynamic obstacles** in real-time.  

This project is ideal for learning **AI search strategies, heuristics, and adaptive pathfinding visualization**.

---

##  Features

- Interactive grid with **start and goal points**  
- Manual wall placement or **random maze generation**  
- **Dynamic obstacles** during path execution  
- Real time **path animation**  
- Metrics: **Nodes Visited**, **Path Cost**, **Execution Time**  
- Choice of **Algorithm**: A* or GBFS  
- Choice of **Heuristic**: Manhattan or Euclidean  

# Algorithms Implemented
## A* Search

- Uses f = g + h (path cost + heuristic)

- Guarantees optimal path with admissible heuristics

- Works best with Manhattan in 4-directional grids

- Slight differences appear with Euclidean heuristic due to diagonal distance calculations

## Greedy Best-First Search (GBFS)

- Uses only heuristic (h) to guide search

- Faster in simple grids but may not guarantee optimal paths in complex mazes
  
- Dynamic obstacles may force recalculations and suboptimal paths
