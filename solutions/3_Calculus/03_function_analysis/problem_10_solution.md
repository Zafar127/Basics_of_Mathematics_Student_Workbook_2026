# Problem 10 — Complete Function Analysis

## Solution

The domain is \(\mathbb R\), and \(f(x)=x/(x^2+1)\) is odd. Its only zero is \(0\), and \(f(x)\to0\) as \(x\to\pm\infty\). The derivative
\[
f'(x)=\frac{1-x^2}{(1+x^2)^2}
\]
is negative on \((-\infty,-1)\), positive on \((-1,1)\), and negative on \((1,\infty)\). Hence there is a minimum \((-1,-1/2)\) and a maximum \((1,1/2)\).

The second derivative is
\[
f''(x)=\frac{2x(x^2-3)}{(1+x^2)^3}.
\]
The graph is concave down on \((-\infty,-\sqrt3)\) and \((0,\sqrt3)\), and convex on \((-\sqrt3,0)\) and \((\sqrt3,\infty)\). Inflection points are \((-\sqrt3,-\sqrt3/4),(0,0),(\sqrt3,\sqrt3/4)\). These symmetries, extrema, inflections, and end behavior determine a consistent sketch.