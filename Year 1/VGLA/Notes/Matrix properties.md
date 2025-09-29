---
tags:
  - maths/algebra
  - maths/property
---

> [!definition|*]- Determinant
> Let $\mathbf{A}\in\mathcal{M_{nm}}(\mathbb{R})$. The determinant of $\mathbf{A}=[a_{ij}]$, denoted by $\\det(A)$ or $|A|$is given by
> $$\sum_{\sigma \in S_{n}}(-1)^{N(\sigma)}\prod^{n}_{i=1}a_{\sigma(i)i}$$
 ^def-vgla-determ

> [!theorem|*]- Transpose identity
> $$(A_{1}\cdot A_{2}\cdot A_{3}\dots A_{k})^{T}=A_{k}^{T}\cdot A_{k-1}^{T}\dots A_{2}^{T}+A_{1}^{T}$$
 ^thm-vgla-transp-mat-ident

> [!theorem|*]- Transpose determinent identity
> $\det(A)=\det(A^{T})$
 ^thm-vgla-transp-mat-det-ident

ERO on matrix:
Multiply a a row or column by $\lambda$ causes $\det(A)\to\lambda \det(A)$. A matrix with a row or column of $0\implies\det(A)=0$. Swapping rows or columns the determinant $\det(A)\to-\det(A)$. A matrix with 2 same rows or columns will have $\det(A)=0$. Add multiple of a row or column to another: $\det(A)=\det (A)$

> [!theorem|*]- Elementary row operations (EROs)
> EROs do not alter the solutions of a system of simultaneous linear equations:
> - Interchange/switch two rows
> - Multiply a row by a non-zero constant
> - Add a multiple of one row to another row
 ^thm-vgla-eros

> [!definition|*]- Echelon form of a matrix
>- All rows consisting of only zeros are at the bottom of the matrix
>- The first non-zero number (in order from left to right) in any row is $'1'$
>- And successive non-zero rows begin with more zeros left of the $'1'$ than the rows above.
>A matrix is in reduced echelon form if it is in echelon form and the first non-zero entry in each row is the only non-zero entry in its column.
 ^def-vgla-echelon-mat

$$\left(
\begin{array}{cc|c}
2 & 1 & 3 \\
1 & 3 & 2
\end{array}\right)= \left(\begin{array}{cc|c}
1 & -2 & 1 \\
0 & 5 & 1
\end{array}\right) \therefore 5y= 1\quad x-2y=1\implies y=\frac{1}{5},x=\frac{7}{5}
$$

> [!theorem|*]- Determinant of triangular
> The determinant of a triangular matrix is the product of the the diagonals 
 ^thm-vgla-det-triang-mat

> [!definition|*]- Cofactor
> Let $\underline{\underline{A}}\in \mathcal{M}_{nm}(\mathbb{R})$, where the cofactor matrix of $\underline{\underline{A}}$ is denoted as $\underline{\underline{C}}(\underline{\underline{A}})$ where $\underline{\underline{C}}_{ij}=(-1)^{i+j}\det(\underline{\underline{A^{*}}})$ where $\underline{\underline{A^{*}}}$ is $\underline{\underline{A}}$ with row $i$ and column $j$ removed - a $i$-$j$ minor..
 ^def-vgla-cofact

> [!theorem|*]- The adjoint-identity matrix relationship
> $\forall\underline{\underline{A}}\in \mathcal{M}_{nm}(\mathbb{R})$,
> $$\underline{\underline{A}}\cdot adj(\underline{\underline{A}})=adj(\underline{\underline{A}})\cdot \underline{\underline{A}}=\det(\underline{\underline{A}}) \underline{\underline{I}}$$
> If $\det(\underline{\underline{A}})= 0$
> $$\underline{\underline{A}}\cdot adj(\underline{\underline{A}})=adj(\underline{\underline{A}})\cdot A=0$$
> If $\det(\underline{\underline{A}})\neq 0$
> $$\implies \underline{\underline{A}}^{-1}= \frac{1}{\det\underline{\underline{A}}} adj(\underline{\underline{A}})$$
 ^thm-vgla-adj-iden-relation

> [!theorem|*]- 
> $\underline{\underline{A}}\cdot x=0$ has any non-trivial solution $\iff$ $\det A=0$
 ^thm-

> [!theorem|*]- Crammer's rule
> Let $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R})$ with $\det A\neq 0$. Let $\underline{b}\in \mathbb{R}^{n}$ be the vector of constants, where $b_{1},b_{2},b_{2}\dots b_{n}$ not all $0$. Let $\underline{x}\in \mathbb{R}^{n}$ be vector of unknowns.
> The inhomogeneous system
> $$\underline{\underline{A}}\cdot \underline{x}=\underline{b}$$
> Has unique solution given by:
> $$x_{1}=\frac{\det(\underline{\underline{A}}_{1})}{\det(\underline{\underline{A}})}\qquad x_{2}=\frac{\det(\underline{\underline{A}}_{2})}{\det(\underline{\underline{A}})}\qquad\dots\qquad x_{n}=\frac{\det(\underline{\underline{A}}_{n})}{\det(\underline{\underline{A}})}$$
> Where $\underline{\underline{A}}_{k}$ is obtained from $\underline{\underline{A}}$ by replacing column $k$ with $\underline{b}$
 ^thm-vgla-crammers-rule

> [!definition|*]- Eigenvector and eigenvalues
> Let $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R})$ and suppose that $\lambda \in \mathbb{R}$ is an eigen value of $\underline{\underline{A}}$. Then the non-zero vector $\underline{\underline{x}}\in\mathcal{M_{n1}}(\mathbb{R})$ or vector in $\mathbb{R}^{n}$ is an eigenvector for $\underline{\underline{A}}$ if:
> $$\underline{\underline{A}}\cdot \underline{\underline{x}}=\lambda \underline{\underline{x}}$$
 ^def-vgla-eigen

> [!theorem|*]- Equivalence of row and column rank of a matrix
> $\forall \underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R})$, row rank of $\underline{\underline{A}}=$ column rank of $\underline{\underline{A}}$
 ^thm-vgla-row-col-rank-equiv

> [!theorem|*]- Invertibility of a matrix
> Consider $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{F})$, $\underline{\underline{M}}\in\mathcal{M_{mn}}(\mathbb{F})$ and $\underline{\underline{N}}\in\mathcal{M_{mn}}(\mathbb{F})$. Then 
> 	- $\text{row}(\underline{\underline{M}}\cdot \underline{\underline{A}})\subseteq \text{row}(\underline{\underline{A}})$ where $\text{row}(\underline{\underline{M}}\cdot \underline{\underline{A}})=\text{row}(\underline{\underline{A}})$ if $\underline{\underline{M}}$ is invertible
> 	- $\text{col}(\underline{\underline{N}}\cdot \underline{\underline{A}})\subseteq \text{col}(\underline{\underline{A}})$ where $\text{col}(\underline{\underline{N}}\cdot \underline{\underline{A}})=\text{col}(\underline{\underline{A}})$ if $\underline{\underline{N}}$ is invertible
 ^thm-vgla-invert-mat

> [!definition|*]- Matrix rank
> For any $m\times n$ matrix $\underline{\underline{A}}$, row rank of $(\underline{\underline{A}})=$ column rank of $(\underline{\underline{A}}):=\text{rank}(\underline{\underline{A}})$ or more generally m$\text{rank}(\underline{\underline{A}})\leq \min(m,n)$
 ^def-vgla-mat-rank

> [!corollary|*]- Solutions of a linear system with regards to column space
> The system of equations $\underline{\underline{A}}\cdot \mathbf{\underline{x}}=\mathbf{\underline{d}}$ of $m$ equations in $n$ unknowns has at least one solution $\iff$ $$\text{col}([\underline{\underline{A}}|\mathbf{\underline{d}}])=\text{col}(\underline{\underline{A}})$$
> Where $[\underline{\underline{A}}|\mathbf{\underline{d}}]$ is the augmented $m$ by $n+1$ matrix obtained by adding a column, consisting of the elements of $\mathbf{\underline{d}}$ to the right of the matrix $\underline{\underline{A}}$
 ^cor-vgla-lin-sys-sol-col

> [!theorem|*]- Solutions of a linear system with regards to rank
> A system of equations $\underline{\underline{A}}\cdot \mathbf{\underline{x}}=\mathbf{\underline{d}}$ of $m$ equations in $n$ unknowns has at least one solution $\iff$ the coefficient matrix $\underline{\underline{A}}$ and the augmented matrix $[\underline{\underline{A}},\mathbf{\underline{d}}]$ have the same rank
 ^thm-vgla-lin-sys-sol-rank

> [!theorem|*]- Unique solutions of a linear system with regards to $n$
> A system of equations $\underline{\underline{A}}\cdot \mathbf{\underline{x}}=\mathbf{\underline{d}}$ of $m$ equations in $n$ unknowns has a unique solution $\iff$ the coefficient matrix $\underline{\underline{A}}$ and the augmented matrix $[\underline{\underline{A}},\mathbf{\underline{d}}]$ have rank equal to $n$.
 ^thm-vgla-lin-sys-uniq-sol-n-rank
