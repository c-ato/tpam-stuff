---
tags:
  - maths/vectors
  - concepts
aliases:
  - linear independence
  - linear dependence
  - linearly independent
  - linearly dependent
---

> [!definition|*]- Linear combination
> A vector $\mathbf{v}\in V$ , with $V$ a vector space over $\mathbb{F}$, is a linear combination of the vectors $u_{1}, u_{2},\dots, u_{k} ∈ V$ if $\mathbf{v}$ can be written in the form
> $$\mathbf{v}=\lambda_{1}\mathbf{u}_{1}+\lambda_{2} \mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}=\sum^{k}_{i=1}\lambda_{i}\mathbf{v}_{i}$$
> where $\lambda_{1},\lambda_{2},\dots,\lambda_{k}\in\mathbb{F}$
 ^def-vgla-lin-comb

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

> [!theorem|*]- Any vector is a unique linear combination of basis vectors
> Consider a vector space $V$ and a basis $B = \{\mathbf{u}_{1}, \mathbf{u}_{2}, . . . , \mathbf{u}_{n}\}$ of $V$. Then any vector $\mathbf{v} \in V$ can be written as a linear combination of the vectors of $B$ in exactly one way.
 ^thm-vgla-vector-composed-basis-unique
 
> [!lemma|*]- Expanding a linearly independent set of vectors
> Consider a linearly independent set of $k$ vectors in a space $V$, $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, and a vector $\mathbf{v} \in V$. Then the set
> $$\{ \mathbf{v},\mathbf{u_{1}},\mathbf{u}_{2},\dots,\mathbf{u}_{l} \}$$
> Is linearly independent if and only if 
> $$\mathbf{v} \notin \text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$$
 ^lem-vgla-lin-indep-expansion
