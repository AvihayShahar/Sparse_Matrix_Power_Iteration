# Sparse_Matrix_Power_Iteration
generating a sparse matrix representation from given matrix and applying power iteration on it.

spmat.c is a module that represents a sparse matrix.
Input to main.c is a binary NxN matrix. output is Nx1 vector of highest eigen value.

The goal was to accelerate power iteration on matrixes containing a lot of 0's.
Using a smart sparse matrix representation, it is possible to multiply Mat x Vector faster
by several orders of magnitude.
