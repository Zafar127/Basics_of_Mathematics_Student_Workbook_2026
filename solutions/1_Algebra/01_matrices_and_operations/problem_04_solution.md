# Exercise 4: Matrix Multiplication and Noncommutativity

## Problem Statement

For
$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad
B=\begin{pmatrix}2&0\\3&1\end{pmatrix},$$
compute $AB$ and $BA$, then compare them.

## Theoretical Background and Concepts

Each entry of a matrix product is the dot product of a row of the first matrix with a column of the second. Matrix multiplication is not generally commutative: reversing the factor order can change the result.

## Detailed Step-by-Step Solution

$$AB=\begin{pmatrix}
1(2)+2(3)&1(0)+2(1)\\
0(2)+1(3)&0(0)+1(1)
\end{pmatrix}
=\begin{pmatrix}8&2\\3&1\end{pmatrix}.$$

$$BA=\begin{pmatrix}
2(1)+0(0)&2(2)+0(1)\\
3(1)+1(0)&3(2)+1(1)
\end{pmatrix}
=\begin{pmatrix}2&4\\3&7\end{pmatrix}.$$

Thus $AB\ne BA$. Noncommutativity means that the order of matrix factors matters.

## Verification and Consistency Checks

Both products are defined and $2\times2$. Their top-left entries already differ (8 versus 2), confirming the matrices are unequal.