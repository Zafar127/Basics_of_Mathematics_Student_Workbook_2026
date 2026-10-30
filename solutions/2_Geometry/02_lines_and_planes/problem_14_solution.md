# Exercise 14 — Contrast: Intersection and Parallelism

## Question

Through \(P=(0,0,1)\), consider lines with directions \(v_1=(2,1,-1)\) and \(v_2=(2,1,0)\). Analyze each relative to \(z=0\). Find the intersection for the line that intersects the plane, and explain how to recognize parallelism for the other.

## Solution

The plane normal is \(n=(0,0,1)\). For \(v_1\), \(v_1\cdot n=-1\ne0\), so the line intersects the plane. Its \(z\)-coordinate is \(1-t\), which is zero at \(t=1\); the intersection point is
\[
(2,1,0).
\]
For \(v_2\), \(v_2\cdot n=0\), so its direction is parallel to the plane. The starting point has \(z=1\), not \(0\), so the line is parallel and disjoint. This conclusion requires no parameter solving: the zero dot product tests direction, and the point confirms the line is not contained.