---
tags:
  - maths/vectors
  - concepts
aliases:
  - subspace
---
"The field $\mathbb{R}$" implies that $(\mathbb{R},+,\cdot)$

Generally, use $F$, or $(F,+,\cdot)$ to denote general fields.

> [!definition|*]- Vector space
> A set non-empty $V$ with binary operation $\oplus$ and a scalar multiplication $\odot$ with elements from a field $(F,+,\cdot)$ is called a vector space over $F$ when the following properties are satisfied.
> - $(V,\oplus)$ is an abelian group with identity $0$:
> 	- Closure, associativity, identity, inverse and commutativity
> - $V$ is closed under the scalar multiplication $\odot$ $$\forall a\in V,\forall\lambda \in F: \lambda \odot a \in V$$
> - Distributivity for scalar multiplication with respect to $\oplus$ in $V$: $$\forall a,b\in V,\forall\lambda \in F: \lambda \odot (a\oplus b )= (\lambda \odot a)\oplus (\lambda \odot b)$$
> - Distributivity for scalar multiplication with respect to $+$ in $\mathbb{F}$ $$\forall \mathbf{a}\in V,\forall \lambda,\nu \in F: (\lambda + \nu) \odot \mathbf{a}= (\lambda \odot \mathbf{a}) \oplus (\nu \odot \mathbf{a})$$
> - Mixed associativity for $\cdot$ and $\odot$ $$\forall \mathbf{a}\in V, \forall \lambda,\nu \in \mathbb{F}: \lambda \odot(\nu \odot \mathbf{a})=(\lambda \cdot \nu)\odot \mathbf{a}$$
> - The identity of $(\mathbb{F}\setminus \{ 0 \},\cdot)$ is also the idenetity for scalar multiplication: $$\forall \mathbf{a}\in V:1 \odot\mathbf{a}=\mathbf{a}$$
 ^def-vgla-vec-space

"The vector space $V$" implies that $(V, \oplus,\odot)$

$V$ is a vector space over $\mathbb{R}$, then $V$ is called a "real vector space".

> [!definition|*]- Subspace
> A subspace $U$ of a vector space $V$ over $\mathbb{F}$ is called a subspace of $V$ if $U$ is non-empty and $U$ is itself a vector space over $\mathbb{F}$ under the same operations of addition and scalar multiplication of $V$ as a vector space over $\mathbb{F}$. We write $U\leq V$ to indicate that $U$ is a subspace of $V$ and not just a subset $V$
 ^def-vgla-subspace

> [!theorem|*]- Subset is subspace if following
> A subset $U$ of a vector space $V$ over $\mathbb{F}$ is a subspace of $V$ if and only if $U$ is non-empty and 
> - $u + v ∈ U \forall u,v \in U$; and 
> - $λu ∈ U \forall λ ∈ \mathbb{F}, u ∈ U$
 ^thm-vgla-subset-subspace

> [!definition|*]- Row (column) space
> Consider a matrix $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{F})$ and let $\mathbf{u}_{i}$, denote the vector in $\mathbb{F^{n}}$ associated with the $i$-th row (column) in $\underline{\underline{A}}$. Then the row (column) space of $\underline{\underline{A}}$, denoted by $\text{row}(\underline{\underline{A}})$ ($\underline{\underline{A}}$, denoted by $\text{col}(\underline{\underline{A}})$) is the subspace of $\mathbb{F}^{n}$ given by
> $$\text{row}(\underline{\underline{A}})=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{m} \}\qquad \text{col}(\underline{\underline{A}})=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{m} \}$$
 ^def-vgla-row-col-space

> [!definition|*]- Row (and column) rank
> Where $\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R})$, the row (column) rank of $\underline{\underline{A}}=\dim(\text{row}(\underline{\underline{A}}))$ ($\underline{\underline{A}}=\dim(\text{col})(\underline{\underline{A}}))$) or the number of non zero rows (column) in $\underline{\underline{\tilde{A}}}$
 ^def-vgla-row-rank

> [!definition|*]- Kernel and image
> Suppose that $T : V → W$ is a linear transformation. Then the kernel, is the subset of $V$ defined by $$\ker(T ) = \{\mathbf{v} ∈ V | T (\mathbf{v}) = \mathbf{0}\}$$and the image of $T$ is the subset of $W$ defined by $$\text{im}(T ) = \{T (\mathbf{v}) | \mathbf{v} ∈ V \}$$
 ^def-vgla-kernel-image

> [!theorem|*]- Image and kernel are subspaces
> Suppose that $V$ and $W$ are vector spaces over $\mathbb{F}$ and let $T : V → W$ be a linear transformation. Then $\ker(T )$ is a subspace of $V$ and $\text{im}(T )$ is a subspace of $W$.
 ^thm-vgla-kern-im-subsp

$$
x^{2}\implies2x
$$
$\underline{\underline{A}}\in\mathcal{M_{mn}}(\mathbb{R}):= A_{(m+1)(n)}=n$
$$
\begin{pmatrix}
0 & 1 & 0 & 0 & \dots \\
0 & 0 & 2 & 0 & \dots \\
0 & 0 & 0 & 3 & \dots \\
0 & 0 & 0 & 0 & \dots \\
\vdots & \vdots & \vdots & \vdots & \ddots
\end{pmatrix}\begin{pmatrix}
co(1) \\
co(x) \\
co(x^{2}) \\
co(x^{3}) \\
\vdots
\end{pmatrix} =\begin{pmatrix}
co(x) \\
2co(x^{2}) \\
3co(x^{3}) \\
4co(x^{4}) \\
\vdots
\end{pmatrix}
$$
> [!theorem|*]- Rank nullity
> Consider two real vector spaces $V$ and $W$ , with $dim(V )= n$. Let $T : V → W$ be a linear transformation. Then, $\text{rank of }T +\text{ nullity of }T = n$.
 ^thm-rank-nullity
