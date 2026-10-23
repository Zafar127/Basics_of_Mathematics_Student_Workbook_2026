# Exercise 2: Addition and Scalar Multiplication

## Problem Statement

For
$$A=\begin{pmatrix}1&2\\-1&3\end{pmatrix},\qquad
B=\begin{pmatrix}4&-2\\0&5\end{pmatrix},$$
compute $A+B$, $A-B$, and $3A-2B$, and explain the size requirement for addition.

## Theoretical Background and Concepts

Addition and subtraction are performed entry by entry, and are defined only when both matrices have the same dimensions. Scalar multiplication multiplies every entry by the scalar.

## Detailed Step-by-Step Solution

$$A+B=\begin{pmatrix}1+4&2+(-2)\\-1+0&3+5\end{pmatrix}
=\begin{pmatrix}5&0\\-1&8\end{pmatrix}.$$

$$A-B=\begin{pmatrix}1-4&2-(-2)\\-1-0&3-5\end{pmatrix}
=\begin{pmatrix}-3&4\\-1&-2\end{pmatrix}.$$

First scale each matrix, then subtract:
$$3A=\begin{pmatrix}3&6\\-3&9\end{pmatrix},\qquad
2B=\begin{pmatrix}8&-4\\0&10\end{pmatrix},$$
so
$$3A-2B=\begin{pmatrix}3-8&6-(-4)\\-3-0&9-10\end{pmatrix}
=\begin{pmatrix}-5&10\\-3&-1\end{pmatrix}.$$

Addition requires equal sizes because every entry in one matrix must have a corresponding entry in the same position in the other.

## Verification and Consistency Checks

All results are $2\times2$, the same size as the inputs. In $3A-2B$, for example, the top-right entry is $3(2)-2(-2)=10$.