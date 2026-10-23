# Exercise 14: Rotation Matrices

## Problem Statement

For
$$R(\theta)=\begin{pmatrix}\cos\theta&-\sin\theta\\
\sin\theta&\cos\theta\end{pmatrix},$$
compute $R(\alpha)R(\beta)$ and prove it equals $R(\alpha+\beta)$.

## Theoretical Background and Concepts

The sine and cosine angle-sum identities are
$\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta$ and
$\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta$.
They allow each entry of the matrix product to be rewritten.

## Detailed Step-by-Step Solution

Multiplication gives
$$R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta&
-\cos\alpha\sin\beta-\sin\alpha\cos\beta\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta&
-\sin\alpha\sin\beta+\cos\alpha\cos\beta
\end{pmatrix}.$$

Using the angle-sum identities, this becomes
$$\begin{pmatrix}
\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\
\sin(\alpha+\beta)&\cos(\alpha+\beta)
\end{pmatrix}
=R(\alpha+\beta).$$

Geometrically, rotating first by $\beta$ and then by $\alpha$ is a rotation through the combined angle $\alpha+\beta$.

## Verification and Consistency Checks

The top-left and bottom-right entries are both the cosine sum formula; the bottom-left is the sine sum formula and the top-right is its negative. This matches the defining pattern of a rotation matrix.