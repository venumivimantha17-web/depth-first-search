# Depth-First Search Algorithm

This project implements the Depth-First Search (DFS) algorithm in Python using an undirected adjacency matrix.

DFS explores a graph by following a path as deeply as possible before backtracking to explore other unvisited paths. The implementation uses a stack following the Last-In-First-Out (LIFO) principle.

## Features

- Implements the Depth-First Search algorithm
- Uses a stack for graph traversal
- Works with an undirected adjacency matrix
- Tracks visited nodes to avoid duplicate visits
- Returns all nodes reachable from the starting node

## Implementation

The `dfs()` function takes two arguments:

- `graph` - An undirected adjacency matrix
- `start` - The starting node label

### Example

```python
graph = [
    [0, 1, 0, 0],
    [1, 0, 1, 0],
    [0, 1, 0, 1],
    [0, 0, 1, 0]
]

print(dfs(graph, 1))
