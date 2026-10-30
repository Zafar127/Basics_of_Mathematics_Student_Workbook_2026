# Exercise 8 — Two Systems with the Same Coefficient Matrix

## Question

Solve by elimination the two systems
$$\begin{cases}2x+y=5,\\x-y=1,\end{cases}$$
$$\begin{cases}2x+y=1,\\x-y=4.\end{cases}$$
Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

For each system, apply the same coefficient-row operation \(R_1\leftarrow R_1-2R_2\). The first system starts with
\[
\left[\begin{array}{cc|c}2&1&5\\1&-1&1\end{array}\right]
\xrightarrow{R_1\leftarrow R_1-2R_2}
\left[\begin{array}{cc|c}0&3&3\\1&-1&1\end{array}\right],
\]
which produces the equation \(3y=3\). The second starts with
\[
\left[\begin{array}{cc|c}2&1&1\\1&-1&4\end{array}\right]
\xrightarrow{R_1\leftarrow R_1-2R_2}
\left[\begin{array}{cc|c}0&3&-7\\1&-1&4\end{array}\right],
\]
which produces \(3y=-7\).

First system: \(3y=3\), so \(y=1\), then \(x=2\).

Second system: \(3y=-7\), so \(y=-7/3\), then \(x=y+4=5/3\).

The left-side elimination and resulting coefficient \(3y\) are identical because both systems have the same coefficient matrix. Only the right-hand side changes.
