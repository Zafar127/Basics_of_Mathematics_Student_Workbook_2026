# Problem 12 — A Function with an Absolute Value

## Question

Analyze
$$f(x)=|x^2-4|.$$
First sketch $x^2-4$, then explain the effect of the absolute value. Indicate the points where the derivative does not exist and justify the reason geometrically.

## Solution

\[
f(x)=|x^2-4|=
\begin{cases}
x^2-4,&|x|\ge2,\\
4-x^2,&|x|<2.
\end{cases}
\]
First, \(y=x^2-4\) is an upward-opening parabola with vertex \((0,-4)\) and zeros at \((-2,0)\) and \((2,0)\):

```text
 y=x²-4
 ↑       ╲       ╱
 0 ───────●─────●────→ x
          -2    2
             ╲ ╱
              • (0,-4)
 ```

Taking the absolute value reflects the part below the \(x\)-axis upward:

```text
 y=|x²-4|
 ↑         • (0,4)
 |       ╱   ╲
 0 ────●───────●────→ x
      -2       2
 ```

The points \((-2,0)\) and \((2,0)\) are corners and global minima, not cusps: the one-sided slopes are \(-4\) and \(4\) at each join. The derivative is \(2x\) outside \([-2,2]\) and \(-2x\) inside, so it does not exist at \(x=\pm2\) because those finite one-sided slopes differ.