# Exercise 14 — Closest Point on a Line

## Question

For \(P=(4,1)\) and the line through the origin with direction \(v=(1,2)\), use projection to find the closest point on the line and the distance to the line. Verify that the appropriate vector is perpendicular to the line direction.

## Solution

The closest point is the projection of \(P\) onto \(v\). Since \(P\cdot v=6\) and \(v\cdot v=5\),
\[
Q=\operatorname{proj}_v P=\frac65(1,2)=\left(\frac65,\frac{12}{5}\right).
\]
The residual from the line to \(P\) is
\[
P-Q=\left(\frac{14}{5},-\frac75\right),\qquad
(P-Q)\cdot v=\frac{14}{5}-\frac{14}{5}=0.
\]
Thus the segment from \(Q\) to \(P\) is perpendicular to the line. Its length, the distance, is
\[
\|P-Q\|=\sqrt{\frac{196+49}{25}}=\frac{7\sqrt5}{5}.
\]