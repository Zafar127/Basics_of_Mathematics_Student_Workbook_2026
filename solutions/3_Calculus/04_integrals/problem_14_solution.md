# Problem 14 — A Piecewise-Defined Function

## Question

Let
$$f(x)=\begin{cases}x+1,&-1\le x<1,\\2,&1\le x\le3.\end{cases}$$
Sketch the graph, decide where to split the integral, compute
$$\int_{-1}^{3}f(x)\,dx$$
and verify the result geometrically.

## Solution

On \([-1,1)\), the graph is the line \(y=x+1\), rising from \((-1,0)\) to the limiting point \((1,2)\); on \([1,3]\), it is the horizontal segment \(y=2\). Split at \(x=1\):
\[
\int_{-1}^3 f(x)\,dx
=\int_{-1}^1(x+1)\,dx+\int_1^3 2\,dx
=2+4=6.
\]
Geometrically, the first part is a triangle of area \(2\), and the second a \(2\)-by-\(2\) rectangle of area \(4\), totaling \(6\).