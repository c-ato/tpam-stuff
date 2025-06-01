---
tags:
  - maths
  - algebra
---
> [!theorem|*] Dot product
> Let $v,u \in E^{n},v=\begin{pmatrix}x_{1} \\ y_{1}\\\dots \\n_{1}\end{pmatrix},u=\begin{pmatrix}x_{2} \\ y_{2}\\\dots \\n_{2}\end{pmatrix}$ and $v\cdot u = x_{1}x_{2}+y_{1}y_{2}+\dots n_{1}n_{2}$
 ^thm-

> [!definition|*]- Binary operation
> A binary operation on a set $V$ to a set $C$ is a function
> $$B:V\times V\mapsto C$$
 ^def-binary-oper

> [!definition|*]- Internal binary operation
> An internal binary operation on a set $V$ is a binary operation for which $C = V$ , or equivalently,
>$$x_{1}*x_{2}\in V\,\,\,\forall x_{1},x_{2}\in V$$
> If a binary operation is internal, then the set $V$ is said to be closed under the binary operation.
 ^def-int-bi-op

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
> - ∗ is associative; 
> - ∗ has an identity $V$
> - Every element of $V$ have an inverse element.
 ^def-group

> [!definition|*]- Abelian
> A group with binary operation $∗$ is called abelian if and only if $∗$ is commutative
 ^def-abelian

> [!definition|*]- Field
> A set F with binary operations $+$ and $×$ is called a field $(F, +, ×)$ if and only if: 
> - $(F, +)$ is an abelian group, with identity denoted by $0$
> - $(F \setminus \{ 0 \}, ×$) is an abelian group, with identity denoted by $1$
> - for all $x ∈ F , 0 × x = x × 0 = 0$
> - distributivity of $×$ with respect to $+$: for all $x_{1}, x_{2}, x_{3} ∈ F$ , we have $$x_{1} × (x_{2} + x_{3}) = (x_{1} × x_{2}) + (x_{1} × x_{3})$$
 ^def-field
 
> [!definition|*]- N-th root of a complex number
> Suppose that $n ≥ 1$ is a natural number. A complex number $w$ is an n-th root of a non-zero complex number $z$, denoted by w = $z^{1/n}$ if $w^{n} = z$. We say that w is a n-th root of unity of $w$ is a n-th root of $1$.
> 
> Generally to find it, convert to exponential form such $z=re^{i\theta}=p^{n}e^{ in \phi }$ s.t. $\phi= \frac{\theta}{n}+k \frac{2\pi}{n},k \in \mathbb{N}$.
> $$\therefore z^{1/n}= r^{1/n}e^{i\frac{\theta+2\pi k}{n}}$$
 ^def-nth-root-complex

$\forall z\in\mathbb{C}\exists n$ distinct n-th roots with equal distance around the origin in an Argand diagram which will differ to neighbouring by $\frac{2\pi}{n}$ and consequently form vertices of a regular n sided polygon 
