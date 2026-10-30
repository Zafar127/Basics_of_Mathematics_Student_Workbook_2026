# Exercise 6 — Solving a System Using the Inverse

## Question

Solve
$$Ax=b,$$
where
$$A=\begin{pmatrix}2&1\\1&3\end{pmatrix},\qquad b=\begin{pmatrix}5\\7\end{pmatrix},$$
using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

## Solution

\[
\det A=2\cdot3-1=5,\qquad
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}.
\]
For \(A=\begin{pmatrix}a&b\\c&d\end{pmatrix}\), the inverse is
\(\frac1{ad-bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}\) when \(ad-bc\ne0\); here the determinant is \(5\). Multiplying \(Ax=b\) on the left by \(A^{-1}\) gives
\[
A^{-1}Ax=(A^{-1}A)x=Ix=x=A^{-1}b.
\]
Therefore
\[
x=A^{-1}b=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}
\begin{pmatrix}5\\7\end{pmatrix}
=\frac15\begin{pmatrix}3\cdot5+(-1)\cdot7\\(-1)\cdot5+2\cdot7\end{pmatrix}
=\begin{pmatrix}\frac85\\\frac95\end{pmatrix}.
\]
Check:
\[
A x=\begin{pmatrix}2(8/5)+9/5\\8/5+3(9/5)\end{pmatrix}
=\begin{pmatrix}5\\7\end{pmatrix}=b.
\]
