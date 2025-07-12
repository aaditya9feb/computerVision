# Requirements
- Python3
- No external libraries needed

  
# Matrix Multiplication Using Nested Loops in Python
This project demonstrates how to multiply two matrices using pure Python and nested loops, without relying on libraries like NumPy.

## What Is Matrix Multiplication?
Matrix multiplication is not element-wise multiplication. Instead, each element in the result matrix is calculated by taking the dot product of a row from the first matrix (A) and a column from the second matrix (B).

For example, if:
A = [[1, 2],
     [3, 4]]

B = [[5, 6],
     [7, 8]]
Then the result matrix is:
[1*5 + 2*7, 1*6 + 2*8] = [19, 22]
[3*5 + 4*7, 3*6 + 4*8] = [43, 50]


# Formula Explanation
To calculate an element result[i][j], you do:
result[i][j] = matrix_a[i][0] * matrix_b[0][j] + matrix_a[i][1] * matrix_b[1][j]
This formula performs the dot product between:

The ith row of matrix A

The jth column of matrix B

**This works when the number of columns in A equals the number of rows in B.**
