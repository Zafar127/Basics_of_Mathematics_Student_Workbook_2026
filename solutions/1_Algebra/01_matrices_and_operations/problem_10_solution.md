# Exercise 10: Columns of a Matrix Product

## Problem Statement

Given
$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\qquad
B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix},$$
compute $Ab_1$, $Ab_2$, and $AB$, where $b_1,b_2$ are the columns of $B$.

## Theoretical Background and Concepts

If $B=[b_1\ b_2]$, then multiplying by $A$ acts on each column: $AB=[Ab_1\ Ab_2]$. This follows directly from the definition of matrix multiplication.

## Detailed Step-by-Step Solution

The columns are
$$b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},\qquad
b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}.$$
Thus
$$Ab_1=\begin{pmatrix}1-2+0\\0-1+3\end{pmatrix}
=\begin{pmatrix}-1\\2\end{pmatrix},\qquad
Ab_2=\begin{pmatrix}2+0+0\\0+0+1\end{pmatrix}
=\begin{pmatrix}2\\1\end{pmatrix}.$$

Putting these vectors side by side gives
$$AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}.$$
Its first and second columns are exactly $Ab_1$ and $Ab_2$.

## Verification and Consistency Checks

Direct row-by-column multiplication gives the same four entries: $1-2=-1$, $2=2$, $-1+3=2$, and $1=1$. The product size is $2\times2$.