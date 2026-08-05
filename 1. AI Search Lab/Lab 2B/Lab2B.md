# Depth-First Search (DFS)

## Objective
Implement the Depth-First Search (DFS) algorithm to find a path between two nodes in a graph.

## Problem Statement
Given the following tree:

```text
        A
       / \
      B   C
     / \ / \
    D  E F  G
       |
       H
```

Find the path from **A** to **H** using Depth-First Search.

## Algorithm
1. Represent the graph using a dictionary.
2. Store complete paths in a stack.
3. Remove the last path from the stack (LIFO).
4. Check whether the goal node is reached.
5. Mark nodes as visited.
6. Push child nodes onto the stack.
7. Continue until the goal is found.

## Files
- `dfs.py` - Python implementation
- `Lab2B.pdf` - Handwritten explanation

## Output
- Path from A to H
- Order of visited nodes

## Concepts Used
- Graph Representation
- Depth-First Search
- Stack (LIFO)
- Lists
- Dictionaries
