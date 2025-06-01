---
tags:
  - maths
  - vectors
---
[[1VGLA_AU.pdf#page=179|1VGLA_AU, p.170]]

> [!theorem|*]- Any vector is a unique linear combination of basis vectors
> Consider a vector space $V$ and a basis $B = \{\mathbf{u}_{1}, \mathbf{u}_{2}, . . . , \mathbf{u}_{n}\}$ of $V$. Then any vector $\mathbf{v} \in V$ can be written as a linear combination of the vectors of $B$ in exactly one way.
 ^thm-vgla-vector-composed-basis-unique

> [!definition|*]- Coordinates
> Consider a vector space $V$ with an ordered basis $B = \{\mathbf{u}_{1}, \mathbf{u}_{2}, . . . , \mathbf{u}_{n}\}$ and a vector $\mathbf{v}\in V$ with
> $$\mathbf{v}=\lambda_{1}\mathbf{u}_{1}+\lambda_{2}\mathbf{u}_{2}+\dots+\lambda_{n}\mathbf{u}_{n}$$
> where $λ_{i} ∈ \mathbb{R}$ for all values of $i$. Then the uniquely determined real numbers $λ_{1}, λ_{2},\dots , λ_{n}$ (in the given order) are known as the coordinates of $\mathbf{v}$ with respect to the basis $B$. We call $(\lambda_{1},\lambda_{2},\dots,\lambda_{n})$ the coordinate vector of $\mathbf{v}$ with respect to the basis $B$
 ^def-vgla-coord

> [!theorem|*]- Property of dimensionality on set of vectors of $n$ elements
> Let $V$ be a vector space of dimension $n\in \mathbb{N}$ and assume that $S$ is a set of vectors in $V$. Then:
> - if $|S|>n$ then $S$ is linearly dependent; and
> - if $|S|<n$ then $V\neq \text{span}(S)$
 ^thm-vgla-n-vect-span-lin-dep

> [!lemma|*]- Expanding a linearly independent set of vectors
> Consider a linearly independent set of $k$ vectors in a space $V$, $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, and a vector $\mathbf{v} \in V$. Then the set
> $$\{ \mathbf{v},\mathbf{u_{1}},\mathbf{u}_{2},\dots,\mathbf{u}_{l} \}$$
> Is linearly independent if and only if 
> $$\mathbf{v} \notin \text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$$
 ^lem-vgla-lin-indep-expansion

> [!theorem|*]- Dimension is restricted by spanning sets
> Let $V$ be a vector space over $\mathbb{F}$ and assume that $V \neq 0$ is spanned by $ℓ$ vectors $(ℓ ∈ \mathbb{N})$. Then: 
> - each linearly independent set of vectors is part of a basis of $V$ ; 
> - if $X ⊆ V$ spans $V$, then there exists $B ⊆ X$ such that $B$ is a basis for $V$; and 
> - $V$ has a basis and $\dim(V ) ≤ ℓ$.
 ^thm-vgla-spanning-set-dimension

> [!theorem|*]- If $S$ spans or is linearly independent (of $n$ vectors) then is a bassi
> Let $V$ be a vector space $V$ of dimension $n ≥ 1$ and let $S = \{u_{1}, . . . , \mathbf{u}_{n}\}$ be a set of $n$ vectors in $V$. 
> - If $S$ spans $V$ , then $S$ is a basis for $V$.  
> - If $S$ is linearly independent, then $S$ is a basis for V
 ^thm-vgla-lin-dep-span-basis

> [!theorem|*]- Properties of subspaces dimension and their bases of $V$
> Consider a real vector space $V$ of dimension $n ∈ \mathbb{N}$. Let $U$ and $W$ be subspaces of $V$ . Then,  
> - $U$ and $W$ are finite-dimensional with $\dim(U ) ≤ n$ and $\dim(W ) ≤ n$;  
> - any basis of $U$ and any basis of $W$ can be extended to a basis of $V$ ; and  
> - if $U ⊆ W$ and $\dim(U ) = \dim(W )$ then $U = W$
 ^thm-vgla-subspace-dim-bases

> [!definition|*]- Row (column) space
> Consider a matrix $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{F})$ and let $\mathbf{u}_{i}$, denote the vector in $\mathbb{F^{n}}$ associated with the $i$-th row (column) in $\underline{\underline{A}}$. Then the row (column) space of $\underline{\underline{A}}$, denoted by $\text{row}(\underline{\underline{A}})$ ($\underline{\underline{A}}$, denoted by $\text{col}(\underline{\underline{A}})$) is the subspace of $\mathbb{F}^{n}$ given by
> $$\text{row}(\underline{\underline{A}})=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{m} \}\qquad \text{col}(\underline{\underline{A}})=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{m} \}$$
 ^def-vgla-row-col-space

> [!definition|*]- Row (and column) rank
> Where $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R})$, the row (column) rank of $\underline{\underline{A}}=\dim(\text{row}(\underline{\underline{A}}))$ ($\underline{\underline{A}}=\dim(\text{col})(\underline{\underline{A}}))$) or the number of non zero rows (column) in $\underline{\underline{\tilde{A}}}$
 ^def-vgla-row-rank

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
