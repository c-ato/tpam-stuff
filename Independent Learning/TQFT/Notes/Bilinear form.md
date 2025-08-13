---
tags:
  - temp
  - maths/vectors
  - maths/algebra
---
> [!definition|*]- Bilinear Form
> Let $V$ and $W$ be vector spaces over field $k$. A function $B$ is called a bilinear form if:
> - $B(v+u,w)=B(v,w)+B(u,w)$, and $B(v,w+u)=B(v,w)+B(v,u)$ for $u,v,w \in W$
> - $B(\lambda v,w)=\lambda B(v,w)=B(v,\lambda w)$
 ^def-vec-bi-lin-form

> [!definition|*]- Non-degenerate bilinear form
> A bilinear form, $B$ of a vector space, $V$ satisfies $B(v,w)=0\iff v\lor w=0$ for $v,w \in V$
 ^def-vec-non-degen-bilin-form

> [!definition|*]- Super Bilinear form
> This is a bilinear form, $B$, of a super vector space, $A=A_{\bar{0}}\oplus A_{\bar{1}}$ that also satisfies $B(v,w)=0\iff \text{deg}(v)+\text{deg}(w)=\bar{1}\quad \text{mod }2$ for $v,w\in A$.
 ^def-vec-sup-bilin-form

