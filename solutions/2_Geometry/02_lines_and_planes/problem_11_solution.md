# Exercise 11 — Plane Containing a Line and a Point

## Question

Find the plane containing \((x,y,z)=(1,0,2)+t(1,1,-1)\) and \(P=(0,2,1)\). Check that the entire line and \(P\) lie in it.

## Solution

The line passes through \(A=(1,0,2)\) with direction \(v=(1,1,-1)\). A second direction in the plane is
\[
w=P-A=(-1,2,-1).
\]
Their cross product is a normal:
\[
n=v\times w
=(1\cdot(-1)-(-1)\cdot2,\;(-1)\cdot(-1)-1\cdot(-1),\;1\cdot2-1\cdot(-1))
=(1,2,3).
\]
The plane through \(A\) is therefore
\[
(x-1)+2y+3(z-2)=0,\quad\text{or}\quad x+2y+3z=7.
\]
For every point on the line, \(x+2y+3z=(1+t)+2t+3(2-t)=7\). The given point also satisfies \(0+4+3=7\).