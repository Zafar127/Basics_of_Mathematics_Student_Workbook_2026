# Exercise 8 — Determinant of a Product

## Question

Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

## Solution

\[
\det(AB)=\det A\det B=3(-5)=-15,\qquad
\det(BA)=\det B\det A=-15.
\]
Since \(\det A=3\ne0\), \(A^{-1}\) exists and
\[
\det(A^{-1}B)=\det(A^{-1})\det B=\frac{1}{3}(-5)=-\frac53.
\]
The product determinant is the product of the determinants, which is independent of order; this does not imply that the matrices \(AB\) and \(BA\) themselves are equal.
