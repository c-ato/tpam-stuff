---
tags:
  - maths/topology
  - maths/category
  - concepts
aliases:
  - bord
  - bordism
  - bords
---

> [!definition|*]- Bordism Category $\left( \text{Bord}_{d} \right)$
> We require the following for this category.
> - The objects of this [[Categories|category]] are closed, [[Surfaces|orientable]], [[Categories|smooth]] $(d-1)$-dimensional [[manifolds]].
> - The morphism of this category, $M:\Sigma_{in}\to\Sigma_{out}$, are compact, orientable, smooth $d$-dimensional manifolds, where $\Sigma_{in}$ and $\Sigma_{out}$ are objects of the bordism. The morphisms boundaries (notated with $\partial M$) satisfy the following properties:
> 	- $\partial M=\partial_{in}M\sqcup\partial_{out}M$
> 	- $f:\partial_{in}M\to \Sigma_{in}$ and $g:\partial_{out}M\to \Sigma_{out}$ where both respects orientation and are diffeomorphic
> 	-  An equivalence between $M,f,g$ and $M',f',g'$ if there exists $\phi:M\to M'$ where $f'\circ(\phi|_{\partial_{in}M})=f$ and $g'\circ(\phi|_{\partial_{out}M})=g$. More simply morphisms are equivalent if there is a way to smoothly shift from one to another (this naturally implies incoming and out coming boundaries are also equivalent).
> - Composition of morphisms, $M_{1}:\Sigma_{1}\to\Sigma_{2}$ and $M_{2}:\Sigma_{2}\to\Sigma_{3}$, follows as expected when their corresponding boundaries are equivalent and glued, $M_{2} \circ M_{1}: \Sigma_{1}\to\Sigma_{3}$:
> - An identity morphism for any $\Sigma$, is a cylinder, $id_{\Sigma}:\Sigma\to\Sigma$.
> - The tensor product category is the disjoint union $\sqcup$ and the unit object on the tensor product is the empty $\varnothing$ $(d-1)$-dimensional manifold.
 ^def-cat-bord

> [!definition|*]- Spin Bordism Category $\left( \text{Bord}_{d}^{\text{Spin}} \right)$
> We require:
> - The objects of this [[Categories|category]] are closed, [[Surfaces|orientable]], smooth $(d-1)$-dimensional [[manifolds]] equipped with spin structures. They will be represented as pairs $(\Sigma,s)$.
> - The morphism of this category, $M:(\Sigma_{in},s_{in})\to(\Sigma_{out},s_{out})$, are compact, orientable, smooth $d$-dimensional manifolds, where $(\Sigma_{in},s_{in})$ and $(\Sigma_{out},s_{out})$ are objects of the bordism. The morphisms boundaries (notated with $\partial M$) satisfy the following properties:
> 	- $\partial M=\partial_{in}M\sqcup\partial_{out}M$
> 	- $f:\partial_{in}M\to \Sigma_{in}$ and $g:\partial_{out}M\to \Sigma_{out}$ where both respects orientation and are diffeomorphic.
> 	- $M$, $f$ and $g$ define a bordism by themselves
> 	- $S$ is a spin structure on $M$ that is extended by $s_{in}$ and $s_{out}$ on the boundaries, $(S|_{\partial _{in}M})\cong f^{*}S$ and $(S|_{\partial _{out}M})\cong g^{*}S$
> 	-  An equivalence between the quadruple $(M,S,f,g)$ (a morphism with its spin structure and boundary diffeomorphisms) and $(M',S',f',g')$ if there exists $\phi:(M,S)\to (M',S')$ that is oriented and diffeomorphic and preserves the spin structure, ($\phi^{*}S'=S$) where $f'\circ(\phi|_{\partial_{in}M})=f$ and $g'\circ(\phi|_{\partial_{out}M})=g$, More simply morphisms are equivalent if there is a way to smoothly shift from one to another while preserving the spin structure (this naturally implies incoming and out coming boundaries are also equivalent).
> - Composition of morphisms, $M_{1}(:\Sigma_{1},s_{1})\to(\Sigma_{2},s_{2})$ and $M_{2}:(\Sigma_{2},s_{2})\to(\Sigma_{3},s_{3})$, follows as expected when their corresponding boundaries are equivalent and glued, $M_{2} \circ M_{1}: (\Sigma_{1},s_{1})\to(\Sigma_{3},s_{3})$:
> - An identity morphism for any $(\Sigma,s)$, is a cylinder, $id_{\Sigma}:(\Sigma,s)\to(\Sigma,s)$.
> - The tensor product is the disjoint union $\sqcup$ and the unit object on the tensor product is the empty $\varnothing$ $(d-1)$-dimensional manifold.
 ^def-cat-spin-bord