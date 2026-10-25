# Exercise 15 — Two Methods for Solving the Same System

The determinant is \(5\), so
\[
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},\qquad
A^{-1}b=\frac15\begin{pmatrix}21-8\\-7+16\end{pmatrix}
=\begin{pmatrix}\frac{13}{5}\\\frac95\end{pmatrix}.
\]
By elimination, the augmented system reduces as
\[
\begin{cases}2x+y=7\\x+3y=8\end{cases}
\xrightarrow{R_1-2R_2}
\begin{cases}2x+y=7\\-5y=-9\end{cases}
\]
so \(y=9/5\), \(x=13/5\), matching the inverse method. For this one right-hand side, elimination is shorter; computing an inverse is useful when the same matrix will solve many right-hand sides.