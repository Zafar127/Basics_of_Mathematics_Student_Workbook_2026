# Exercise 13 — Determinant by Elimination

Use determinant-preserving row additions:
\[
\begin{pmatrix}1&2&3\\2&5&7\\1&0&2\end{pmatrix}
\xrightarrow{R_2-2R_1}
\begin{pmatrix}1&2&3\\0&1&1\\1&0&2\end{pmatrix}
\xrightarrow{R_3-R_1}
\begin{pmatrix}1&2&3\\0&1&1\\0&-2&-1\end{pmatrix}
\xrightarrow{R_3+2R_2}
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}.
\]
All operations preserve the determinant. The upper-triangular determinant is \(1\cdot1\cdot1=1\), hence \(\det A=1\).