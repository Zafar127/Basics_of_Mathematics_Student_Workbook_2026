# Exercise 12 — Homogeneous System

## Question

Solve
$$\begin{cases}x+2y-z=0,\\2x+4y-2z=0,\\x-y+2z=0.\end{cases}$$
Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

## Solution

The second equation is twice the first. From \(x+2y-z=0\), write \(x=-2y+z\). Substitution into \(x-y+2z=0\) gives \(-3y+3z=0\), so \(z=y\), then \(x=-y\). Hence
\[
(x,y,z)=s(-1,1,1),\qquad s\in\mathbb R.
\]
The zero vector is always a solution of a homogeneous system because every left-hand side becomes zero when all unknowns are zero.
