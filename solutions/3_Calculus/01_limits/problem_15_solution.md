# Exercise 15 — Observation Versus Proof

## Question

Choose one sequence and one function from this set. For the sequence, compute several values for increasingly large $n$. For the function, prepare a table of values with arguments approaching the limit point from the left and right. Sketch the behavior of both objects.

Compare the observation with the analytical result and explain why a finite number of calculations or a sketch does not constitute a proof that the limit exists.

## Solution

Choose the sequence \(a_n=(2/3)^n\), whose limit is \(0\), and the function from Exercise 7, \(f(x)=(x^2-4x+3)/(x-3)\), as \(x\to3\). For \(n=1,2,3,4,5\), the sequence values are \(0.667,\ 0.444,\ 0.296,\ 0.198,\ 0.132\), visibly approaching zero.

For \(x\ne3\), \(f(x)=x-1\). Values from the left at \(2.9,2.99,2.999\) are \(1.9,1.99,1.999\); from the right at \(3.1,3.01,3.001\) they are \(2.1,2.01,2.001\). Both sides approach \(2\). A sketch would show the sequence terms decreasing toward zero and the line \(y=x-1\) with a hole at \((3,2)\).

```text
 a_n
  ^
  |  •
  |     •
  |        •
  |           •  • ...
0 +--------------------→ n
    1  2  3  4  5
```

```text
 y
 3 |                    /
 2 |                 ○ /   hole at (3,2)
 1 |              /
 0 +------------/----------→ x
                1     3
```

The calculations and sketches illustrate the limits but only examine finitely many values. Proof requires an argument covering all sufficiently large \(n\), or all \(x\) sufficiently close to \(3\).