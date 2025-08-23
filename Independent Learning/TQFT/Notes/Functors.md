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

> [!definition|*]- Direct sum
> This binary operator $\oplus$ takes two objects, $A$ and $B$, of a single [[Categories|category]], $\mathcal{C}$ to make a new object $A\oplus B$ together with four morphisms
> - The projective morphisms $p_{A}:A\oplus B\to A$ and $p_{B}:A\oplus B\to B$
> - The injective morphisms $i_{A}:A\to A\oplus B$ and $i_{B}:B\to B$, 
> - Finally for the identity $p_{A}\circ i_{A}=\text{id}_{A}$ and $p_{B}\circ i_{B}=\text{id}_{B}$ to be true
 ^def-cat-tens-prod


> [!definition|*]- Super Tensor Product
> This binary operator $\otimes_{s}$ takes two objects of a single [[Categories|category]], $\mathcal{C}$ satisfies the following:
> - $A,B$ of $\mathcal{C}$, a super vector space, to make a new object $A\otimes_{s} B$, where the grade of the new object is given as $\text{deg}(a\otimes_{s}b)=\text{deg}(a)+\text{deg}(b)\, \text{mod(2)}$, where $a \in A,b \in B$
> - It also needs to satisfy for composition for [[morphisms]]: $A',B'$ are of $\mathcal{C}$, $f:A\to A'$ and $g:B\to B'$ such that $f\otimes_{s} g:A\otimes_{s} B\to A'\otimes_{s} B'$, where the grade of the new morphism is given as $\text{deg}(f\otimes_{s}g)=\text{deg}(f)+\text{deg}(g)\, \text{mod(2)}$
> - For the identity $\text{id}_{A}\otimes_{s} \text{id}_{B}=\text{id}_{A\otimes_{s} B}$ to be true where it is an morphism contained in the bosonic space of the super vector space, so its degree is always $0$
> - Finally for supersymmetry to hold as such, $a\otimes_{s}b=(-1)^{\text{deg}(a)\cdot \text{deg}(b)}b\otimes_{s}a$
 ^def-cat-sup-tens-prod
