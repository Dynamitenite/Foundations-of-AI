# Breadth-First Search (BFS)

## Objective
Implement the Breadth-First Search (BFS) algorithm to find a path between two nodes in a graph.

## Problem Statement
Given the following tree:

```text
        A
      /   \
     B     C
    / \   / \
   D   E F   G
       |
       H
```

Find the path from **A** to **H**.

## Algorithm
1. Represent the graph using a dictionary.
2. Store complete paths in a queue.
3. Remove the first path from the queue (FIFO).
4. Check whether the goal node is reached.
5. Mark nodes as visited.
6. Add child nodes to the queue.
7. Repeat until the goal is found.

## Files
- `bfs.py` - Python implementation
- `Lab2A.pdf` - Handwritten explanation

## Output
- Path from A to H
- Order of visited nodes

## Concepts Used
- Graph Representation
- Breadth-First Search
- Queue (FIFO)
- Lists
- Dictionaries

