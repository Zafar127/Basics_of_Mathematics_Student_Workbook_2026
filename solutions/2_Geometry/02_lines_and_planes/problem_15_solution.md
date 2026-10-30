# Exercise 15 — Complete Classification of a Line Relative to a Plane

## Question

For \(L:p+tv\) and \(\Pi:n\cdot x=d\), state the conditions for one intersection point, parallel with no common points, and containment. Give a numerical example of each case.

## Solution

Along the line,
\[
n\cdot(p+tv)=n\cdot p+t(n\cdot v).
\]
If \(n\cdot v\ne0\), there is exactly one intersection, at
\[
t=\frac{d-n\cdot p}{n\cdot v}.
\]
Example: \(p=(0,0,1)\), \(v=(0,0,-1)\), and plane \(z=0\) intersect at \(t=1\).

If \(n\cdot v=0\), the line's direction is parallel to the plane. When \(n\cdot p\ne d\), the line has no common points with the plane. Example: the line \((t,0,1)\) is parallel and disjoint from \(z=0\).

If \(n\cdot v=0\) and \(n\cdot p=d\), the base point lies in the plane and the direction remains in the plane, so the entire line is contained. Example: \((t,0,0)\) lies in \(z=0\).