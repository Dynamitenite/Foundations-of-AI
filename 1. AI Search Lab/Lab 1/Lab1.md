# Water Jug Problem - State Space Search

## Objective
Implement a state space search for the Water Jug Problem using two jugs of capacities 4 litres and 3 litres. The objective is to obtain exactly **2 litres** in the 4-litre jug.

## Problem Statement
Two jugs are available:
- Jug X: 4 litres
- Jug Y: 3 litres

Allowed operations:
- Fill a jug
- Empty a jug
- Pour water from one jug to the other

The program explores the state space and identifies the state where the 4-litre jug contains exactly 2 litres.

## Algorithm
1. Represent each state as `(x, y)`, where:
   - `x` = water in the 4L jug
   - `y` = water in the 3L jug
2. Generate all possible successor states.
3. Start from the initial state `(0,0)`.
4. Explore the state space using Breadth-First Search (BFS).
5. Keep track of visited states to avoid repetition.
6. Stop when the goal state is reached.

## Files
- `water_jug.py` - Python implementation
- `Lab1.pdf` - Handwritten explanation

## Output
- States generated at each level
- Goal state when 2 litres is obtained
- Total number of unique states explored

## Concepts Used
- State Space Representation
- Breadth-First Search (BFS)
- Sets
- Lists
- Successor Function

## Author
Aakaash Anoop
