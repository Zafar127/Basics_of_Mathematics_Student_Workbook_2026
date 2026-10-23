# Exercise 9: Composing Transformations

## Problem Statement

Let
$$S=\begin{pmatrix}2&0\\0&1\end{pmatrix},\qquad
R=\begin{pmatrix}0&-1\\1&0\end{pmatrix},\qquad
x=\begin{pmatrix}1\\2\end{pmatrix}.$$
Compute $RSx$ and $SRx$ and compare the transformations.

## Theoretical Background and Concepts

In a product of transformation matrices, the rightmost matrix acts first. The matrix $S$ doubles the horizontal coordinate, while $R$ rotates a vector $90^\circ$ counterclockwise.

## Detailed Step-by-Step Solution

First scale, then rotate:
$$Sx=\begin{pmatrix}2\\2\end{pmatrix},\qquad
RSx=\begin{pmatrix}0&-1\\1&0\end{pmatrix}\begin{pmatrix}2\\2\end{pmatrix}
=\begin{pmatrix}-2\\2\end{pmatrix}.$$

First rotate, then scale:
$$Rx=\begin{pmatrix}-2\\1\end{pmatrix},\qquad
SRx=\begin{pmatrix}2&0\\0&1\end{pmatrix}\begin{pmatrix}-2\\1\end{pmatrix}
=\begin{pmatrix}-4\\1\end{pmatrix}.$$

The results differ because scaling before the rotation doubles the original horizontal component, which becomes the vertical component after rotation; scaling afterward instead doubles the rotated horizontal component.

## Verification and Consistency Checks

The computed vectors are different, $(-2,2)^T\ne(-4,1)^T$, showing that the order of these transformations matters.