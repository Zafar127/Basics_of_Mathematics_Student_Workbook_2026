# Exercise 14 — A Matrix That Is Its Own Inverse

## Question

Assume that a square matrix $A$ satisfies
$$A^2=I.$$
Show that
$$A^{-1}=A.$$
Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

## Solution

Since \(A^2=I\), we have \(AA=I\). By the definition of an inverse, \(A^{-1}=A\).

For an example distinct from \(I\) and \(-I\), take
\[
A=\begin{pmatrix}1&0\\0&-1\end{pmatrix}.
\]
Multiplying entry by entry,
\[
A^2=
\begin{pmatrix}
1\cdot1+0\cdot0&1\cdot0+0\cdot(-1)\\
0\cdot1+(-1)\cdot0&0\cdot0+(-1)\cdot(-1)
\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I.
\]
Thus this matrix is its own inverse.
