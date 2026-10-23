# Exercise 5: Matrix Times Vector

## Problem Statement

For
$$A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},\qquad
x=\begin{pmatrix}4\\2\end{pmatrix},$$
compute $Ax$ and express it as a linear combination of the columns of $A$.

## Theoretical Background and Concepts

Matrix-vector multiplication forms dot products of matrix rows with the vector. Equivalently, the product is a linear combination of the columns of the matrix, weighted by the entries of the vector.

## Detailed Step-by-Step Solution

$$Ax=\begin{pmatrix}2(4)+(-1)(2)\\1(4)+3(2)\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}.$$

The columns of $A$ are $c_1=\begin{pmatrix}2\\1\end{pmatrix}$ and
$c_2=\begin{pmatrix}-1\\3\end{pmatrix}$. Since the entries of $x$ are 4 and 2,
$$Ax=4c_1+2c_2
=4\begin{pmatrix}2\\1\end{pmatrix}
+2\begin{pmatrix}-1\\3\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}.$$

## Verification and Consistency Checks

The column-combination result agrees with the row-by-row multiplication. The dimensions also match: a $2\times2$ matrix times a $2\times1$ vector gives a $2\times1$ vector.