# matrix
This project aims to create a header file that contains functions for matrix operations. The header file will provide a variety of functionalities such as matrix
addition, subtraction, multiplication, transposition, determinant calculation, and inverse calculation. These functions will be designed to work with matrices of different sizes and will be optimized for efficiency. The header file will be easy to use and integrate into other programs that require matrix operations, making it a valuable tool for programmers working with linear algebra.

 here's an example of how the header file can be used:
 Suppose you have two matrices:
   Matrix A:
           2 4
           1 3

   Matrix B:
           5 1
           2 7
You can use the header file to perform matrix addition as follows:

#include "matrix.h"

int main() {
  Matrix A = {{2, 4}, {1, 3}};
  Matrix B = {{5, 1}, {2, 7}};
  
  Matrix C = matrix_addition(A, B);
  
  print_matrix(C);
  
  return 0;
}

The output will be:
  Matrix C:
           7 5
           3 10
