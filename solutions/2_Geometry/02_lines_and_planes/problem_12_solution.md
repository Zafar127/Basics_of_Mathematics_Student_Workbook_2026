# Exercise 12 — Intersection Line of Two Planes

## Question

Find a parametric equation for the intersection of \(x+y+z=3\) and \(x-y+z=1\). Find its direction vector both from the equations and from the cross product of the normals, and compare.

## Solution

Subtracting the second plane equation from the first gives \(2y=2\), so \(y=1\); then \(x+z=2\). Let \(z=t\), giving
\[
(x,y,z)=(2-t,1,t)=(2,1,0)+t(-1,0,1).
\]
The direction from this parameterization is \((-1,0,1)\). The plane normals are \(n_1=(1,1,1)\), \(n_2=(1,-1,1)\), and
\[
n_1\times n_2=(2,0,-2)=-2(-1,0,1),
\]
which is a nonzero scalar multiple of the same direction. Substitution shows the parameterized points satisfy both plane equations.