---
tags:
  - maths/algebra
  - concepts
  - maths/vectors
aliases:
  - group
  - orthogonal group
  - special orthogonal group
  - special orthogonal groups
  - orthogonal groups
  - abelian
---

> [!definition|*]- Commutative
> A binary operation on a set $V$ is commutative if and only if for all $x_{1}, x_{1} ∈ V$ $$x1 ∗ x2 = x2 ∗ x1$$
 ^def-commutative

> [!definition|*]- Associative
> A binary operation on a set $V$ is associative if and only if for all $x_{1}, x_{2}, x_{3} ∈ V$  $$(x1 ∗ x2) ∗ x3 = x1 ∗ (x2 ∗ x3)$$
> 
 ^def-associative

> [!definition|*]- Identity
> An element $e ∈ V$ is called an identity for a binary operation on a set $V$ if and only if for all $x_{1} ∈ V$  $$e ∗ x_{1} = x_{1} ∗ e = x_{1}$$.
 ^def-identity

> [!theorem|*]- Uniqueness of identity
> If a binary operation on a set $V$ has an identity, then the identity is unique.
 ^thm-uniq-ident

> [!definition|*]- Inverse
> Consider a binary operation on a set V which has identity $e ∈ V$ . An element $a ∈ V$ has an inverse if there exists an element $b ∈ V$ such that $$a ∗ b = b ∗ a = e$$
 ^def-inverse

> [!definition|*]- Group
> A set $V$ endowed with an internal binary operation $∗$ is called a group with respect to the binary operation $∗$ if and only if the following hold: 
> - $V$ is closed under the operation $*$ 
> - $*$ is associative; 
> - $*$ has an identity $V$
> - Every element of $V$ have an inverse element.
 ^def-alg-group

> [!definition|*]- Abelian Group
> A group with binary operation $∗$ is called abelian if and only if $∗$ is commutative
 ^def-alg-abelian

> [!definition|*]- General Linear Group
> This is the set of $n \times n$ invertible matrices with the operation of ordinary matrix multiplication. It is notated $GL(n,\mathbb{F})$ or $GL_{n}(\mathbb{F})$ where $\mathbb{F}$ is a field or ring or $GL(n)$ if the field is evident or even $GL(V)$ where $V$ is a vector space (the latter most will be used from hereforth).
 ^def-alg-GLV

> [!definition|*]- Orthogonal Matrices
> A square matrix of $n\times n$, $\underline{\underline{A}}\in\mathcal{M_{nn}}$ is orthogonal if $\underline{\underline{A}}^{-1}=\underline{\underline{A}}^{T}$
 ^def-alg-orth-matr

> [!definition|*]- Orthogonal Groups
> The orthogonal group of $n$, $O(n)$, is the group of all $n\times n$ orthogonal matrices of the reals. Geometrically this group represents the linear transformations of $\mathbb{R}^{n}$ that preserve the Euclidean inner product. This means they preserve lengths and angles.
> 
These transformations include rotation and reflection (across a hyperplane (this is a higher dimensional plane)).
 ^def-alg-orth-gro

> [!definition|*]- Special Orthogonal Group
> This is a subgroup of $O(n)$, $SO(n)$, which consists of all orthogonal matrices of determinant $1$. Geometrically this represents rotation
 ^def-alg-son
