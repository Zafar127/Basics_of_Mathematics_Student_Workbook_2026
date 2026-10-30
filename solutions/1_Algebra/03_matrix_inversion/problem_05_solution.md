# Exercise 5 — A \(3\times3\) Matrix

## Question

Use Gauss–Jordan elimination to find the inverse of
$$A=\begin{pmatrix}1&1&0\\0&1&1\\1&0&1\end{pmatrix}.$$
Check the result by multiplication.

## Solution

Gauss–Jordan reduction gives
\[
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\0&1&1&0&1&0\\1&0&1&0&0&1
\end{array}\right]
\xrightarrow{R_3\leftarrow R_3-R_1}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\0&1&1&0&1&0\\0&-1&1&-1&0&1
\end{array}\right]
\xrightarrow{R_3\leftarrow R_3+R_2}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&2&-1&1&1
\end{array}\right]
\xrightarrow{R_3\leftarrow \frac12R_3}
\left[\begin{array}{ccc|ccc}
1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&1&-\frac12&\frac12&\frac12
\end{array}\right]
\xrightarrow{R_2\leftarrow R_2-R_3,\ R_1\leftarrow R_1-R_2}
\left[\begin{array}{ccc|ccc}
1&0&0&\frac12&-\frac12&\frac12\\
0&1&0&\frac12&\frac12&-\frac12\\
0&0&1&-\frac12&\frac12&\frac12
\end{array}\right].
\]
Each row operation is applied to both blocks, preserving the represented equations. Reducing the left block to \(I\) therefore leaves \(A^{-1}\) on the right.
Thus
\[
A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}.
\]
For an entry-by-entry check,
\[
AA^{-1}
=\frac12\begin{pmatrix}
1-1+0&-1+1+0&1-1+0\\
0+1-1&0+1+1&0-1+1\\
1+0-1&-1+0+1&1+0+1
\end{pmatrix}
=I.
\]
