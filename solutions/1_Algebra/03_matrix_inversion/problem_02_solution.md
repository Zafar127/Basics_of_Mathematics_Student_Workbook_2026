# Exercise 2 — Formula for a \(2\times2\) Matrix

## Question

Find the inverse of
$$A=\begin{pmatrix}3&2\\5&4\end{pmatrix}$$
using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

## Solution

For \(\begin{pmatrix}a&b\\c&d\end{pmatrix}\), the inverse is
\(\frac1{ad-bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}\) when \(ad-bc\ne0\).
Here \(\det A=3\cdot4-2\cdot5=2\ne0\), so the formula applies:
\[
A^{-1}=\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}
=\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}.
\]
Verification by multiplying the entries gives
\[
AA^{-1}=\begin{pmatrix}3&2\\5&4\end{pmatrix}
\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}
=\begin{pmatrix}
3\cdot2+2\cdot(-\frac52)&3\cdot(-1)+2\cdot\frac32\\
5\cdot2+4\cdot(-\frac52)&5\cdot(-1)+4\cdot\frac32
\end{pmatrix}
=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I.
\]
This identity product confirms that the proposed matrix is the inverse.
