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

Both paths give the same result, which illustrates associativity. Using the standard dense-multiplication convention, multiplying an $m\times n$ matrix by an $n\times p$ matrix uses $mnp$ scalar multiplications and $mp(n-1)$ scalar additions.

For $(AB)C$, forming $AB$ uses $2\cdot3\cdot2=12$ multiplications and $2\cdot2\cdot(3-1)=8$ additions. Multiplying that $2\times2$ result by $C$ uses $2\cdot2\cdot2=8$ multiplications and $2\cdot2\cdot(2-1)=4$ additions. The total is 20 multiplications and 12 additions.

For $A(BC)$, forming $BC$ uses $3\cdot2\cdot2=12$ multiplications and $3\cdot2\cdot(2-1)=6$ additions. Multiplying $A$ by that $3\times2$ result uses $2\cdot3\cdot2=12$ multiplications and $2\cdot2\cdot(3-1)=8$ additions. The total is 24 multiplications and 14 additions. The different intermediate dimensions lead to different operation counts, even though associativity gives the same final matrix.

## Verification and Consistency Checks

The equal final matrices verify the associative property in this example. Dimensions are compatible in both paths: $AB$ is $2\times2$, $BC$ is $3\times2$, and either final product is $2\times2$.