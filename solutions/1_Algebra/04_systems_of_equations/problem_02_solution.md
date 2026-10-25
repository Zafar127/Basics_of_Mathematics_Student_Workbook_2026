# Exercise 2 — Gaussian Elimination: One Solution

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