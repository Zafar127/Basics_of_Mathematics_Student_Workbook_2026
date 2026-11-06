# Exercise 5 — Relative Position of Two Lines

## Question

Classify
\[
L_1:(x,y,z)=(1,1,0)+t(1,2,1),\qquad
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
\]
If they intersect, give their intersection point; otherwise, determine whether they are parallel or skew.

## Solution

Equating coordinates gives
\[
1+t=2,\qquad 1+2t=s,\qquad t=1-s.
\]
The first equation gives \(t=1\); then the second gives \(s=3\). But the third equation would require \(1=1-3=-2\), which is impossible, so the lines do not intersect. Their direction vectors \((1,2,1)\) and \((0,1,-1)\) are not proportional, so they are not parallel either. They are skew lines.

The corresponding points at the candidate parameters are
\[
\text{on }L_1:(2,3,1),\qquad\text{on }L_2:(2,3,-2),
\]
which differ in their third coordinate.