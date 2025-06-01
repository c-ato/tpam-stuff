---
tags:
  - maths
  - algebra
---
> [!definition|*]- Submatrix
> A submatrix of $\mathbf{A}\in\mathcal{M_{mn}}(\mathbb{R})$ is obtained from $\mathbf{A}$ by deleting $\tilde{m}$ rows from $\mathbf{A}$ with $0\leq\tilde{m}\leq m-1,\,0\leq \tilde{n}\leq n-1$ and $\max\{ \tilde{m},\tilde{n} \}\geq 1$
 ^def-vgla-submat

> [!definition|*]- $(i,j)$-minor
> The $(i,j)$-minor of a matrix is written $M_{ij}(\mathbf{A})$, is the determinant of the $(n-1)\times(n-1)$-submatrix of $\mathbf{A}$ obtained by deleting row $i$ and column $j$ of $\mathbf{A}$
 ^def-vgla-i-j-minor

> [!definition|*]- Triangular matrix
> A matrix is triangular is either:
> - Upper triangular $a_{ij}=0$ whenever $i>j$
> - Lower triangular $a_{ij}=0$ whenever $i<j$
 ^def-vgla-trian-mat

> [!theorem|*]- Determinant of triangular
> The determinant of a triangular matrix is the product of the the diagonals 
 ^thm-vgla-det-triang-mat

> [!definition|*]- Cofactor
> Let $\underline{\underline{A}}\in \mathcal{M}_{nm}(\mathbb{R})$, where the cofactor matrix of $\underline{\underline{A}}$ is denoted as $\underline{\underline{C}}(\underline{\underline{A}})$ where $\underline{\underline{C}}_{ij}=(-1)^{i+j}\det(\underline{\underline{A^{*}}})$ where $\underline{\underline{A^{*}}}$ is $\underline{\underline{A}}$ with row $i$ and column $j$ removed - a $i$-$j$ minor..
 ^def-vgla-cofact

> [!definition|*]- The adjoint matrix
> This of $\underline{\underline{A}}$, is denoted as $adj(\underline{\underline{A}})=(\underline{\underline{C}}(\underline{\underline{A}}))^{T}$
 ^def-vgla-adj-mat

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

