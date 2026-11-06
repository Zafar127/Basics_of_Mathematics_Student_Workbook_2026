# Problem 12 — Exhibition Room Optimization

## Solution

Let \(x\) be the room depth perpendicular to the wall (m), and \(y\) the length parallel to the wall (m). The two depth sides cost \(600x\) PLN in total, and the opposite side costs \(500y\) PLN. Using the full budget,
\[
600x+500y=30000,\qquad y=60-1.2x.
\]
Positive dimensions give \(0<x<50\). The area is
\[
A(x)=xy=60x-1.2x^2\quad\text{m}^2.
\]
Its derivative is \(A'(x)=60-2.4x\), which vanishes at \(x=25\). Since \(A''(x)=-2.4<0\) and the area tends to zero at both endpoints, this is the maximum. Then \(y=30\) m and \(A=750\text{ m}^2\). The dimensions mean a \(25\)-m depth and a \(30\)-m side along the wall.

The graph is a downward-opening parabola on \(0<x<50\), with vertex \((25,750)\). A schematic sketch (horizontal axis \(x\) in meters; vertical axis \(A\) in square meters) is:

```text
A
750 |                 *
    |             *       *
    |         *               *
    |     *                       *
  0 +--------------------------------- x
    0                25              50
```

As a numerical check,
\[
A(24)=748.8,\qquad A(25)=750,\qquad A(26)=748.8.
\]
The constraint translating costs and budget into \(y=60-1.2x\) is the modeling step; differentiating and maximizing the resulting quadratic is calculation. The mathematical argument establishes the optimum, while the nearby values and graph only confirm its shape numerically and visually.