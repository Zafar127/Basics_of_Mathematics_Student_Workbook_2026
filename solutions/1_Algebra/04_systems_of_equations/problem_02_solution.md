# Exercise 2 — Gaussian Elimination: One Solution

## Question

Solve using Gaussian elimination:
$$\begin{cases}x+y+z=6,\\2x-y+z=3,\\x+2y-z=2.\end{cases}$$
After solving, substitute the result into all equations and check consistency.

## Solution

The elementary row operations preserve the solution set and are chosen to eliminate variables. The first two updates eliminate \(x\) from rows 2 and 3. Then \(R_2\leftarrow R_2+3R_3\) eliminates \(y\), allowing back-substitution to start with \(z\).

\[
\left[\begin{array}{ccc|c}
1&1&1&6\\2&-1&1&3\\1&2&-1&2
\end{array}\right]
\xrightarrow{R_2-2R_1,\ R_3-R_1}
\left[\begin{array}{ccc|c}
1&1&1&6\\0&-3&-1&-9\\0&1&-2&-4
\end{array}\right].
\]
Using \(R_2+3R_3\) gives \( -7z=-21\), hence \(z=3\). Then \(y-2z=-4\) gives \(y=2\), and \(x+y+z=6\) gives \(x=1\).

Check: \(1+2+3=6\), \(2-2+3=3\), and \(1+4-3=2\). Thus \((x,y,z)=(1,2,3)\).
