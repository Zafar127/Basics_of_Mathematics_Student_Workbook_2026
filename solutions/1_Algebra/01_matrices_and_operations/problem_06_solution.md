# Exercise 6: Transpose

## Problem Statement

Given
$$A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix},\qquad
B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},$$
compute $A^T$, $B^T$, and $AB$, and verify $(AB)^T=B^TA^T$.

## Theoretical Background and Concepts

Transposition exchanges rows and columns. For compatible matrices, transposing a product reverses the order of the factors: $(AB)^T=B^TA^T$.

## Detailed Step-by-Step Solution

$$A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix},\qquad
B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}.$$

Multiplying rows of $A$ by columns of $B$ gives
$$AB=\begin{pmatrix}
1(1)+2(2)+3(-1)&1(0)+2(1)+3(3)\\
4(1)+5(2)+6(-1)&4(0)+5(1)+6(3)
\end{pmatrix}
=\begin{pmatrix}2&11\\8&23\end{pmatrix}.$$

Therefore
$$(AB)^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}.$$
Directly,
$$B^TA^T
=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}
\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix}
=\begin{pmatrix}2&8\\11&23\end{pmatrix}.$$

## Verification and Consistency Checks

Both sides are the same $2\times2$ matrix. The transposed product reverses factor order, and the dimensions $(2\times3)(3\times2)$ remain compatible after transposition as $(2\times3)(3\times2)$ for $B^TA^T$.