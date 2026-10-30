# Exercise 1 — Definition of the Inverse

## Question

For
$$A=\begin{pmatrix}2&1\\1&1\end{pmatrix},\qquad B=\begin{pmatrix}1&-1\\-1&2\end{pmatrix}$$
check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

## Solution

\[
AB=\begin{pmatrix}2&1\\1&1\end{pmatrix}
\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
=\begin{pmatrix}
2\cdot1+1\cdot(-1)&2\cdot(-1)+1\cdot2\\
1\cdot1+1\cdot(-1)&1\cdot(-1)+1\cdot2
\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix},
\quad
BA=\begin{pmatrix}1&-1\\-1&2\end{pmatrix}
\begin{pmatrix}2&1\\1&1\end{pmatrix}
=\begin{pmatrix}
1\cdot2+(-1)\cdot1&1\cdot1+(-1)\cdot1\\
(-1)\cdot2+2\cdot1&(-1)\cdot1+2\cdot1
\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix}.
\]

Both products equal the identity matrix \(I\), so \(B=A^{-1}\) by the definition of a two-sided inverse.
