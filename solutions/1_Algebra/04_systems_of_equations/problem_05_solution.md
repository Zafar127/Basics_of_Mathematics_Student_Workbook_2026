# Exercise 5 — Row Echelon Form and Number of Solutions

## Question

For the augmented matrix
$$\left[\begin{array}{ccc|c}1&2&-1&3\\0&1&2&1\\0&0&0&0\end{array}\right]$$
determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

## Solution

The rows represent
\[
x+2y-z=3,\qquad y+2z=1.
\]
There is no pivot in the \(z\)-column, so \(z\) is free; there are infinitely many solutions. Set \(z=t\). Then \(y=1-2t\), and the first equation gives \(x=1+5t\). Thus
\[
(x,y,z)=(1+5t,\,1-2t,\,t),\qquad t\in\mathbb R.
\]
There are two pivot variables and three unknowns, leaving one free variable.
