# Pascal's Triangle

## Description

This project implements Pascal's Triangle using Python. Pascal's Triangle is a triangular array of the binomial coefficients. The rows of Pascal's Triangle represent the coefficients of the binomial expansion in increasing powers. Each element in a row is the sum of the two elements directly above it from the previous row.

The goal is to implement a function `pascal_triangle(n)` that returns a list of lists representing the first `n` rows of Pascal's Triangle.

## Requirements

- You must create a function `def pascal_triangle(n):` that returns a list of lists of integers representing the Pascal's triangle of `n`.
- If `n` is less than or equal to 0, the function should return an empty list.
- You can assume that `n` will always be an integer.
  
## Example

Here's an example using the function:

```python
#!/usr/bin/python3
"""
0-main
"""
pascal_triangle = __import__('0-pascal_triangle').pascal_triangle

def print_triangle(triangle):
    """
    Print the triangle
    """
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))

