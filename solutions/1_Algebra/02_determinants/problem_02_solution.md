# Exercise 2 — Determinant of a \(3\times3\) Matrix

## Question

For
$$A=\begin{pmatrix}1&2&-1\\0&3&4\\2&1&5\end{pmatrix}$$
compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution

In Sarrus' rule, the three downward diagonals are added and the three upward diagonals are subtracted:
\[
\det A=(1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1)
-((-1)\cdot3\cdot2+2\cdot0\cdot5+1\cdot4\cdot1)=31-(-2)=33.
\]

As a check, replace \(R_3\) by \(R_3-2R_1\), which preserves the determinant:
\[
\begin{pmatrix}
1&2&-1\\
0&3&4\\
0&-3&7
\end{pmatrix}.
\]
The first column is now \((1,0,0)^T\), so expansion along it leaves the minor
\[
\det\begin{pmatrix}3&4\\-3&7\end{pmatrix}
=3\cdot7-4(-3)=33.
\]
