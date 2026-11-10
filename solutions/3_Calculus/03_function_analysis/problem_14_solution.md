# Problem 14 — Reconstructing Information from the Derivative

## Question

It is known that
$$f'(x)=(x-1)(x+2).$$
Determine the monotonicity and the locations of the extrema, and sketch a possible qualitative shape of the function. Then, for
$$g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x$$
verify that $g'(x)=(x-1)(x+2)$, and compare the specific graph with the earlier qualitative sketch.

## Solution

\[
f'(x)=(x-1)(x+2).
\]
Its sign is positive on \((-\infty,-2)\), negative on \((-2,1)\), and positive on \((1,\infty)\). Thus \(f\) increases, then decreases, then increases: it has a local maximum at \(-2\) and a local minimum at \(1\). Any vertical translate of an antiderivative has this qualitative shape.

```text
 qualitative shape of f
 y
 ↑       local maximum
 |          •
 |        ╱   ╲
 |      ╱       ╲
 |    ╱           •
 |  ╱         local minimum ╲
 +----------------------------→ x
           -2         1
 ```

For \(g(x)=x^3/3+x^2/2-2x\),
\[
g'(x)=x^2+x-2=(x-1)(x+2).
\]
Its corresponding extrema are \(g(-2)=10/3\) and \(g(1)=-7/6\). The derivative determines monotonicity and the horizontal locations of the extrema, while the integration constant (here zero) sets their vertical positions.

```text
 g(x)
 ↑         • (-2,10/3)
 |       ╱   ╲
 |     ╱       ╲
 0 ──╱──────────╲────────────→ x
 |                 • (1,-7/6)
 |                   ╲
 ```