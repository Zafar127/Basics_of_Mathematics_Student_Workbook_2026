# Exercise 5 — Row Operations and Determinants

Start with
\(A=\begin{pmatrix}1&2&3\\2&1&0\\-1&4&2\end{pmatrix}\).
Use row additions, which preserve the determinant:
\[
R_2\leftarrow R_2-2R_1,\quad
R_3\leftarrow R_3+R_1
\quad\Longrightarrow\quad
\begin{pmatrix}1&2&3\\0&-3&-6\\0&6&5\end{pmatrix}.
\]
Expanding down the first column gives
\[
\det A=(-3)(5)-(-6)(6)=21.
\]
No row swaps or row scalings were used, so the determinant was unchanged.