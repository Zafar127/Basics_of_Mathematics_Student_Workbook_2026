# Exercise 7 — Inverse of a Product

\[
AB=\begin{pmatrix}2&3\\0&3\end{pmatrix},\qquad
(AB)^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}.
\]
Since \(A^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}\) and
\(B^{-1}=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}\),
\[
B^{-1}A^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}=(AB)^{-1}.
\]
The order reverses because undoing the action of \(A\) followed by \(B\) requires undoing \(B\) first, then \(A\).