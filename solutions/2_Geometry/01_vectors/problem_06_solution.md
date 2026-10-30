# Exercise 6 — Projection and Perpendicular Component

## Question

Find the projection of \(u=(4,2)\) onto the direction \(v=(1,1)\). Compute \(r=u-\operatorname{proj}_v u\), verify that \(r\cdot v=0\), and explain the result geometrically.

## Solution

The projection formula is \(\operatorname{proj}_v u=\frac{u\cdot v}{v\cdot v}v\). Here \(u\cdot v=6\) and \(v\cdot v=2\), so
\[
\operatorname{proj}_v u=3(1,1)=(3,3),\qquad r=(4,2)-(3,3)=(1,-1).
\]
The residual is perpendicular to \(v\):
\[
r\cdot v=(1,-1)\cdot(1,1)=1-1=0.
\]
Thus \(u\) is decomposed into a component parallel to the line spanned by \(v\) and a perpendicular component.