# Exercise 13 — Undoing a Composite Transformation

First,
\[
T=HS=\begin{pmatrix}2&1\\0&1\end{pmatrix},
\qquad
T^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
\]
Using the product rule gives the same result:
\[
S^{-1}H^{-1}
=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
\]
The reversed (incorrect) order is
\[
H^{-1}S^{-1}=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix},
\]
which differs. To undo \(HS\), first undo \(H\), then \(S\), represented by \(S^{-1}H^{-1}\).