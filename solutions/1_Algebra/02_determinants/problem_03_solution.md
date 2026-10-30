# Exercise 3 — Swapping Two Rows

## Question

For
$$A=\begin{pmatrix}1&2&0\\0&3&1\\2&1&1\end{pmatrix}$$
compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

## Solution

\[
\det A
=1\det\begin{pmatrix}3&1\\1&1\end{pmatrix}
-2\det\begin{pmatrix}0&1\\2&1\end{pmatrix}
+0\det\begin{pmatrix}0&3\\2&1\end{pmatrix}
=1(3-1)-2(0-2)+0=6.
\]
This is a cofactor expansion along the first row: the three \(2\times2\) determinants are the minors obtained by deleting that row and the corresponding column.
Swapping two rows changes the determinant's sign, so the swapped matrix \(B\) should have determinant \(-6\):
\[
B=\begin{pmatrix}0&3&1\\1&2&0\\2&1&1\end{pmatrix},\qquad
\det B=-3(1-0)+(1-4)=-6.
\]
The direct calculation agrees with the prediction.
