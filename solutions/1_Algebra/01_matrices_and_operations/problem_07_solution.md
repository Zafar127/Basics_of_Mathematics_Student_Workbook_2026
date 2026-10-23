# Exercise 7: Identity Matrix, Zero Matrix, and Powers

## Problem Statement

For
$$A=\begin{pmatrix}2&1\\0&2\end{pmatrix},$$
compute $AI$, $IA$, $A+0$, $A^2$, and $A^3$, and describe the roles of $I$ and $0$ and the power pattern.

## Theoretical Background and Concepts

The identity matrix $I$ is the multiplicative identity ($AI=IA=A$). The zero matrix $0$ is the additive identity ($A+0=A$). A matrix power $A^n$ is a product of $n$ copies of $A$.

## Detailed Step-by-Step Solution

Here $I=\begin{pmatrix}1&0\\0&1\end{pmatrix}$ and $0$ is the $2\times2$ zero matrix, so
$$AI=IA=A,\qquad A+0=A.$$

$$A^2=\begin{pmatrix}2&1\\0&2\end{pmatrix}
\begin{pmatrix}2&1\\0&2\end{pmatrix}
=\begin{pmatrix}4&4\\0&4\end{pmatrix},$$
and
$$A^3=A^2A
=\begin{pmatrix}4&4\\0&4\end{pmatrix}
\begin{pmatrix}2&1\\0&2\end{pmatrix}
=\begin{pmatrix}8&12\\0&8\end{pmatrix}.$$

For the computed positive powers, the diagonal entries are $2^n$ and the upper-right entry is $n2^{n-1}$, suggesting
$$A^n=\begin{pmatrix}2^n&n2^{n-1}\\0&2^n\end{pmatrix}\quad(n\ge1).$$

## Verification and Consistency Checks

Multiplying $A^2$ by $A$ gives the displayed $A^3$; in particular, its upper-right entry is $4(1)+4(2)=12$. Multiplication by $I$ and addition of $0$ preserve each entry.