
# Exercise 1: Matrix Size and Entries

## Problem Statement

Given
$$A=\begin{pmatrix}2&-1&3\\0&4&5\end{pmatrix},\qquad
B=\begin{pmatrix}1&0\\-2&3\\4&1\end{pmatrix},$$
find their sizes, the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$, the second row of $A$, and the first column of $B$.

## Theoretical Background and Concepts

The size of a matrix is its number of rows by its number of columns. An entry $a_{ij}$ lies in row $i$, column $j$.

## Detailed Step-by-Step Solution

- $A$ has 2 rows and 3 columns, so its size is $2\times3$.
- $B$ has 3 rows and 2 columns, so its size is $3\times2$.
- Reading entries by their row and column indices gives
  $$a_{12}=-1,\quad a_{23}=5,\quad b_{21}=-2,\quad b_{32}=1.$$
- The second row of $A$ is $(0,4,5)$.
- The first column of $B$, written as a column vector, is
  $$\begin{pmatrix}1\\-2\\4\end{pmatrix}.$$

## Verification and Consistency Checks

Each listed entry is in the specified row and column. The row has three entries, matching the three columns of $A$, and the column has three entries, matching the three rows of $B$.
