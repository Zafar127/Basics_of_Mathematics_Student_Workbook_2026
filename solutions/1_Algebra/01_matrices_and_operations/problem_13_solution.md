# Exercise 13: A Recurrence Written in Matrix Form

## Problem Statement

For
$$F=\begin{pmatrix}1&1\\1&0\end{pmatrix},$$
compute $F^2$ through $F^5$, relate their entries to the Fibonacci sequence, and explain the action of $F$ on $(a,b)^T$.

## Theoretical Background and Concepts

The Fibonacci sequence is defined by $F_0=0$, $F_1=1$, and $F_{k+1}=F_k+F_{k-1}$. Matrix multiplication can encode this recurrence as an update of a pair of consecutive terms.

## Detailed Step-by-Step Solution

Repeated multiplication gives
$$F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},\quad
F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},\quad
F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},\quad
F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}.$$

The entries are consecutive Fibonacci numbers. In general, for $n\ge1$,
$$F^n=\begin{pmatrix}F_{n+1}&F_n\\F_n&F_{n-1}\end{pmatrix}.$$
For a pair of consecutive terms,
$$F\begin{pmatrix}a\\b\end{pmatrix}
=\begin{pmatrix}a+b\\a\end{pmatrix}.$$
If $a,b$ are consecutive terms with $a$ the later one, this creates their sum as the next term and retains $a$ as the second component for the next step.

## Verification and Consistency Checks

For example, $F^5$ contains $8,5,5,3$, matching the Fibonacci sequence at the corresponding indices. Applying the formula to $(1,0)^T$ gives $(1,1)^T$, the first recurrence update from the initial pair.