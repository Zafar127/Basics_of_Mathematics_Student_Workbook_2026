# Exercise 7 — Choosing a Method Deliberately

1. The coefficient matrix is triangular, so use back-substitution. From \(4y=8\), \(y=2\); then \(2x-y=3\) gives \(x=5/2\).
2. Since the same invertible \(A\) is used for three right-hand sides and \(A^{-1}\) is already known, reuse it: compute each \(x_i=A^{-1}b_i\). The inverse need not be recomputed.
3. For one solution of one \(3\times3\) system, Gaussian elimination on the augmented matrix is appropriate. Computing the entire inverse would find more information than needed; the row reduction can focus directly on the given right-hand side.