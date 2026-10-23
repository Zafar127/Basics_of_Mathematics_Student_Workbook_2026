# Exercise 15: Associativity of Multiplication and Different Calculation Paths

## Problem Statement

Given
$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad
B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},\quad
C=\begin{pmatrix}2&1\\0&-1\end{pmatrix},$$
compute $(AB)C$ and $A(BC)$, compare them, and explain associativity.

## Theoretical Background and Concepts

Matrix multiplication is associative: $(AB)C=A(BC)$ whenever the dimensions are compatible. The parentheses can change the calculation path without changing the final product.

## Detailed Step-by-Step Solution

First calculate
$$AB=\begin{pmatrix}5&2\\1&4\end{pmatrix}.$$
Then
$$(AB)C
=\begin{pmatrix}5&2\\1&4\end{pmatrix}
\begin{pmatrix}2&1\\0&-1\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

For the other grouping,
$$BC=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix},$$
so
$$A(BC)
=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}
\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

Both paths give the same result, which illustrates associativity. For this example, forming $AB$ first uses $2\cdot3\cdot2+2\cdot2\cdot2=20$ scalar multiplications; forming $BC$ first uses $3\cdot2\cdot2+2\cdot3\cdot2=24$. Thus the first grouping uses fewer scalar multiplications.

## Verification and Consistency Checks

The equal final matrices verify the associative property in this example. Dimensions are compatible in both paths: $AB$ is $2\times2$, $BC$ is $3\times2$, and either final product is $2\times2$.