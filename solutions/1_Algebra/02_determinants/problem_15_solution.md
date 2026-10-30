# Exercise 15 — Combining Determinant Properties

## Question

Let $A$ and $B$ be invertible $2\times2$ matrices with
$$\det A=-2,\qquad \det B=3.$$
Without finding the entries of the matrices, compute
$$\det\left(B^{-1}A^TB\right).$$
State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

## Solution

\[
\det(B^{-1}A^TB)
=\det(B^{-1})\det(A^T)\det(B)
=\frac1{3}(-2)(3)=-2.
\]
By multiplicativity, the determinant of the product is the product of the determinants of its factors. Then \(\det(B^{-1})=1/\det B\) and \(\det(A^T)=\det A\), so the \(B\)-factors cancel because \(\det(B^{-1})\det B=1\).
