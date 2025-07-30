---
tags:
  - maths
  - maths/topology
  - maths/category
aliases:
  - bord
  - bordism
  - bords
---
> [!definition|*]- Bordism [[Categories|Category]] $(\text{Bord}_{d})$
> As a [[Categories|category]] this will naturally need objects, [[morphisms]], composition of [[morphisms]], associativity and finally an identity [[Morphisms|morphism]], but there are additional properties which are the following:
> - The objects of this [[Categories|category]] are closed, [[Surfaces|orientable]], [[Categories|smooth]] $(d-1)$-dimensional [[manifolds]]. Let $\Sigma_{1},\Sigma_{2}$ be two distinct objects of this [[Categories|category]], being outgoing and incoming respectively.
> - The [[morphisms]] of this [[Categories|category]] are $d$-dimensional [[manifolds]] $M$
> 	- The boundaries $\partial M$ is composed of $\partial_{in} M$ and $\partial_{out}M$ which are disjoint $(\partial M=\partial_{in} M\sqcup\partial_{out}M)$ which is the [[Functors|tensor product]] of $\text{Bord}_{d}$
> 	- The 2 boundaries are [[Morphisms|diffeomorphic]] to $\Sigma_{1}$ and $\Sigma_{2}$, $f: \partial_{in} M\to \Sigma_{1}$ and $g:\partial_{out}M\to\Sigma_{2}$. Overall we may compose and simply write as such $g^{-1}\circ f=M:\Sigma_{1}\to\Sigma_{2}$.
 ^def-cat-bord