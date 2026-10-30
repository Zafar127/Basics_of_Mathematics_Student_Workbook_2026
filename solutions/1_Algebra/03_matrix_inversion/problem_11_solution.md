# Exercise 11 — Parameter and Invertibility

## Question

For
$$A(t)=\begin{pmatrix}1&t\\t&1\end{pmatrix}$$
find all $t$ for which the matrix is invertible, and then give a formula for $A(t)^{-1}$. Explain what happens to this formula at the excluded values.

## Solution

For \(\begin{pmatrix}a&b\\c&d\end{pmatrix}\), the inverse is
\(\frac1{ad-bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}\), provided \(ad-bc\ne0\).
Here
\[
\det A(t)=1\cdot1-t\cdot t=1-t^2.
\]
Thus \(A(t)\) is invertible exactly when \(t\ne\pm1\), and substituting its entries into the inverse rule gives
\[
A(t)^{-1}=\frac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}.
\]
At \(t=1\) or \(t=-1\), the determinant is zero and the denominator vanishes; the rows (and columns) are dependent, so no inverse exists.
