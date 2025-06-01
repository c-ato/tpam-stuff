---
tags:
  - maths
  - vectors
---
[[1VGLA_AU.pdf#page=195|1VGLA_AU, p.186]]

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
