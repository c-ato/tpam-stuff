---
tags:
  - maths/vectors
  - concepts
aliases:
  - linear transformation
---

> [!definition|*]- Linear transformation
> Let $V$ and $W$ be vector spaces over $\mathbb{F}$. A function $T:V\to W$ is called a linear transformation if:
> - $T(\mathbf{v}_{1}+\mathbf{v}_{2})=T(\mathbf{v}_{1})+T(\mathbf{v}_{2})$ for all $\mathbf{v}_{1},\mathbf{v}_{2}\in V$
> - $T(\lambda \mathbf{v})=\lambda T(\mathbf{v})$ for all $\lambda \in \mathbb{F},\mathbf{v} \in V$
 ^def-vgla-lin-trans

> [!theorem|*]- Properties of linear transformations
> Consider vector spaces $V$ and $W$ over $\mathbb{F}$ and let $T:V\to W$ be a linear transformation. Then:
> - $T(\mathbf{0})=\mathbf{0} \in W$
> - $T(-\mathbf{v})=-T(\mathbf{v})\forall \mathbf{v}\in V$ with $-\mathbf{v}\in V$ the additive inverse of $\mathbf{v}$
> - $T(\lambda_{1}\mathbf{v}_{1}+\lambda_{2}\mathbf{v}_{2}+\dots+\lambda_{k}\mathbf{v}_{k})=T(\lambda_{1}\mathbf{v}_{1})+T(\lambda_{2}\mathbf{v}_{2})+\dots+T(\lambda_{k}\mathbf{v}_{k})$$\forall \mathbf{v}_{1},\mathbf{v}_{2},\dots, \mathbf{v}_{k}\in V,\lambda_{1},\lambda_{2},\dots,\lambda_{k}\in \mathbb{F}$
 ^thm-vgla-lin-trans-prop

> [!theorem|*]- Equivalence of linear transformations
> Consider two real vector spaces $V$ and $W$ . Let $B = \{\mathbf{v}_{1}, \mathbf{v}_{2}, \dots , \mathbf{v_{n}}\}$ be a basis of $V$ with $\dim(V ) = n$. Let $T_{1} : V → W$ and $T_{2} : V → W$ be linear transformations such that$$T_{1}(\mathbf{v}_{i})=T_{2}(\mathbf{v}_{2})\qquad \forall \mathbf{v}_{i}\in B$$
> Then $T_{1}=T_{2}$
 ^thm-vgla-lin-trans-equi

> [!theorem|*]- Unique linear transformation
> Consider two real vector spaces $V$ and $W$ . Let $B = \{\mathbf{v}_{1}, \mathbf{v}_{2}, \dots , \mathbf{v_{n}}\}$ be a basis of $V$ with $\dim(V ) = n$. Let $\mathbf{w}_{1},\mathbf{w}_{2},\dots ,\mathbf{w}_{n}$ be $n$ (not necessarily distinct) vectors in $W$. Then there exists a unique linear transformation $T : V → W$ such that $$T (\mathbf{v}_{1}) = \mathbf{w}_{1}, T (\mathbf{v}_{2}) = \mathbf{w}_{2}, \dots , T (\mathbf{v}_{n}) = \mathbf{w}_{n}$$
 ^thm-vgla-uniq-lin-trans

> [!definition|*]- Composition (linear transformation)
>  Let $U$, $V$ and $W$ be vector spaces over $\mathbb{F}$ and $T : U → V$ and $S : V → W$ be linear transformations. Then the composition of $T$ and $S$ is defined by the mapping $S ◦ T : U → W$ , with $$S ◦ T = S(T (\mathbf{u})) \qquad ∀ \mathbf{u} ∈ U$$
 ^def-vgla-compo-lin-trans

> [!definition|*]- Composition of linear transformations
>  Let $U$, $V$ and $W$ be vector spaces over $\mathbb{F}$ and $T : U → V$ and $S : V → W$ be linear transformations. Then the composition of $T$ and $S$, denoted by $S◦T:U\to W$, is linear transformation from $U$ to $W$
 ^def-vgla-comp-lin-trans
