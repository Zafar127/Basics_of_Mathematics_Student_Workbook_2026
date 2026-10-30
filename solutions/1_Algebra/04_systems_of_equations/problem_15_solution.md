# Exercise 15 — Classifying Three Systems

## Question

For each of the following systems, perform only as much elimination as necessary to recognize its type:

1. $\begin{cases}x+y=2,\\x-y=0,\end{cases}$
2. $\begin{cases}x+y=2,\\2x+2y=4,\end{cases}$
3. $\begin{cases}x+y=2,\\2x+2y=5.\end{cases}$

For each, justify the classification: one solution, infinitely many solutions, or no solution.

## Solution

1. Adding and subtracting the equations gives \(2x=2,\ 2y=2\), so \(x=y=1\): exactly one solution.
2. Row reduction gives
\[
\left[\begin{array}{cc|c}1&1&2\\2&2&4\end{array}\right]
\xrightarrow{R_2\leftarrow R_2-2R_1}
\left[\begin{array}{cc|c}1&1&2\\0&0&0\end{array}\right].
\]
Thus \(0=0\) and only one equation remains for two unknowns, so one variable is free. Letting \(y=s\) gives infinitely many solutions \((x,y)=(2-s,s)\).
3. Subtract twice the first equation from the second to obtain \(0=1\): no solution.
