---
tags:
  - maths
  - maths/category
aliases:
  - functor
  - tensor product
  - tensor products
---

> [!definition|*]- Functors
> Let $\mathcal{C}$ and $\mathcal{D}$ be [[categories]], $X,Y$ be of $\mathcal{C}$, $f:X\to Y,g:Y\to X$, and then the functor is $F: \mathcal{C}\to \mathcal{D}$ so that it maps each object in $\mathcal{C}$ to $\mathcal{D}$, $F(X)\implies\text{Obj}(\mathcal{D})$. 
> 
> The same for each [[Morphisms|morphism]] $f$ such that $F(f):F(X)\to F(Y)$, while also preserving the identity: $F(I_{\mathcal{C}})=I_{\mathcal{D}}$ and $F(g\circ f)=F(g)\circ F(f)$.
 ^def-cat-functor

> [!definition|*]- Tensor Product
> This binary operator $\otimes$ takes two objects of a single [[Categories|category]], $\mathcal{C}$ satisfies the following:
> - $A,B$ of $\mathcal{C}$ to make a new object $A\otimes B$
> - It also needs to satisfy for composition for [[morphisms]]: $A',B'$ are of $\mathcal{C}$, $f:A\to A'$ and $g:B\to B'$ such that $f\otimes g:A\otimes B\to A'\otimes B'$
> - Finally for the identity $\text{id}_{A}\otimes \text{id}_{B}=\text{id}_{A\otimes B}$ to be true
 ^def-cat-tens-prod

