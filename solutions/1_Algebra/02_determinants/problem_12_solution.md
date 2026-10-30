# Exercise 12 — A Parameter Revealed by a Row Operation

## Question

For
$$A(t)=\begin{pmatrix}1&2&3\\2&4&t\\0&1&1\end{pmatrix}$$
find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation
$$R_2\leftarrow R_2-2R_1$$
and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

## Solution

The operation \(R_2\leftarrow R_2-2R_1\) preserves the determinant and gives
\[
\begin{pmatrix}1&2&3\\0&0&t-6\\0&1&1\end{pmatrix}.
\]
Expanding along the first column, the determinant is
\[
\det\begin{pmatrix}0&t-6\\1&1\end{pmatrix}=6-t.
\]
Thus the matrix is singular only for \(t=6\). At this value the original second row \((2,4,6)\) is twice the first row, so the rows are dependent.
