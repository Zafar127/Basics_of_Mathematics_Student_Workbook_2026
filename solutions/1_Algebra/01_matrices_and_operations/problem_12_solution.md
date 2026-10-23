# Exercise 12: Formula for a Matrix Power

## Problem Statement

For
$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},$$
compute $A^2,A^3,A^4$, conjecture a formula for $A^n$, and prove the formula by induction.

## Theoretical Background and Concepts

Matrix powers are repeated products. A formula suggested by several cases can be proved for all positive integers by verifying a base case and showing that truth for $n$ implies truth for $n+1$.

## Detailed Step-by-Step Solution

$$A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\qquad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.$$
These calculations suggest
$$A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.$$

For the induction proof, the formula holds for $n=1$, since it gives $A$. Suppose it holds for some $n\ge1$. Then
$$A^{n+1}=A^nA
=\begin{pmatrix}1&n\\0&1\end{pmatrix}
\begin{pmatrix}1&1\\0&1\end{pmatrix}
=\begin{pmatrix}1&n+1\\0&1\end{pmatrix},$$
which is exactly the formula with $n+1$ in place of $n$. Therefore it holds for every positive integer $n$.

## Verification and Consistency Checks

The general formula gives the computed cases by setting $n=2,3,4$. The induction step preserves diagonal entries 1 and increases the upper-right entry by 1.