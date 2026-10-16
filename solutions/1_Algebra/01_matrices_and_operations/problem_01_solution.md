# Solutions: Matrices and Basic Operations

---

## Basic Exercises

### Exercise 1. Matrix Size and Entries

#### 1. Problem Statement
Given
$$A=\begin{pmatrix}2&-1&3\\0&4&5\end{pmatrix},\qquad B=\begin{pmatrix}1&0\\-2&3\\4&1\end{pmatrix}.$$
1. State the sizes of matrices $A$ and $B$.
2. Read off the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

#### 2. Theoretical Background and Concepts
* **Matrix Dimensions:** A matrix of size $m \times n$ consists of $m$ horizontal rows and $n$ vertical columns.
* **Index Notation:** The entry $a_{ij}$ denotes the element situated at the intersection of the $i$-th row and the $j$-th column.
* **Row and Column Vectors:** A single row of an $m \times n$ matrix forms a $1 \times n$ row vector, while a single column forms an $m \times 1$ column vector.

#### 3. Detailed Step-by-Step Solution
1. **Determining Matrix Sizes:**
   * Counting the horizontal lines of entries in $A$, there are $2$ rows. Counting the vertical lines, there are $3$ columns. Thus, the size of $A$ is $2 \times 3$.
   * Counting the horizontal lines of entries in $B$, there are $3$ rows. Counting the vertical lines, there are $2$ columns. Thus, the size of $B$ is $3 \times 2$.

2. **Reading Specific Entries:**
   * $a_{12}$: Located in Row 1, Column 2 of matrix $A$, which is $-1$.
   * $a_{23}$: Located in Row 2, Column 3 of matrix $A$, which is $5$.
   * $b_{21}$: Located in Row 2, Column 1 of matrix $B$, which is $-2$.
   * $b_{32}$: Located in Row 3, Column 2 of matrix $B$, which is $1$.

3. **Extracting Vectors:**
   * The second row of $A$ is the $1 \times 3$ row vector:
     $$r_2(A) = \begin{pmatrix} 0 & 4 & 5 \end{pmatrix}$$
   * The first column of $B$ is the $3 \times 1$ column vector:
     $$c_1(B) = \begin{pmatrix} 1 \\ -2 \\ 4 \end{pmatrix}$$

#### 4. Verification and Consistency Checks
* A $2 \times 3$ matrix has $2 \cdot 3 = 6$ total entries, and $A$ indeed contains $6$ numbers. Similarly, $B$ has $3 \cdot 2 = 6$ entries.
* Any row of a $2 \times 3$ matrix must have $3$ components, and any column of a $3 \times 2$ matrix must have $3$ components. Both extracted vectors have length $3$.
* The entry $a_{23} = 5$ is the third element of the extracted second row of $A$ $\begin{pmatrix} 0 & 4 & 5 \end{pmatrix}$, and $b_{21} = -2$ is the second element of the extracted first column of $B$, confirming internal consistency.

---

### Exercise 2. Addition and Scalar Multiplication

#### 1. Problem Statement
For
$$A=\begin{pmatrix}1&2\\-1&3\end{pmatrix},\qquad B=\begin{pmatrix}4&-2\\0&5\end{pmatrix}$$
compute
$$A+B,\qquad A-B,\qquad 3A-2B.$$
Explain why matrix addition is possible only for matrices of the same size.

#### 2. Theoretical Background and Concepts
* **Matrix Addition and Subtraction:** For two matrices $A$ and $B$ of the exact same dimension $m \times n$, their sum/difference $C = A \pm B$ is defined entry-by-entry: $c_{ij} = a_{ij} \pm b_{ij}$ for all $1 \le i \le m$ and $1 \le j \le n$.
* **Scalar Multiplication:** Multiplying a matrix $A$ by a scalar $k \in \mathbb{R}$ scales every entry by $k$: $(kA)_{ij} = k \cdot a_{ij}$.
* **Dimension Requirement:** Addition requires identical dimensions because the operation pairs each entry $a_{ij}$ with a unique corresponding entry $b_{ij}$ in the exact same row $i$ and column $j$. If dimensions differ, at least one matrix has entries with no corresponding partner in the other matrix.

#### 3. Detailed Step-by-Step Solution
1. **Compute $A+B$:**
   $$A+B = \begin{pmatrix} 1+4 & 2+(-2) \\ -1+0 & 3+5 \end{pmatrix} = \begin{pmatrix} 5 & 0 \\ -1 & 8 \end{pmatrix}$$

2. **Compute $A-B$:**
   $$A-B = \begin{pmatrix} 1-4 & 2-(-2) \\ -1-0 & 3-5 \end{pmatrix} = \begin{pmatrix} -3 & 4 \\ -1 & -2 \end{pmatrix}$$

3. **Compute $3A-2B$:**
   First, compute the scalar multiples $3A$ and $2B$:
   $$3A = 3\begin{pmatrix} 1 & 2 \\ -1 & 3 \end{pmatrix} = \begin{pmatrix} 3 & 6 \\ -3 & 9 \end{pmatrix},\qquad 2B = 2\begin{pmatrix} 4 & -2 \\ 0 & 5 \end{pmatrix} = \begin{pmatrix} 8 & -4 \\ 0 & 10 \end{pmatrix}$$
   Next, subtract $2B$ from $3A$:
   $$3A-2B = \begin{pmatrix} 3-8 & 6-(-4) \\ -3-0 & 9-10 \end{pmatrix} = \begin{pmatrix} -5 & 10 \\ -3 & -1 \end{pmatrix}$$

#### 4. Verification and Consistency Checks
We can verify the results using the algebraic identity $3A - 2B = 2(A - B) + A$ and also $(A+B) + (A-B) = 2A$:
* Check 1:
  $$(A+B) + (A-B) = \begin{pmatrix} 5 & 0 \\ -1 & 8 \end{pmatrix} + \begin{pmatrix} -3 & 4 \\ -1 & -2 \end{pmatrix} = \begin{pmatrix} 2 & 4 \\ -2 & 6 \end{pmatrix} = 2\begin{pmatrix} 1 & 2 \\ -1 & 3 \end{pmatrix} = 2A$$
* Check 2:
  $$2(A-B) + A = 2\begin{pmatrix} -3 & 4 \\ -1 & -2 \end{pmatrix} + \begin{pmatrix} 1 & 2 \\ -1 & 3 \end{pmatrix} = \begin{pmatrix} -6+1 & 8+2 \\ -2-1 & -4+3 \end{pmatrix} = \begin{pmatrix} -5 & 10 \\ -3 & -1 \end{pmatrix}$$
Both checks match our calculated matrices.

---

### Exercise 3. When Can Matrices Be Multiplied?

#### 1. Problem Statement
The matrix sizes are
$$A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.$$
For the products
$$AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA$$
determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

#### 2. Theoretical Background and Concepts
* **Dimension Compatibility Condition:** Let $X$ be an $m \times n$ matrix and $Y$ be a $p \times q$ matrix. The matrix product $XY$ is defined if and only if the inner dimensions are equal, i.e., $n = p$ (the number of columns of the left matrix equals the number of rows of the right matrix).
* **Size of the Product:** When $n = p$, the resulting product matrix $XY$ has dimensions given by the outer numbers: $m \times q$.

#### 3. Detailed Step-by-Step Solution
1. **$AB$:** $A$ is $2 \times 3$ and $B$ is $3 \times 4$. The inner dimensions are $3$ and $3$ ($3 = 3$). Thus, **$AB$ is defined**, and its size is $2 \times 4$.
2. **$BA$:** $B$ is $3 \times 4$ and $A$ is $2 \times 3$. The inner dimensions are $4$ and $2$ ($4 \neq 2$). Thus, **$BA$ is not defined**.
3. **$BC$:** $B$ is $3 \times 4$ and $C$ is $4 \times 2$. The inner dimensions are $4$ and $4$ ($4 = 4$). Thus, **$BC$ is defined**, and its size is $3 \times 2$.
4. **$CB$:** $C$ is $4 \times 2$ and $B$ is $3 \times 4$. The inner dimensions are $2$ and $3$ ($2 \neq 3$). Thus, **$CB$ is not defined**.
5. **$AC$:** $A$ is $2 \times 3$ and $C$ is $4 \times 2$. The inner dimensions are $3$ and $4$ ($3 \neq 4$). Thus, **$AC$ is not defined**.
6. **$CA$:** $C$ is $4 \times 2$ and $A$ is $2 \times 3$. The inner dimensions are $2$ and $2$ ($2 = 2$). Thus, **$CA$ is defined**, and its size is $4 \times 3$.
7. **$AD$:** $A$ is $2 \times 3$ and $D$ is $2 \times 2$. The inner dimensions are $3$ and $2$ ($3 \neq 2$). Thus, **$AD$ is not defined**.
8. **$DA$:** $D$ is $2 \times 2$ and $A$ is $2 \times 3$. The inner dimensions are $2$ and $2$ ($2 = 2$). Thus, **$DA$ is defined**, and its size is $2 \times 3$.

| Product | Dimensions $(m \times n)(p \times q)$ | Condition ($n = p$) | Defined? | Result Size ($m \times q$) |
| :--- | :--- | :--- | :--- | :--- |
| **$AB$** | $(2 \times 3)(3 \times 4)$ | $3 = 3$ | Yes | $2 \times 4$ |
| **$BA$** | $(3 \times 4)(2 \times 3)$ | $4 \neq 2$ | No | — |
| **$BC$** | $(3 \times 4)(4 \times 2)$ | $4 = 4$ | Yes | $3 \times 2$ |
| **$CB$** | $(4 \times 2)(3 \times 4)$ | $2 \neq 3$ | No | — |
| **$AC$** | $(2 \times 3)(4 \times 2)$ | $3 \neq 4$ | No | — |
| **$CA$** | $(4 \times 2)(2 \times 3)$ | $2 = 2$ | Yes | $4 \times 3$ |
| **$AD$** | $(2 \times 3)(2 \times 2)$ | $3 \neq 2$ | No | — |
| **$DA$** | $(2 \times 2)(2 \times 3)$ | $2 = 2$ | Yes | $2 \times 3$ |

#### 4. Verification and Consistency Checks
In every defined product ($AB, BC, CA, DA$), each row of the first matrix has the exact same number of elements as each column of the second matrix, ensuring the dot product between any row of the first and any column of the second is well-defined. Furthermore, the number of rows in each valid product matches the first factor, and the number of columns matches the second factor.

---

### Exercise 4. Matrix Multiplication and Noncommutativity

#### 1. Problem Statement
For
$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}2&0\\3&1\end{pmatrix}$$
compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

#### 2. Theoretical Background and Concepts
* **Matrix Multiplication:** Given $A_{m \times n}$ and $B_{n \times p}$, the entry $(AB)_{ij}$ in row $i$ and column $j$ of the product is the dot product of row $i$ of $A$ and column $j$ of $B$:
  $$(AB)_{ij} = \sum_{k=1}^{n} a_{ik}b_{kj}$$
* **Noncommutativity:** An operation $*$ is commutative if $x * y = y * x$ for all $x, y$. Matrix multiplication is **noncommutative**, meaning that even when both $AB$ and $BA$ are defined and have the same size, $AB \neq BA$ in general.

#### 3. Detailed Step-by-Step Solution
1. **Compute $AB$:**
   $$AB = \begin{pmatrix} 1 & 2 \\ 0 & 1 \end{pmatrix}\begin{pmatrix} 2 & 0 \\ 3 & 1 \end{pmatrix} = \begin{pmatrix} 1(2) + 2(3) & 1(0) + 2(1) \\ 0(2) + 1(3) & 0(0) + 1(1) \end{pmatrix} = \begin{pmatrix} 2+6 & 0+2 \\ 0+3 & 0+1 \end{pmatrix} = \begin{pmatrix} 8 & 2 \\ 3 & 1 \end{pmatrix}$$

2. **Compute $BA$:**
   $$BA = \begin{pmatrix} 2 & 0 \\ 3 & 1 \end{pmatrix}\begin{pmatrix} 1 & 2 \\ 0 & 1 \end{pmatrix} = \begin{pmatrix} 2(1) + 0(0) & 2(2) + 0(1) \\ 3(1) + 1(0) & 3(2) + 1(1) \end{pmatrix} = \begin{pmatrix} 2+0 & 4+0 \\ 3+0 & 6+1 \end{pmatrix} = \begin{pmatrix} 2 & 4 \\ 3 & 7 \end{pmatrix}$$

3. **Comparison and Explanation:**
   Comparing the results:
   $$\begin{pmatrix} 8 & 2 \\ 3 & 1 \end{pmatrix} \neq \begin{pmatrix} 2 & 4 \\ 3 & 7 \end{pmatrix} \implies AB \neq BA.$$
   Noncommutativity means the order in which matrices are multiplied changes the outcome. In $AB$, we take rows of $A$ and columns of $B$; in $BA$, we take rows of $B$ and columns of $A$, pairing completely different sets of numbers.

#### 4. Verification and Consistency Checks
We can verify both products using two invariant properties of square matrices: the **trace** ($\operatorname{tr}(AB) = \operatorname{tr}(BA)$, where trace is the sum of diagonal entries) and the **determinant** ($\det(AB) = \det(BA) = \det(A)\det(B)$):
* **Trace check:** $\operatorname{tr}(AB) = 8 + 1 = 9$, and $\operatorname{tr}(BA) = 2 + 7 = 9$. They match.
* **Determinant check:** $\det(A) = 1(1) - 2(0) = 1$ and $\det(B) = 2(1) - 0(3) = 2$, so $\det(A)\det(B) = 2$.
  * $\det(AB) = 8(1) - 2(3) = 8 - 6 = 2$.
  * $\det(BA) = 2(7) - 4(3) = 14 - 12 = 2$.
Both checks confirm our calculations are accurate.

---

### Exercise 5. Matrix Times Vector

#### 1. Problem Statement
Let
$$A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},\qquad x=\begin{pmatrix}4\\2\end{pmatrix}.$$
Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

#### 2. Theoretical Background and Concepts
* **Row-by-Column Rule:** Multiplying an $m \times n$ matrix $A$ by an $n \times 1$ column vector $x$ yields an $m \times 1$ column vector whose $i$-th entry is the dot product of row $i$ of $A$ with $x$.
* **Column Picture (Linear Combination of Columns):** If $A = \begin{pmatrix} a_1 & a_2 & \cdots & a_n \end{pmatrix}$ has columns $a_j$ and $x = \begin{pmatrix} x_1 \\ \vdots \\ x_n \end{pmatrix}$, then:
  $$Ax = x_1 a_1 + x_2 a_2 + \cdots + x_n a_n$$

#### 3. Detailed Step-by-Step Solution
1. **Standard Computation of $Ax$:**
   $$Ax = \begin{pmatrix} 2 & -1 \\ 1 & 3 \end{pmatrix}\begin{pmatrix} 4 \\ 2 \end{pmatrix} = \begin{pmatrix} 2(4) + (-1)(2) \\ 1(4) + 3(2) \end{pmatrix} = \begin{pmatrix} 8 - 2 \\ 4 + 6 \end{pmatrix} = \begin{pmatrix} 6 \\ 10 \end{pmatrix}$$

2. **Expressing $Ax$ as a Linear Combination of the Columns of $A$:**
   The columns of $A$ are $a_1 = \begin{pmatrix} 2 \\ 1 \end{pmatrix}$ and $a_2 = \begin{pmatrix} -1 \\ 3 \end{pmatrix}$, and the entries of $x$ are $x_1 = 4$ and $x_2 = 2$. Forming the linear combination:
   $$Ax = 4\begin{pmatrix} 2 \\ 1 \end{pmatrix} + 2\begin{pmatrix} -1 \\ 3 \end{pmatrix} = \begin{pmatrix} 8 \\ 4 \end{pmatrix} + \begin{pmatrix} -2 \\ 6 \end{pmatrix} = \begin{pmatrix} 6 \\ 10 \end{pmatrix}$$

#### 4. Verification and Consistency Checks
Both the row-by-column dot product method and the linear combination of columns method independently yield the exact same $2 \times 1$ vector $\begin{pmatrix} 6 \\ 10 \end{pmatrix}$, confirming the calculation and demonstrating the equivalence of the two perspectives.

---

### Exercise 6. Transpose

#### 1. Problem Statement
For
$$A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix},\qquad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}$$
compute $A^T$, $B^T$, and $AB$. Then verify in this example that
$$(AB)^T=B^TA^T.$$

#### 2. Theoretical Background and Concepts
* **Matrix Transpose:** The transpose of an $m \times n$ matrix $M$, denoted $M^T$, is the $n \times m$ matrix obtained by interchanging its rows and columns: $(M^T)_{ij} = M_{ji}$.
* **Transpose of a Product:** For matrices $A$ and $B$ of compatible sizes, $(AB)^T = B^T A^T$. The order reverses because the $(i,j)$ entry of $(AB)^T$ is the $(j,i)$ entry of $AB$, which is the dot product of row $j$ of $A$ (column $j$ of $A^T$) and column $i$ of $B$ (row $i$ of $B^T$).

#### 3. Detailed Step-by-Step Solution
1. **Compute $A^T$ and $B^T$:**
   * Since $A$ is $2 \times 3$, $A^T$ is $3 \times 2$:
     $$A^T = \begin{pmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{pmatrix}$$
   * Since $B$ is $3 \times 2$, $B^T$ is $2 \times 3$:
     $$B^T = \begin{pmatrix} 1 & 2 & -1 \\ 0 & 1 & 3 \end{pmatrix}$$

2. **Compute $AB$:**
   $$AB = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}\begin{pmatrix} 1 & 0 \\ 2 & 1 \\ -1 & 3 \end{pmatrix} = \begin{pmatrix} 1(1)+2(2)+3(-1) & 1(0)+2(1)+3(3) \\ 4(1)+5(2)+6(-1) & 4(0)+5(1)+6(3) \end{pmatrix}$$
   $$AB = \begin{pmatrix} 1+4-3 & 0+2+9 \\ 4+10-6 & 0+5+18 \end{pmatrix} = \begin{pmatrix} 2 & 11 \\ 8 & 23 \end{pmatrix}$$

3. **Compute $(AB)^T$ and $B^T A^T$:**
   * Transposing $AB$:
     $$(AB)^T = \begin{pmatrix} 2 & 8 \\ 11 & 23 \end{pmatrix}$$
   * Multiplying $B^T$ by $A^T$:
     $$B^T A^T = \begin{pmatrix} 1 & 2 & -1 \\ 0 & 1 & 3 \end{pmatrix}\begin{pmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{pmatrix} = \begin{pmatrix} 1(1)+2(2)+(-1)(3) & 1(4)+2(5)+(-1)(6) \\ 0(1)+1(2)+3(3) & 0(4)+1(5)+3(6) \end{pmatrix}$$
     $$B^T A^T = \begin{pmatrix} 1+4-3 & 4+10-6 \\ 0+2+9 & 0+5+18 \end{pmatrix} = \begin{pmatrix} 2 & 8 \\ 11 & 23 \end{pmatrix}$$

#### 4. Verification and Consistency Checks
Comparing the two matrices computed in Step 3:
$$(AB)^T = \begin{pmatrix} 2 & 8 \\ 11 & 23 \end{pmatrix} = B^T A^T.$$
Additionally, note that the product $A^T B^T$ would be $(3 \times 2)(2 \times 3) = 3 \times 3$, which doesn't even match the $2 \times 2$ size of $(AB)^T$, illustrating why the reversal of order in $B^T A^T$ is necessary.

---

### Exercise 7. Identity Matrix, Zero Matrix, and Powers

#### 1. Problem Statement
For
$$A=\begin{pmatrix}2&1\\0&2
