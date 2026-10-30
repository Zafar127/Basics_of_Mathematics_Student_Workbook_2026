# Exercise 7 — Choosing a Method Deliberately

## Question

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix
   $$\begin{cases}2x-y=3,\\4y=8;\end{cases}$$
2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

## Solution

1. The coefficient matrix is triangular, so use back-substitution. From \(4y=8\), \(y=2\); then \(2x-y=3\) gives \(x=5/2\).
2. Since the same invertible \(A\) is used for three right-hand sides and \(A^{-1}\) is already known, reuse it: compute each \(x_i=A^{-1}b_i\). The inverse need not be recomputed.
3. For one solution of one \(3\times3\) system, Gaussian elimination on the augmented matrix is appropriate. Computing the entire inverse would find more information than needed; the row reduction can focus directly on the given right-hand side.
