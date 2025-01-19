# Stack Overflow Bug in Hack

This repository demonstrates a common stack overflow error in a recursive factorial function written in Hack. The `foo` function calculates the factorial using recursion. However, it lacks proper handling for negative inputs, leading to infinite recursion and a stack overflow.

The `bug.hack` file contains the erroneous code. The `bugSolution.hack` file provides a corrected version with a base case that handles negative input correctly.

## How to Reproduce

1. Clone this repository.
2. Compile and run `bug.hack` with a large positive integer. You'll observe a stack overflow error.
3. Compile and run `bugSolution.hack` with the same input; it will correctly handle both positive and negative inputs.