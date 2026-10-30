# Exercise 15 — Recognition and Sketch Without a Given Name

## Question

For \(4x^2+9y^2-8x+36y+4=0\), find canonical form and the curve's important features. For \(4x^2+y^2=z^2\), describe the sections \(z=c\), \(x=0\), and \(y=0\), paying attention to scale, then identify the surface.

## Solution

For the plane curve, complete the squares:
\[
4(x^2-2x)+9(y^2+4y)+4=0,
\]
\[
4\bigl((x-1)^2-1\bigr)+9\bigl((y+2)^2-4\bigr)+4=0,
\]
so
\[
4(x-1)^2+9(y+2)^2=36,\qquad
\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1.
\]
This is an ellipse centered at \((1,-2)\), with horizontal semiaxis \(3\) and vertical semiaxis \(2\). Its vertices are \((4,-2),(-2,-2),(1,0),(1,-4)\).

For the surface, fixing \(z=c\) gives
\[
4x^2+y^2=c^2.
\]
For \(c\ne0\), this is an ellipse with semiaxes \(|c|/2\) along \(x\) and \(|c|\) along \(y\); at \(c=0\) it is the origin. Setting \(x=0\) gives \(y=\pm z\), while \(y=0\) gives \(z=\pm2x\). The horizontal ellipses widen as \(|z|\) increases, and the vertical sections are pairs of lines with different slopes, so the surface is an elliptic double cone, stretched more along the \(y\)-direction than the \(x\)-direction.