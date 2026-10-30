# Exercise 3 — Inconsistent System

## Question

Solve or show that the system is inconsistent:
$$\begin{cases}x+2y=3,\\2x+4y=7.\end{cases}$$
Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

## Solution

\[
\left[\begin{array}{cc|c}1&2&3\\2&4&7\end{array}\right]
\xrightarrow{R_2-2R_1}
\left[\begin{array}{cc|c}1&2&3\\0&0&1\end{array}\right].
\]
The second row represents \(0=1\), a contradiction. Equivalently, the left side of the second original equation is twice the first, but its right side is \(7\ne2\cdot3\). There is no solution.
