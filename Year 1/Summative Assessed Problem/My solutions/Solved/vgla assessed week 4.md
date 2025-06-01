[[Semester_2_Sheet_2_qs.pdf]]

1. Let $n ≥ 2$ be an integer. Consider the permutation $σ : \{1, 2, . . . , n\} → \{1, 2, . . . , n\}$ defined by
$$
\sigma(i)=\left\{ \begin{matrix}
i+1 & \text{if }i<n, \\
1 & \text{if } i=n.
\end{matrix} \right. 
$$
(a) Write down $σ$ in the sequence notation, $σ = [σ(1), σ(2), . . . , σ(n)]$
$$
\sigma:\{ 2,3,4\dots n-1,n,1 \}
$$
b) Find $N (σ)$, the number of inversions in $σ$.
$$
N(\sigma)=n-1
$$
(c) Find $σ^{-1}$, the inverse of $σ$
$$
\sigma(i)=\left\{ \begin{matrix}
i-1 & \text{if }i<n, \\
n & \text{if } i=1.
\end{matrix} \right. 
$$
2. Find the determinants of the following matrices. You may use any general results about determinants, as long as you clearly state them. Giving the correct answer without showing a correct justification will get you no marks.

For all of the below, we use that the determinant of a triangular matrix is the product of the diagonals.
$$\det(A)=\prod^{n}_{i=1}a_{ii}$$
$A$ is a (upper) triangular matrix as below the $a_{ii}$ values they are all $0$:
$$
\det A=1\cdot 1\cdot 1\cdot 1=1
$$
We will use EROs to assume $B$ into the form of an triangular matrix, and the fact that adding or subtracting to another row or column with an existing row or column does not change the determinant. We subtract row $2$ by $1$, $4$ times.
$$
\det B=\det\begin{pmatrix}
1 & 2 & 3 & 4 \\
0 & -7 & -10 & -13 \\
0 & 0 & 1 & 2 \\
0 & 0 & 0 & 1
\end{pmatrix}=1\cdot-7 \cdot 1 \cdot 1=-7
$$
For $C$ we will use the ERO of swapping rows, or columns and the resulting effect that causes the determinant to become negative of the original determinant. It is then given, by swapping row 1 with 2:

$$
\det C=-\det \begin{pmatrix}
4 & 1 & 2 & 3 \\
0 & 2 & 3 & 4 \\
0 & 0 & 1 & 2 \\
0 & 0 & 0 & 1
\end{pmatrix}=-8
$$
For $D$ we will use both swapping and adding, and subtracting existing rows to the form of a triangular matrix. We swap row 1 and 2, and then the new row 2 and 3. Then we add the new row 3 to row 4. As we have swapped twice the $-1^{2}$ which cancels out on the determinant
$$
\det D=\det \begin{pmatrix}
4 & 1 & 2 & 3 \\
0 & 2 & 3 & 4 \\
0 & 0 & 1 & 2 \\
0 & 0 & 0 & 1
\end{pmatrix}=24
$$
For $E$ we will the following:
- $\det(AB)=\det A\det B$
- Applying a scalar $\lambda$ on a matrix is the same as multiplying every row or column by $\lambda$ which's effect is to increase the determinant by $\lambda$ for each row/column multiplied so the overall effect increases the determinant by $\lambda^{n}$ where $n$ is the size of the $n\times n$ square matrix. 
- $\det A=\det A^{T}$
- The inverse is given by $\det (D\cdot D^{-1})=\det D\cdot \det D^{-1}=\det I=1\implies \det D^{-1}=\frac{1}{\det D}$
$$
\det E=\det\left( \frac{1}{2}A^{T}\cdot B\cdot C^{2}\cdot D^{-1} \right)=\det \frac{1}{2}A^{T} \cdot\det B\cdot \det C^{2}\cdot\det D^{-1}
$$
$$
=\frac{1}{2}^{4}\cdot\det A\cdot\det B\cdot \det C\cdot \det C\cdot \frac{1}{\det D}=\frac{1}{16}\cdot 1\cdot-7\cdot-8^{2}\cdot \frac{1}{24}=-\frac{7}{6}
$$

3. Let $n ∈ \mathbb{N}$ and $a_{i} ∈ \mathbb{R}$ for $i = 1, 2, \dots, n$. Find the determinant of the $n × n$ matrix,
$$
A=\begin{pmatrix}
0 & 0 & \dots & 0 & a_{1} \\
0 & 0 & \dots & a_{2} & 0 \\
\vdots & \vdots & \ddots & \vdots & \vdots \\
0 & a_{n-1} & \dots & 0 & 0 \\
a_{n} & 0 & \dots & 0 & 0
\end{pmatrix}
$$
where the $i^{th}$ row has $a_{i}$ in the $(n-i+1)^{th}$ column and $0$ in every column.

Let $B$ be some  matrix and $C$ be $B$ with a swap, and use use the result that the determinant of a matrix that has had a row or column swapped, which is given by:
$$
\det B=-\det C
$$
Let $k\in \mathbb{N}$ be the number of swaps that $C$ has undergone. It then follows that for $k$ swaps:
$$
\det B=(-1)^{k}\det C
$$
If $n=2m$ (even), then it takes $m$ swaps of columns or rows to obtain a triangular matrix, if $m$ is even ($n$ is a multiple of 4), then the negative for each switch cancels out and the determinant is simply:
$$
\det A=\prod^{n}_{i=1}a_{i(n-i+1)}
$$
If $m$ is odd otherwise:
$$
\det A=-\prod^{n}_{i=1}a_{i(n-i+1)}
$$
Now lets consider $n=2m+1$ (odd),. there are then again $m$ swaps needed to obtain a triangular matrix as the middle row/column $(m+1)$ does not need to be changed. Following by the same reasoning as the even case $(n=2m)$ we see if $m$ is even then
$$
\det A=\prod^{n}_{i=1}a_{i(n-i+1)}

$$
Else odd:
$$
\det A=-\prod^{n}_{i=1}a_{i(n-i+1)}

$$
We may then generalise this as:
$$
\det A=(-1)^{\left\lfloor {\frac{n}{2}} \right\rfloor}\prod^{n}_{i=1}a_{i(n-i+1)}
$$
4. For every integer $n\geq 2$, let 
$$
A_{n}=\begin{pmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{pmatrix}
$$
be the $n × n$ matrix where every element on the main diagonal, every element just above the main diagonal, and every element just below the main diagonal, is $1$, while every other element is $0$. An equivalent description of $A_{n}$ is that the $1^{st}$ row has $1$ in the first and second columns, the $n^{th}$ row has $1$ in the $(n − 1)^{th}$ and $n^{th}$ columns, and the $i^{th}$ row for $i = 2, 3, . . . , n − 1$ has $1$ in the $(i − 1)^{th}$, $i^{th}$ and $(i + 1)^{th}$ columns, while every other element is $0$.
.
(a) Write down $A_{2}$ and find $\det A_{2}$.
$$
A_{2}=\begin{pmatrix}
1 & 1 \\
1 & 1
\end{pmatrix}\qquad \det A=0
$$
(b) Write down $A_{3}$ and find $\det A_{3}$.
$$
A_{3}=\begin{pmatrix}
1 & 1 & 0 \\
1 & 1 & 1 \\
0 & 1 & 1
\end{pmatrix}\qquad \det A_{3}=\begin{vmatrix}
1 & 1 \\
1 & 1
\end{vmatrix}-\begin{vmatrix}
1 & 1 \\
0 & 1
\end{vmatrix}=-1$$
(c) For $n\geq 4$, show that
$$
\det(A_{n})=\det(A_{n-1})-\det(A_{n-2})
$$
and hence, show that $$\det A_{n+1}=-\det A_{n-2}$$
Prototyping:
$$
\det A_{4}=\det \begin{pmatrix}
1 & 1 & 0 & 0 \\
1 & 1 & 1 & 0 \\
0 & 1 & 1 & 1 \\
0 & 0 & 1 & 1
\end{pmatrix}=1 \begin{vmatrix}
1 & 1 & 0 \\
1 & 1 & 1 \\
0 & 1 & 1
\end{vmatrix} -1\begin{vmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
0 & 1 & 1
\end{vmatrix}
$$
$$
=\begin{vmatrix}
1 & 1 & 0 \\
1 & 1 & 1 \\
0 & 1 & 1
\end{vmatrix} -1\begin{vmatrix}
1 & 1 \\
1 & 1
\end{vmatrix}=\det A_{3}-\det A_{2}=-1
$$
Now let us prove it is subsequently true $\forall k>4$ by induction by finding the determinant using cofactors.
$$
\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k }=\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k-1 }
$$

$$
\,-\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k - 1}
$$
We use cofactors again to find the determinant of the 2nd matrix and realise that it has a column of $0$ so its determinant must be $0$
$$
=\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k - 1}-\left( \overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k -2 } - \right. 
$$
$$
\left. - \overbrace{ \begin{vmatrix}
0 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k-2 } \right) 
$$
$$
=\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k -1}-\overbrace{ \begin{vmatrix}
1 & 1 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
1 & 1 & 1 & 0 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 1 & 1 & 1 & 0 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 1 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
0 & 0 & 0 & 1 & 1 & \dots & 0 & 0 & 0 & 0 & 0 \\
\vdots & \vdots & \vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots & \vdots & \vdots \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 0 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 1 & 1 & 1 & 0 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 1 & 1 & 1 & 0 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 1 & 1 & 1 \\
0 & 0 & 0 & 0 & 0 & \dots & 0 & 0 & 0 & 1 & 1 
\end{vmatrix} }^{ k -2 } 
$$
$$
\therefore \det A_{k} =\det A_{k-1} -\det A_{k-2}
$$
Hence 
$$
\det A_{n+1}=\det A_{n}-\det A_{n-1}=(\cancel{ \det A_{n-1} }-\det A_{n-2})-\cancel{ \det A_{n-1} }=-\det A_{n-2}
$$
(d) Find $\det A_{n}$ when
- (i) $n = 3k − 1$ for some integer $k ≥ 1$;

For $k=1$
$$
A_{2}=0\therefore \forall k\geq 1,A_{3k-1}=0 \because \det A_{n+1}=-\det A_{n-2}
$$
- (ii) $n = 3k$ for some integer $k ≥ 1$;
For $k=1$
$$
A_{3}=-1\therefore \forall k\geq 1,A_{3k}=\pm1 \because \det A_{n+1}=-\det A_{n-2}
$$
For even $k$:
$$
\det A_{3k}=1
$$
For odd $k$:
$$
\det A_{3k}=-1
$$
- (iii) $n = 3k + 1$ for some integer $k ≥ 1$;

For $k=1$
$$
A_{4}=-1\therefore \forall k\geq 1,A_{3k+1}=\pm 1 \because \det A_{n+1}=-\det A_{n-2}
$$
For even $k$:
$$
\det A_{3k+1}=1
$$
For odd $k$:
$$
\det A_{3k+1}=-1
$$
