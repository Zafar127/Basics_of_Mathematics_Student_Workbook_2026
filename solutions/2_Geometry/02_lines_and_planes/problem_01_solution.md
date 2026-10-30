# Exercise 1 — Line Through Two Points

## Question

Find the line through \(A=(1,2)\) and \(B=(4,-1)\) in parametric and general form. Give a direction vector and a normal vector, and check both points.

## Solution

A direction vector is
\[
v=B-A=(3,-3),
\]
so a parametric equation is
\[
(x,y)=(1,2)+t(3,-3),\quad t\in\mathbb R.
\]
The direction is parallel to \((1,-1)\), so \(n=(1,1)\) is a normal vector. Using \(n\cdot((x,y)-A)=0\), the general equation is
\[
x+y=3.
\]
Both points satisfy it: \(1+2=3\) and \(4+(-1)=3\). In the parametric form, \(t=0\) gives \(A\), and \(t=1\) gives \(B\).