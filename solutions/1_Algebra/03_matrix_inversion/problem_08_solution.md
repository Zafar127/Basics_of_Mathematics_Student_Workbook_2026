# Exercise 8 — Inverse of a Transformation

## Question

The matrix
$$S=\begin{pmatrix}2&0\\0&\frac12\end{pmatrix}$$
describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

## Solution

\[
S^{-1}=\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}.
\]
It reverses the scaling: horizontal coordinates are halved and vertical coordinates are doubled. For example,
\[
\begin{pmatrix}2&0\\0&\frac12\end{pmatrix}\begin{pmatrix}2\\4\end{pmatrix}
=\begin{pmatrix}4\\2\end{pmatrix},\qquad
S^{-1}\begin{pmatrix}4\\2\end{pmatrix}=\begin{pmatrix}2\\4\end{pmatrix}.
\]
