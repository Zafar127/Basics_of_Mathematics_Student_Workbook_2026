# Exercise 12 — A Normal Vector to a Plane

## Question

Given \(A=(1,0,2)\), \(B=(2,1,0)\), and \(C=(0,3,1)\), construct two vectors in the plane, find a vector perpendicular to both, and check perpendicularity using dot products.

## Solution

Two vectors in the plane are
\[
\overrightarrow{AB}=B-A=(1,1,-2),\qquad
\overrightarrow{AC}=C-A=(-1,3,-1).
\]
Their cross product gives a normal vector:
\[
n=\overrightarrow{AB}\times\overrightarrow{AC}
=(1\cdot(-1)-(-2)\cdot3,\;(-2)\cdot(-1)-1\cdot(-1),\;1\cdot3-1\cdot(-1))
=(5,3,4).
\]
Check both dot products:
\[
n\cdot\overrightarrow{AB}=5+3-8=0,\qquad
n\cdot\overrightarrow{AC}=-5+9-4=0.
\]
Thus \(n\) is perpendicular to both directions lying in the plane.