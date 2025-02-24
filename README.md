# Python Average Calculator with ZeroDivisionError Handling

This repository demonstrates a common error in Python: the `ZeroDivisionError`. The `calculate_average` function calculates the average of a list of numbers.  It includes robust handling for the case where an empty list is provided as input, preventing the program from crashing.  This showcases best practices for error handling in Python.

## The Bug

The original `calculate_average` function would throw a `ZeroDivisionError` if an empty list was passed as input because it tried to divide by zero (`len(numbers)` would be 0). 

## The Solution

The improved `calculate_average` function now includes an `if not numbers:` check. If the list is empty, it returns 0, preventing the error.

## How to Run

1. Clone this repository.
2. Run `bug.py` to see the `ZeroDivisionError`. 
3. Run `bugSolution.py` to see the improved, error-free version.