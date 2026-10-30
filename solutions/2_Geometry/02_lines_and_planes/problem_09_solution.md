# Exercise 9 — Distances

## Question

Compute the distance from \(P=(2,3)\) to \(3x+4y-10=0\), and from \(Q=(2,-1,3)\) to \(2x-2y+z-4=0\). Compare the formulas and explain their connection with the normal direction.

## Solution

For a line or plane \(n\cdot x+c=0\), the point-to-object distance is the absolute value of the signed normal component, \(\frac{|n\cdot x_0+c|}{\|n\|}\).
For \(P\), the line gives
\[
d=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}=\frac8{5}.
\]
For \(Q\), the plane gives
\[
d=\frac{|2(2)-2(-1)+3-4|}{\sqrt{2^2+(-2)^2+1^2}}=\frac5{3}.
\]
Both formulas divide the magnitude of the point's signed normal displacement by the normal length; only the ambient dimension differs.