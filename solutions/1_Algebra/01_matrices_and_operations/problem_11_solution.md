# Exercise 11: When Do Matrices Commute?

## Problem Statement

For
$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},\qquad
B=\begin{pmatrix}a&b\\c&d\end{pmatrix},$$
find the conditions on $a,b,c,d$ such that $AB=BA$ and describe all such $B$.

## Theoretical Background and Concepts

Two matrices commute when their products in both orders are equal. Equality of matrices is equivalent to equality of all corresponding entries.

## Detailed Step-by-Step Solution

Compute both products:
$$AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix},\qquad
BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}.$$

Equating entries gives $a+c=a$, so $c=0$; $b+d=a+b$, so $d=a$; and $d=c+d$, again giving $c=0$. The remaining entry equality is already satisfied.

Therefore $a,b$ are arbitrary and $c=0,d=a$. All commuting matrices have the form
$$B=\begin{pmatrix}a&b\\0&a\end{pmatrix}.$$

## Verification and Consistency Checks

Substitution confirms
$$AB=BA=\begin{pmatrix}a& a+b\\0&a\end{pmatrix}$$
for every matrix of the stated form.