[[Semester_2_Sheet_4_qs.pdf]]

1. Consider the vector space $\mathbb{R}^{3}$ and $$u_{1}=(2,-1,0)\in \mathbb{R}^{3},\quad u_{2}=(0,-1,2)\in \mathbb{R}^{3},$$$$U=\{ (x_{1},x_{2},x_{3})\in \mathbb{R}^{3}: 3x_{1}+2x_{2}+x_{3}=0 \}\leq \mathbb{R}^{3}$$
- (a) Show that $\text{span}\{ u_{1},u_{2} \}$ is the plane through the origin with normal vector $(1,2,1)$
$$
\lambda_{1},\lambda_{2}\in \mathbb{R}
$$
$$
\text{span}\{ \lambda_{1}(2,-1,0) +\lambda_{2}(0,-1,2): x+y+z\}=\text{span}\{ 2\lambda_{1},-\lambda_{1}-\lambda_{2},2\lambda_{2}: x+y+z \}
$$
$$
x=2\lambda_{1}\iff \lambda_{1}=\frac{x}{2}\quad z=2\lambda_{2}\iff\lambda_{2}=\frac{z}{2}\quad -\lambda_{1}-\lambda_{2}=y\implies \frac{x}{2}+y+\frac{z}{2}=x+2y+z=0
$$
$x+2y+z=0$ gives the plane spanned by $\text{span}\{ u_{1},u_{2} \}$, and the normal vector is given by the equation as $(1,2,1)$.

- (b) Find a spanning set for $U$
$$
x_{1}=(2,-1,0)\qquad x_{2}=(0,-1,2)\qquad x_{3}=(a,b,c)
$$
$$
3x_{1}+2x_{2}+x_{3}=(6+a,-5+b,4+c)=0 \iff x_{3}=(-6,5,-4)
$$
2. Let $\mathcal{M_{22}}(\mathbb{R})$ be the vector space of $2\times 2$ real matrices, with the standard matrix addition and scalar multiplication. Let $$\underline{\underline{A}}=\begin{pmatrix}
1 & 0 \\
1 & 1
\end{pmatrix}\qquad \underline{\underline{B}}=\begin{pmatrix}
1 & 1 \\
0 & 1
\end{pmatrix}\qquad \underline{\underline{C}}=\begin{pmatrix}
1 & 1 \\
1 & 0
\end{pmatrix}.$$ Show that $\{ \underline{\underline{A}},\underline{\underline{B}},\underline{\underline{C}} \}$ is  linearly independent set
$$
\lambda_{1},\lambda_{2},\lambda_{3}\in \mathbb{R}
$$
The $\{ \underline{\underline{A}},\underline{\underline{B}},\underline{\underline{C}} \}$ is linearly independent if the following is satisfied:
$$
\lambda_{1}\underline{\underline{A}}+\lambda_{2}\underline{\underline{B}}+\lambda_{3}\underline{\underline{C}}=0\iff \lambda_{1}=\lambda_{2}=\lambda_{3} =0
$$
$$
\lambda_{1}\underline{\underline{A}}+\lambda_{2}\underline{\underline{B}}+\lambda_{3}\underline{\underline{C}}=\begin{pmatrix}
\lambda_{1}+\lambda_{2}+\lambda_{3} & \lambda_{2}+\lambda_{3} \\
\lambda_{1}+\lambda_{3} & \lambda_{1}+\lambda_{2}
\end{pmatrix}=\begin{pmatrix}
0 & 0 \\
0 & 0
\end{pmatrix}
$$
$$
\begin{array}{}
\lambda_{1}+\lambda_{2}+\lambda_{3}&=&0 \\
\lambda_{2}+\lambda_{3}&=&0
\end{array}\implies\lambda_{1}=0\qquad \lambda_{1}+\lambda_{2}=0 \iff\lambda_{2}=0\qquad \lambda_{1}+\lambda_{3}=0\iff \lambda_{3}=0
$$
We have shown the only solution is $\lambda_{1}=\lambda_{2}=\lambda_{3}=0$ and this satisfise the definition of linear independence of the set $\{ \underline{\underline{A}},\underline{\underline{B}},\underline{\underline{C}} \}$.

3. Let $\mathcal{P}_{2}(\mathbb{R})$ be the vector space of real polynomials of order at most $2$:$$\mathcal{P}_{2}(\mathbb{R})=\{ a_{2}x^{2}+a_{1}x+a_{0}:a_{0},a_{2},a_{3}\in \mathbb{R} \},$$with vector addition defined by $$(a_{2}x^{2}+a_{1}x+a_{0})+(b_{2}x^{2}+b_{1}x+b_{0})=(a_{2}+b_{2})x^{2}+(a_{1}+b_{1})x+(a_{0}+b_{0}),$$and scalar multiplication defined for all $\lambda \in \mathbb{R}$ by $$\lambda(a_{2}x^{2}+a_{1}x+a_{0})=\lambda a_{2}x^{2}+\lambda a_{1}x+\lambda a_{0}.$$
- (a) Show that $$U=\{ a_{2}x^{2}+a_{1}x+a_{0}:a_{0},a_{1},a_{2}\in \mathbb{R},a_{0}+a_{1}+a_{2}=0 \}$$is a subspace of $\mathcal{P}_{2}(\mathbb{R})$.

To demonstrate whether this subset $U$ of vectors is a vector space it is enough to show that it satisfies closure upon $\oplus$ (vector addition) and $\odot$ (vector scalar multiplication) on $U$, where $U$ is a subset of $\mathcal{P}_{2})\mathbb{R}$.

$$
(a_{2}x^{2}+a_{1}x+a_{0})+(b_{2}x^{2}+b_{1}x+b_{0})=(a_{2}+b_{2})x^{2}+(a_{1}+b_{1})x+(a_{0}+b_{0})
$$
$$
\implies(a_{0}+b_{0})+(a_{1}+b_{1})+(a_{2}+b_{2})=\underbrace{ (a_{0}+a_{1}+a_{2}) }_{ 0 }+\underbrace{ (b_{0}+b_{1}+b_{2}) }_{ 0 }=0
$$
We have shown that there is closure under vector addition.
$$
\lambda(a_{2}x^{2}+a_{1}x+a_{0})=\lambda a_{2}x^{2}+\lambda a_{1}x+\lambda a_{0}
$$
$$
\implies\lambda a_{2}+\lambda a_{1}+\lambda a_{0}=\lambda\underbrace{ (a_{0}+a_{1}+a_{2}) }_{ 0 }=0
$$
We have shown that there is closure under scalar multiplication. Hence we have proved that $U$ is a subspace.

- (b) Show that $$U=\text{span}\{ x^{2}-1,x-1 \}$$Hence, show that $\dim(U)=2$.

We may show the set of vectors are linearly independent if the following is satisfied:
$$
\lambda_{1}(x^{2}-1)+\lambda_{2}(x-1)=0 \iff \lambda_{1}=\lambda_{2}=0
$$
$$
\lambda_{1}x^{2}+\lambda_{2}x+(-\lambda_{1}-\lambda_{2})=0
$$
Comparing coefficients:
$$
\lambda_{1}x^{2}=0\iff\lambda_{1}=0\qquad (-\lambda_{1}-\lambda_{2})=0 \iff \lambda_{2}=0 \therefore \lambda_{1}=\lambda_{2}=0
$$
We may now show that this satisfies the subspace and hence is a spanning set of $U$:
$$
0=a_{0}+a_{1}+a_{2}=(-\lambda_{1}-\lambda_{2})+\lambda_{2}+\lambda_{1}=0
$$
We have shown that this is a basis of $U$ as this set of vectors is the spanning set $U$ and is linearly independent. We may then use the result that the number of vectors in a basis of a vector space gives its dimensions and we can see that $\dim(U)=2$.

4. By finding the rank of a suitably defined matrix, show that the following set of vectors in $\mathbb{R}^{4}$ is linearly independent$$U=\{ (1,0,0,0),(1,1,0,0),(1,1,1,0) \}$$Extend $U$ to a basis of $\mathbb{R}^{4}$ such that $U\subseteq B$.
$$
u_{1}=(1,0,0,0)\qquad u_{2}=(1,1,0,0)\qquad u_{3}=(1,1,1,0)
$$
$$
\begin{pmatrix}
u_{1} \\
u_{2} \\
u_{3}
\end{pmatrix}^{T}=\begin{pmatrix}
1 & 0 & 0 & 0 \\
1 & 1 & 0 & 0 \\
1 & 1 & 1 & 0
\end{pmatrix}^{T}=B^{T}=\begin{pmatrix}
1 & 1 & 1 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
0 & 0 & 0
\end{pmatrix}=\underline{\underline{A}}
$$
$$
\text{row}(\underline{\underline{B}})=\text{col}(\underline{\underline{B}}^{T})=\text{col}(\underline{\underline{A}})\qquad 
\text{col}(\underline{\underline{B}})=\text{row}(\underline{\underline{B}}^{T})=\text{row}(\underline{\underline{A}})
$$
The column space of $\underline{\underline{A}}$ is defined as $\text{col}(\underline{\underline{A}})=\text{span}\{u_{1}^{T},u_{2}^{T},u_{3}^{T}\}$. The rank of $\underline{\underline{A}}$ is equal to the column (or row) rank. The column rank is given by the number of non-zero columns in echelon form and this is 3. This means that the columns of $\underline{\underline{A}}$ are linearly independent as the rank is equal to the number of columns.

To extend $U$ to a basis of $\mathbb{R}^{4}$, we need a fourth basis vector (as $\mathbb{R}^{4}$ has $\dim(\mathbb{R}^{4})=4$ so it requires 4 basis vectors) that is linearly independent from the initial set so may add the following vector:
$$
u_{4}=(1,1,1,1) \iff u_{4}^{T}=\begin{pmatrix}
1 \\
1 \\
1 \\
1
\end{pmatrix}\therefore B=\text{span}\{ u_{1}^{T},u_{2}^{T},u_{3}^{T},u_{4}^{T} \}
$$
Observe the following matrix $\underline{\underline{A'}}$ is in echelon and has a rank of 4, and this is equal to to the number of columns, which are then also linearly independent. This is also a basis of $\mathbb{R}^{4}$ as there is 4 linearly independent vectors.
$$
A'=\begin{pmatrix}
1 & 1 & 1  & 1\\
0 & 1 & 1  & 1\\
0 & 0 & 1  & 1\\
0 & 0 & 0 & 1
\end{pmatrix}
$$

Then observe that we can rewrite the set $B$ as $B=U\cup \text{span}\{ u_{4}^{T} \}$. Hence $U$ is a strict subset of $B$. $U\subseteq B$.