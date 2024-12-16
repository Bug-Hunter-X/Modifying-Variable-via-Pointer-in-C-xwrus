# Modifying Variable via Pointer in C
This repository demonstrates a common C programming error involving the modification of a variable's value through a pointer. The primary objective is to illustrate this subtle error and provide a clear solution.

## Understanding the Bug
The core issue lies in how pointers interact with variables in memory. The code within `bug.c` directly manipulates the variable `x` using a pointer. Although seemingly straightforward, this can lead to unexpected behavior if not handled carefully.

## Bug Solution
The `bugSolution.c` file offers a robust alternative. While the fundamental concept remains the same (modifying a variable through a pointer), the solution offers a structured approach, emphasizing clarity and error prevention.

## How to Run
1. Clone this repository.
2. Compile the `bug.c` and `bugSolution.c` files using a C compiler (like GCC):
   ```bash
   gcc bug.c -o bug
   gcc bugSolution.c -o bugSolution
   ```
3. Run the compiled executables to observe the output and compare the results.