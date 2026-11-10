# Problem 1 — A Cubic Polynomial

## Question

Analyze the monotonicity and extrema of
$$f(x)=x^3-3x^2+2.$$
Sketch the graph based on the results and mark the critical points.

## Solution

\[
f'(x)=3x^2-6x=3x(x-2).
\]
The derivative has signs \(+,-,+\) on \((-\infty,0)\), \((0,2)\), and \((2,\infty)\), respectively. Therefore the function increases, decreases, then increases: the sign changes \(+\to-\) at \(0\) give the local maximum \((0,2)\), and \(-\to+\) at \(2\) give the local minimum \((2,-2)\). The cubic tends to \(-\infty\) as \(x\to-\infty\) and \(+\infty\) as \(x\to+\infty\).

```text
 y
 ↑             • (0,2)
 |          ╭──╯ ╲
 0 ────────╯──────╲──────────→ x
 |                  ╲
 |                   • (2,-2) ╭
 |                              ╰──
 ```