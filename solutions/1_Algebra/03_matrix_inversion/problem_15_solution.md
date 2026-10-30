# Exercise 15 — Two Methods for Solving the Same System

## Question

For
$$A=\begin{pmatrix}2&1\\1&3\end{pmatrix},\qquad b=\begin{pmatrix}7\\8\end{pmatrix}$$
solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

## Solution

The determinant is \(2\cdot3-1\cdot1=5\), so the \(2\times2\) inverse formula gives
\[
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},\qquad
A^{-1}b=\frac15\begin{pmatrix}21-8\\-7+16\end{pmatrix}
=\begin{pmatrix}\frac{13}{5}\\\frac95\end{pmatrix}.
\]
By elimination, the augmented system reduces as
\[
\begin{cases}2x+y=7\\x+3y=8\end{cases}
\xrightarrow{R_2\leftarrow R_1-2R_2}
\begin{cases}2x+y=7\\-5y=-9\end{cases}
\]
so back-substitution gives \(y=9/5\) and then \(2x+9/5=7\), hence \(x=13/5\), matching the inverse method.

The inverse method requires computing the determinant and inverse, then multiplying \(A^{-1}b\). Elimination uses one row update and back-substitution. Thus elimination has fewer essential steps for this single right-hand side; an inverse may be reusable when solving for many right-hand sides with the same matrix.
