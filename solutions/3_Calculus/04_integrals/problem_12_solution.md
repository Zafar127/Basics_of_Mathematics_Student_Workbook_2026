# Problem 12 — Symmetry, Sign, and Absolute Value

## Question

Compare
$$\int_{-2}^{2}x\,dx$$
and
$$\int_{-2}^{2}|x|\,dx.$$
Before calculating, predict the results from symmetry and a sketch, then carry out the calculation and explain the difference.

## Solution

For \(y=x\), the region on \([-2,0]\) is below the axis and the region on \([0,2]\) is above it; the two equal triangles should cancel in the signed integral. For \(y=|x|\), both triangular regions are above the axis and should add.

```text
 y=x                              y=|x|
 2 |          /                   2 | \       /
 1 |       /                      1 |  \     /
 0 +----/------→ x                0 +---\---/--→ x
 -1| ##/                              ##   ##
 -2|#/                                shaded areas
    -2  0  2                           -2 0 2
    ## = region between curve and axis
```

The odd function \(x\) has zero integral over the symmetric interval:
\[
\int_{-2}^2x\,dx=0.
\]
The function \(|x|\) is even and nonnegative; its two triangular areas each equal \(2\), so
\[
\int_{-2}^2|x|\,dx=2\int_0^2x\,dx=4.
\]
The first integral cancels equal positive and negative signed areas; the second adds their magnitudes.