# Matrix Operations in C

Console program for matrix addition, multiplication, and transpose.

## Requirements
- GCC or another C compiler

## Compile and run
```bash
gcc -Wall -Wextra -Wpedantic matrix_operations.c -o matrix_operations
# Windows: .\matrix_operations.exe
# macOS/Linux: ./matrix_operations
``

Enter each matrix's dimensions between 1 and 10, then enter integer elements. Addition requires matching dimensions; multiplication requires the number of columns in Matrix A to equal the number of rows in Matrix B. Transpose operates on Matrix A.
