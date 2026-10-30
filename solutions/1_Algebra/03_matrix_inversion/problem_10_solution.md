# Exercise 10 — Inverse of a Diagonal Matrix

## Question

Given
$$D=\begin{pmatrix}2&0&0\\0&-3&0\\0&0&5\end{pmatrix},\qquad E=\begin{pmatrix}2&0&0\\0&0&0\\0&0&5\end{pmatrix}.$$
Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

## Solution

\(D\) is invertible because all diagonal entries are nonzero. \(E\) is not invertible because its middle diagonal entry is zero.
\[
D^{-1}=\begin{pmatrix}\frac12&0&0\\0&-\frac13&0\\0&0&\frac15\end{pmatrix},
\qquad
DD^{-1}=\begin{pmatrix}
2\cdot\frac12&0&0\\
0&(-3)\cdot(-\frac13)&0\\
0&0&5\cdot\frac15
\end{pmatrix}
=\begin{pmatrix}1&0&0\\0&1&0\\0&0&1\end{pmatrix}=I.
\]
The inverse is formed by taking the reciprocal of each nonzero diagonal entry; off-diagonal entries remain zero. The diagonal checks are \(2\cdot\frac12=1\), \((-3)(-\frac13)=1\), and \(5\cdot\frac15=1\).
