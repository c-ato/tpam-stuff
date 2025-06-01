---
tags:
  - maths
  - vectors
  - algebra
---
[[1VGLA_AU.pdf#page=161|1VGLA_AU, p.152]]

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

> [!definition|*]- Subtraction
> A subtraction is the inverse of the binary operation $+$ on the real vector space $V$
 ^def-vgla-subtraction

> [!definition|*]- Subspace
> A subspace $U$ of a vector space $V$ over $\mathbb{F}$ is called a subspace of $V$ if $U$ is non-empty and $U$ is itself a vector space over $\mathbb{F}$ under the same operations of addition and scalar multiplication of $V$ as a vector space over $\mathbb{F}$. We write $U\leq V$ to indicate that $U$ is a subspace of $V$ and not just a subset $V$
 ^def-vgla-subspace

> [!theorem|*]- Subset is subspace if following
> A subset $U$ of a vector space $V$ over $\mathbb{F}$ is a subspace of $V$ if and only if $U$ is non-empty and 
> - $u + v ∈ U \forall u,v \in U$; and 
> - $λu ∈ U \forall λ ∈ \mathbb{F}, u ∈ U$
 ^thm-vgla-subset-subspace

> [!definition|*]- Linear combination
> A vector $\mathbf{v}\in V$ , with $V$ a vector space over $\mathbb{F}$, is a linear combination of the vectors $u_{1}, u_{2},\dots, u_{k} ∈ V$ if $\mathbf{v}$ can be written in the form
> $$\mathbf{v}=\lambda_{1}\mathbf{u}_{1}+\lambda_{2} \mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}=\sum^{k}_{i=1}\lambda_{i}\mathbf{v}_{i}$$
> where $\lambda_{1},\lambda_{2},\dots,\lambda_{k}\in\mathbb{F}$
 ^def-vgla-lin-comb

> [!definition|*]- Spanning set
> If $u_{1}, u_{2},\dots, u_{k} ∈ V$, with $V$ a vector space over $\mathbb{F}$, then the subset of $V$ consisting of all possible linear combination of $u_{1}, u_{2},\dots, u_{k}$ is called their span and is denoted
> $$\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}=\{ \lambda_{1}\mathbf{u}_{1}+\lambda_{2} \mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}|\lambda_{1},\lambda_{2},\dots,\lambda_{k} \in \mathbb{F} \}$$
> If $U=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, then we say that $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$ is a spanning set for $U$ or that $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$ spans $U$
 ^def-vgla-spanning-set

> [!theorem|*]- Spanning set is a subspace
> Suppose that $U=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, where for a vector space $V$ over $\mathbb{F}$ we have $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \in V$. Then,
> - $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \in U$
> - $U$ is a subspace of $V$, and
> - $U$ is the smallest subspace of $V$ that contains $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k}$ in the sense that if $\tilde{U}$ is another subspace of $V$, which contains $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k}$, then $U\subseteq \tilde{U}$
 ^thm-spanning-set-subspace

> [!definition|*]- Linear independence
> A set of vectors $\{ u_{1},u_{2},\dots u_{k} \}$ in a vector space $V$ over $\mathbb{F}$ is said to be linearly independent if and only if for $\lambda_{1},\lambda_{2},\dots,\lambda_{k}\in \mathbb{F}$,
> $$\lambda_{1}\mathbf{u_{1}}+\lambda_{2}\mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}=0 \iff \lambda_{1}=\lambda_{2}=\dots=\lambda_{k}=0$$
 ^def-vgla-lin-indep

> [!definition|*]- Linear dependence
> A set of vectors $\{ u_{1},u_{2},\dots u_{k} \}$ in a vector space $V$ over $\mathbb{F}$ is said to be linearly dependent if there is a non-trivial linear combination which is equal to the zero vector, i.e.
> $$\lambda_{1}\mathbf{u_{1}}+\lambda_{2}\mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}=0 \cancel{ \implies } \lambda_{i}=0\forall i=1,\dots,k$$
 ^def-vgla-lin-dep

> [!theorem|*]- $V$ contains a linearly independent subset
> Consider a vector space $V$ over $\mathbb{F}$ and assume that $V\neq \{ 0 \}$. Then any set of finitely many non-zero vectors in $V$ which spans $V$ contains a linearly independent subset which spans $V$
 ^thm-vgla-V-indep-subset

> [!theorem|*]- Linearly independent subset never exceeds spanning set
> Let $S$ be a set of $k$ vectors in a vector space $V$ which spans $V$. Let $T$ be a linearly independent set of $m$ vectors in $V$. Then,
> $$m\leq k$$
 ^thm-vgla-lin-indep-set-less-spanning

> [!definition|*]- Basis
> A set of vectors $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$ in a vector space $V$ is called a basis of $V$ if
> - $V=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$
> - $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots \mathbf{u_{k}} \}$ is a linearly independent set
 ^def-vgla-basis

> [!definition|*]- Finite-dimensional
> A vector space $V$ is called finite-dimensional if there exists a basis of $V$ which contains a finite number of vectors. A vector space which is not finite-dimensional is called infinite-dimensional.
 ^def-vgla-finite-dim

> [!definition|*]- Dimension
> The number of vectors in any basis of a finite-dimensional vector space $V$ is called the dimension of $V$, also written as $\dim(V )$.
 ^def-vgla-def