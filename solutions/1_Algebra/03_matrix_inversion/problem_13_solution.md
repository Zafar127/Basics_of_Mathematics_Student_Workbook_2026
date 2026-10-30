# Exercise 13 — Undoing a Composite Transformation

## Question

The matrices
$$S=\begin{pmatrix}2&0\\0&1\end{pmatrix},\qquad H=\begin{pmatrix}1&1\\0&1\end{pmatrix}$$
describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

## Solution

First,
\[
T=HS
=\begin{pmatrix}
2\cdot1+0\cdot0&2\cdot1+0\cdot1\\
0\cdot1+1\cdot0&0\cdot1+1\cdot1
\end{pmatrix}
=\begin{pmatrix}2&1\\0&1\end{pmatrix},
\qquad
\det T=2\cdot1-1\cdot0=2,\qquad
T^{-1}=\frac12\begin{pmatrix}1&-1\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
\]
Using the product rule gives the same result:
\[
S^{-1}H^{-1}
=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}
\frac12\cdot1+0\cdot0&\frac12\cdot(-1)+0\cdot1\\
0\cdot1+1\cdot0&0\cdot(-1)+1\cdot1
\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
\]
The reversed (incorrect) order is
\[
H^{-1}S^{-1}
=\begin{pmatrix}1&-1\\0&1\end{pmatrix}
\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
=\begin{pmatrix}
1\cdot\frac12+(-1)\cdot0&1\cdot0+(-1)\cdot1\\
0\cdot\frac12+1\cdot0&0\cdot0+1\cdot1
\end{pmatrix}
=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix},
\]
which differs. To undo \(HS\), first undo \(H\), then \(S\), represented by \(S^{-1}H^{-1}\).
