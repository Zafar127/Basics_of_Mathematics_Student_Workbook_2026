# Exercise 13 — Do Four Points Lie in One Plane?

## Question

Given \(A=(0,0,0)\), \(B=(1,2,0)\), \(C=(0,1,1)\), and \(D=(2,5,1)\):

1. Construct \(\overrightarrow{AB}\) and \(\overrightarrow{AC}\).
2. Find \(n=\overrightarrow{AB}\times\overrightarrow{AC}\).
3. Construct \(\overrightarrow{AD}\) and check whether \(\overrightarrow{AD}\cdot n=0\).
4. Decide whether \(D\) lies in the plane through \(A,B,C\), and justify the criterion.

## Solution

\[
\overrightarrow{AB}=(1,2,0),\qquad
\overrightarrow{AC}=(0,1,1),\qquad
n=\overrightarrow{AB}\times\overrightarrow{AC}
=(2\cdot1-0\cdot1,\;0\cdot0-1\cdot1,\;1\cdot1-2\cdot0)
=(2,-1,1).
\]
Also \(\overrightarrow{AD}=(2,5,1)\), and
\[
\overrightarrow{AD}\cdot n=2\cdot2+5(-1)+1\cdot1=0.
\]
Since \(n\) is normal to the plane, a displacement from \(A\) lies in that plane exactly when its dot product with \(n\) is zero. Therefore \(D\) lies in the plane. Indeed, \(\overrightarrow{AD}=2\overrightarrow{AB}+\overrightarrow{AC}\).