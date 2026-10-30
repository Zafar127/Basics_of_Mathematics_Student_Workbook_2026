# Exercise 13 — Closest Point on a Plane

## Question

Find the point on \(x+2y+2z=4\) closest to \(P=(3,0,0)\), give the distance, and check that the joining segment is perpendicular to the plane.

## Solution

The normal is \(n=(1,2,2)\), with \(n\cdot n=9\). At \(P\), the plane's left side is \(3\), one less than \(4\). Move one third of the normal to reach the plane:
\[
H=P+\frac19n=(3,0,0)+\left(\frac19,\frac29,\frac29\right)
=\left(\frac{28}{9},\frac29,\frac29\right).
\]
Indeed, \(x+2y+2z=\frac{28+4+4}{9}=4\). The distance is
\[
\|H-P\|=\frac13\|n\|=\frac13\cdot3=1.
\]
The displacement \(H-P=\frac19n\) is parallel to the plane normal, hence perpendicular to the plane.