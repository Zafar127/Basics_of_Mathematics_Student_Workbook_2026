# Exercise 7 — Inverse of a Product

## Question

For
$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}2&0\\0&3\end{pmatrix}$$
compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

## Solution

\[
AB=\begin{pmatrix}2&3\\0&3\end{pmatrix},\qquad
\det(AB)=6,\qquad
(AB)^{-1}=\frac1{\det(AB)}\begin{pmatrix}3&-3\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}.
\]
Since \(A^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}\) and
\(B^{-1}=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}\),
\[
B^{-1}A^{-1}
=\begin{pmatrix}
\frac12\cdot1+0\cdot0&\frac12\cdot(-1)+0\cdot1\\
0\cdot1+\frac13\cdot0&0\cdot(-1)+\frac13\cdot1
\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}
=(AB)^{-1}.
\]
The product \(AB\) applies \(B\) first and then \(A\). To undo it, apply \(A^{-1}\) first and then \(B^{-1}\), which gives the reversed product; indeed \(B^{-1}A^{-1}AB=B^{-1}(A^{-1}A)B=I\).
