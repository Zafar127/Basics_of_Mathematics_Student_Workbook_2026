# Exercise 14 — A System of Equations and the Determinant

## Question

Consider the system $Ax=b$, where
$$A=\begin{pmatrix}1&2\\k&4\end{pmatrix}.$$
For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

## Solution

\[
\det A=1\cdot4-2\cdot k=4-2k.
\]
For \(k\ne2\), \(A\) is invertible, so there is exactly one solution for every \(b\).

For \(k=2\), the equations are \(x+2y=b_1\) and \(2x+4y=b_2\). For \(b=(1,2)^T\), the second equation duplicates the first; \(x=1-2y\), with \(y\) free, gives infinitely many solutions. For \(b=(1,3)^T\), doubling the first equation would require \(2=3\), so there is no solution.
