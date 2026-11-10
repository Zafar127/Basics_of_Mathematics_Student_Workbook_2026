# Problem 10 — Complete Function Analysis

## Question

Perform a complete analysis of
$$f(x)=\frac{x}{x^2+1}.$$
Include the domain, symmetry, zeros, limits, monotonicity, extrema, and convexity. Finally, produce a sketch based only on this information.

## Solution

The domain is \(\mathbb R\), and \(f(x)=x/(x^2+1)\) is odd. Its only zero is \(0\), and \(f(x)\to0\) as \(x\to\pm\infty\). The derivative
\[
f'(x)=\frac{(x^2+1)-2x^2}{(x^2+1)^2}
=\frac{1-x^2}{(1+x^2)^2}
\]
is negative on \((-\infty,-1)\), positive on \((-1,1)\), and negative on \((1,\infty)\). Hence there is a minimum \((-1,-1/2)\) and a maximum \((1,1/2)\).

Differentiating \(f'\) by the quotient rule gives
\[
f''(x)=\frac{(-2x)(1+x^2)^2-(1-x^2)\,4x(1+x^2)}{(1+x^2)^4}
=\frac{-2x(1+x^2)-4x(1-x^2)}{(1+x^2)^3}
=\frac{2x(x^2-3)}{(1+x^2)^3}.
\]
Since the denominator is positive, the sign of \(f''\) is the sign of \(x(x^2-3)\): it is negative on \((-\infty,-\sqrt3)\) and \((0,\sqrt3)\), and positive on \((-\sqrt3,0)\) and \((\sqrt3,\infty)\). Inflection points are \((-\sqrt3,-\sqrt3/4),(0,0),(\sqrt3,\sqrt3/4)\).

```text
 y
 ↑         I       • (1,1/2)       I
 |       ╭─────────╯ ╲
 0 ─────•─────────────╲──────→ x   y=0
      ╱ (0,0)           ╲
    •                     ╰──
 (-1,-1/2)
 ```

The marked inflections are \((-\sqrt3,-\sqrt3/4)\), \((0,0)\), and \((\sqrt3,\sqrt3/4)\); the extrema are \((-1,-1/2)\) and \((1,1/2)\). The \(x\)-axis is the horizontal asymptote \(y=0\). The graph is odd and approaches it at both ends.