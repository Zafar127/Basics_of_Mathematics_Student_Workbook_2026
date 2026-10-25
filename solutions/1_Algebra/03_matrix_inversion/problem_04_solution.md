# Exercise 4 — Gauss–Jordan

\[
\left[\begin{array}{cc|cc}1&2&1&0\\3&5&0&1\end{array}\right]
\xrightarrow{R_2-3R_1}
\left[\begin{array}{cc|cc}1&2&1&0\\0&-1&-3&1\end{array}\right]
\xrightarrow{R_2\mapsto-R_2}
\left[\begin{array}{cc|cc}1&2&1&0\\0&1&3&-1\end{array}\right]
\]
\[
\xrightarrow{R_1-2R_2}
\left[\begin{array}{cc|cc}1&0&-5&2\\0&1&3&-1\end{array}\right].
\]
Hence \(A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}\). The same row operations transform \([A\mid I]\) into \([I\mid A^{-1}]\), since they left-multiply both blocks by the matrix that changes \(A\) into \(I\).