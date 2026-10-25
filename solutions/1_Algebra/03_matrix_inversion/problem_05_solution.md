# Exercise 5 — A \(3\times3\) Matrix

Gauss–Jordan reduction gives
\[
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\0&1&1&0&1&0\\1&0&1&0&0&1
\end{array}\right]
\longrightarrow
\left[\begin{array}{ccc|ccc}
1&0&0&\frac12&-\frac12&\frac12\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}\right].
\]
Thus
\[
A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}.
\]
Multiplication gives \(AA^{-1}=I\): the products of the rows of \(A\) with the columns of \(A^{-1}\) give respectively \((1,0,0)\), \((0,1,0)\), and \((0,0,1)\).