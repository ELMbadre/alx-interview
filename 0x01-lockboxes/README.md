# 0x01. Lockboxes

## Algorithm | Python

**Weight:** 1

Project timeline:
- **Start:** October 7, 2024, 4:00 AM
- **End:** October 11, 2024, 4:00 AM
- **Checker Release:** October 8, 2024, 4:00 AM
- **Auto Review Launch:** At the project deadline

## Must-Know Concepts

For this project, you will need a solid understanding of several key concepts to efficiently determine if all boxes can be opened. Here are the essential topics:

### Lists and List Manipulation
- Working with lists, including accessing elements, iterating, and modifying lists dynamically.
- [Python Lists (Python Official Documentation)](https://docs.python.org/3/tutorial/datastructures.html)

### Graph Theory Basics
- Knowledge of traversal algorithms like Depth-First Search (DFS) or Breadth-First Search (BFS), viewing boxes and keys as nodes and edges in a graph.
- [Graph Theory (Khan Academy)](https://www.khanacademy.org/computing/computer-science/algorithms)

### Algorithmic Complexity
- Understanding time and space complexity for writing efficient algorithms.
- [Big O Notation (GeeksforGeeks)](https://www.geeksforgeeks.org/analysis-of-algorithms-set-1-asymptotic-analysis/)

### Recursion
- Applying recursive methods to traverse through boxes and keys.
- [Recursion in Python (Real Python)](https://realpython.com/python-recursion/)

### Queue and Stack
- Utilizing queues and stacks for BFS or DFS algorithm implementation.
- [Python Queue and Stack (GeeksforGeeks)](https://www.geeksforgeeks.org/stack-in-python/)

### Set Operations
- Using sets to keep track of visited boxes and available keys to optimize the search process.
- [Python Sets (Python Official Documentation)](https://docs.python.org/3/tutorial/datastructures.html#sets)

By reviewing these concepts and using these resources, you will be well-equipped to develop an efficient solution for this project, applying both your algorithmic thinking and Python programming skills.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- Files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the project folder, is mandatory
- Code should be documented
- Code should follow the PEP 8 style (version 1.7.x)
- All files must be executable

## Tasks

### 0. Lockboxes
**Mandatory**

You have `n` number of locked boxes in front of you. Each box is numbered sequentially from `0` to `n - 1` and each box may contain keys to other boxes.

Write a method that determines if all the boxes can be opened.

#### Prototype:
```python
def canUnlockAll(boxes):

