# Exercise 8: Row Operations and Their Reversibility

## Problem Statement

Starting with
$$A=\begin{pmatrix}1&2&-1\\2&4&1\\-1&1&3\end{pmatrix},$$
perform, in order, $R_2\leftarrow R_2-2R_1$, $R_3\leftarrow R_3+R_1$, and then swap rows 2 and 3. State the inverse operation for each step.

## Theoretical Background and Concepts

An elementary row operation changes only the rows specified. Replacing a row by itself plus a multiple of another row is reversed by adding the opposite multiple; swapping the same two rows twice restores the original order.

## Detailed Step-by-Step Solution

1. Apply $R_2\leftarrow R_2-2R_1$. The new second row is
   $(2,4,1)-2(1,2,-1)=(0,0,3)$:
   $$\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix}.$$
   Reverse this with $R_2\leftarrow R_2+2R_1$.
2. Apply $R_3\leftarrow R_3+R_1$. The new third row is
   $(-1,1,3)+(1,2,-1)=(0,3,2)$:
   $$\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix}.$$
   Reverse this with $R_3\leftarrow R_3-R_1$.
3. Interchange $R_2$ and $R_3$:
   $$\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}.$$
   Reverse this by interchanging $R_2$ and $R_3$ again.

## Verification and Consistency Checks

In each replacement, only the target row changes. For example, applying $R_2\leftarrow R_2+2R_1$ to the first result restores $(2,4,1)$.