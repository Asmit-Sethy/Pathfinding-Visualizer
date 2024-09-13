# Pathfinding Visualizer

## Introduction

Pathfinding algorithms are crucial in applications like network routing and mapping. This project visualizes pathfinding algorithms using React and CSS animations. It features various algorithms, including BFS, DFS, Dijkstra’s, and A*, displayed on a grid where the green box represents the start node and the red box represents the end node. The grid is designed with HTML tables, and node colors are managed with CSS.


## Algorithms Used

#### Breadth-first Search
- Guarantees the shortest path in an unweighted grid; a reliable algorithm for pathfinding.

#### Depth-first Search 
- A less effective algorithm for pathfinding; does not guarantee the shortest path but explores paths deeply before backtracking.

#### Dijkstra's Algorithm
- It can be used for unweighted graphs by treating all edge weights as equal. It finds the shortest path based on the number of edges, similar to Breadth-first Search (BFS).

#### A* Search
- A highly efficient algorithm that uses heuristics to find the shortest path much faster than Dijkstra's Algorithm.


## How to Use

1. **Start Node:** Click on the grid to set the starting node (green box).
2. **End Node:** Click on another cell to set the end node (red box).
3. **Select Algorithm:** Choose from the available algorithms to visualize the pathfinding process.
4. **Clear Grid:** Use the 'Clear Grid' button to reset the grid while keeping the start and end nodes intact.
5. **Clear Walls:** Use the 'Clear Walls' button to remove any walls or obstacles you have added to the grid.
