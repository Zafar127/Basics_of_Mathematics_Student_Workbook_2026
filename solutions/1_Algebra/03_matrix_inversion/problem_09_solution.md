# Exercise 9 — Matrix Equation

## Question

Given
$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}3&1\\2&4\end{pmatrix}.$$
Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

## Solution

From \(AX=B\), multiply on the left by \(A^{-1}\). Associativity gives \(A^{-1}(AX)=(A^{-1}A)X=X\), so \(X=A^{-1}B\). The \(2\times2\) formula gives \(A^{-1}=\frac1{\det A}\begin{pmatrix}1&-2\\0&1\end{pmatrix}\); since \(\det A=1\),
\[
A^{-1}=\begin{pmatrix}1&-2\\0&1\end{pmatrix},\qquad
X=\begin{pmatrix}1&-2\\0&1\end{pmatrix}
\begin{pmatrix}3&1\\2&4\end{pmatrix}
=\begin{pmatrix}
1\cdot3+(-2)\cdot2&1\cdot1+(-2)\cdot4\\
0\cdot3+1\cdot2&0\cdot1+1\cdot4
\end{pmatrix}
=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}.
\]
Check:
\[
AX=\begin{pmatrix}1&2\\0&1\end{pmatrix}
\begin{pmatrix}-1&-7\\2&4\end{pmatrix}
=\begin{pmatrix}
1\cdot(-1)+2\cdot2&1\cdot(-7)+2\cdot4\\
0\cdot(-1)+1\cdot2&0\cdot(-7)+1\cdot4
\end{pmatrix}
=\begin{pmatrix}3&1\\2&4\end{pmatrix}=B.
\]
