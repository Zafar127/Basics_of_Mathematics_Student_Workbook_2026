# Exercise 12 — Finding Inverses from Known Properties

## Question

It is known that
$$A^{-1}=\begin{pmatrix}2&-1\\-3&2\end{pmatrix}.$$
Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

## Solution

\[
(3A)^{-1}=\frac13A^{-1}
=\begin{pmatrix}\frac23&-\frac13\\-1&\frac23\end{pmatrix}.
\]
Also,
\[
(A^T)^{-1}=(A^{-1})^T=\begin{pmatrix}2&-3\\-1&2\end{pmatrix},
\qquad
(A^2)^{-1}=(A^{-1})^2
=\begin{pmatrix}
2\cdot2+(-1)\cdot(-3)&2\cdot(-1)+(-1)\cdot2\\
(-3)\cdot2+2\cdot(-3)&(-3)\cdot(-1)+2\cdot2
\end{pmatrix}
=\begin{pmatrix}7&-4\\-12&7\end{pmatrix}.
\]
These follow by multiplying the proposed inverses by the corresponding matrices; for the square, the inverse product reverses order, and both factors are \(A^{-1}\).
