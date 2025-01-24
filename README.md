# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The error occurs because the loop condition `i <= vec.size()` attempts to access the element at index `vec.size()`, which is one position beyond the last valid element. 

The `bug.cpp` file shows the erroneous code, while `bugSolution.cpp` presents the corrected version.