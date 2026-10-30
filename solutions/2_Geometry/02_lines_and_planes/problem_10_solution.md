# Exercise 10 — Projection of a Point onto a Plane

## Question

Find the orthogonal projection of \(P=(2,1,3)\) onto \(x+y+z=3\), and the reflection of \(P\) across the plane. Check that the midpoint of \(P\) and its reflection lies on the plane.

## Solution

The plane normal is \(n=(1,1,1)\). The signed plane value at \(P\) is \(2+1+3-3=3\), and \(n\cdot n=3\). The projection is
\[
H=P-\frac{3}{3}n=(2,1,3)-(1,1,1)=(1,0,2).
\]
The reflection is twice the projection minus \(P\):
\[
P'=2H-P=(0,-1,1).
\]
Their midpoint is \(\frac{P+P'}2=(1,0,2)=H\), and \(1+0+2=3\), so it lies on the plane.