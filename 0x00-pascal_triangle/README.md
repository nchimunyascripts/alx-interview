# Pascal's Triangle Project

## Overview

This project involves creating a function to generate Pascal's Triangle, a classic algorithmic problem, using Python. The function `pascal_triangle(n)` will return a list of lists of integers representing Pascal's Triangle of size `n`. This project aims to reinforce understanding and application of several key Python programming concepts.

## Resources

- [What is Pascal’s Triangle](https://www.cuemath.com/algebra/pascals-triangle/)
- [Pascal’s Triangle - Numberphile](https://www.youtube.com/watch?v=0iMtlus-afo)
- [What are Python Algorithms](https://builtin.com/data-science/python-algorithms)

### Additional Resources

- [Mock Technical Interview](https://www.youtube.com/watch?v=1qw5ITr3k9E)

## Must Know Concepts

To successfully complete this project, you should revise the following Python concepts:

### Lists and List Comprehensions

- **Creation, Access, Modification, and Iteration:** Understand how to create, access, modify, and iterate over lists.
- **List Comprehensions:** Utilize list comprehensions for more concise and readable code, especially for generating rows of Pascal’s Triangle.

### Functions

- **Defining and Calling Functions:** Know how to define and call functions.
- **Parameters and Return Values:** Pass parameters and return values, particularly how to return a list of lists representing Pascal’s Triangle.

### Loops

- **For and While Loops:** Use for and while loops to iterate through sequences.
- **Nested Loops:** May be necessary for generating each row and calculating the values of Pascal’s Triangle.

### Conditional Statements

- **If, Elif, and Else Conditions:** Apply conditional statements to implement logic based on the position within Pascal’s Triangle (e.g., the edges of the triangle always being 1).

### Recursion (Optional)

- **Base and Recursive Cases:** Recognize base cases and recursive cases for a function that generates the triangle’s rows.

### Arithmetic Operations

- **Addition:** Perform addition, a fundamental operation for calculating each element of Pascal’s Triangle as the sum of the two elements directly above it.

### Indexing and Slicing

- **Access Elements and Slices:** Crucial for identifying and summing the correct elements when constructing each row of the triangle.

### Memory Management

- **Storage and Copying:** Be mindful of how lists are stored and copied, especially when creating new rows based on the values of the previous row.

### Error and Exception Handling (Optional)

- **Try-Except Blocks:** Use as needed to handle potential errors, such as invalid input types or values.

### Efficiency and Optimization

- **Time and Space Complexity:** Consider the time and space complexity of different approaches to generating Pascal’s Triangle.
- **Optimizations:** Evaluate and apply optimizations to improve the performance of the solution.

By revisiting these concepts, you will be well-prepared to tackle the challenges of implementing Pascal’s Triangle in Python, applying both your mathematical understanding and programming skills to develop an efficient and effective solution.

## Tasks

### Task 0: Pascal's Triangle (Mandatory)

Create a function `def pascal_triangle(n):` that returns a list of lists of integers representing the Pascal’s triangle of `n`:

- Returns an empty list if `n <= 0`
- Assume `n` will always be an integer

#### Example

```python
guillaume@ubuntu:~/0x00$ cat 0-main.py
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

guillaume@ubuntu:~/0x00$
guillaume@ubuntu:~/0x00$ ./0-main.py
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
guillaume@ubuntu:~/0x00$
```

## Repository

- **GitHub Repository:** alx-interview
- **Directory:** `0x00-pascal_triangle`
- **File:** `0-pascal_triangle.py`

## Conclusion

This README provides an overview of the Pascal's Triangle project, including project details, essential resources, key Python concepts to revise, and specific tasks to accomplish. By following this guide and revisiting the necessary concepts, you will be equipped to implement an efficient solution to generate Pascal’s Triangle in Python.
