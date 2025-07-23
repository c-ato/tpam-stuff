---
tags:
  - maths
  - physics
  - topology
  - quantum
  - category
aliases:
  - TQFTs
  - tqft
  - tqfts
  - TFT
  - tfts
---
> [!definition|*]- TQFT
> This is a symmetric [[Monoidal Category|monoidal]] [[Functors|functor]] between a [[Bordisms|bord]] and vector space $Z:\text{Bord}_{d}\to\text{Vect}_{k}$. It will naturally have the properties of a [[Functors|functor]]:
> - The objects of $\text{Bord}_{d}$, $\Sigma$, of $(d-1)$-dimensions are mapped to a $k$-vector space $Z(\Sigma)\implies Vect_{k}$
> - It also implies the empty manifold maps to the base field $k$, $Z(\varnothing)=k$ (each respectively the unit object,)
> - The $d$-dimension [[morphisms]], $M:\Sigma_{0}\to\Sigma_{1}$, map to $k$-linear maps, $Z(M):Z(\Sigma_{0})\to Z(\Sigma_{1})$. We can then call $Z(M)$ a transition operator (much in the same vein as transition maps of Riemann surfaces)
> - The linear map of a composition of [[morphisms]] is the same as the composition of linear maps of [[morphisms]], $Z(M_{1}\circ M_{2})=Z(M_{1})\circ Z(M_{2})$
> - $Z(I_{\Sigma})=I_{Z(\Sigma)}$
> - The map of disjoint unions of $\Sigma$ and $M$ are [[Morphisms|isomorphic]] to the [[Functors|tensor product]] of the maps of each disjoint $\Sigma$ and $M$ respectively, $Z(\Sigma_{1}​\sqcup\Sigma_{2}​)\simeq Z(\Sigma_{1}​)\otimes Z(\Sigma_{2}​)$ and $Z(M_{1}​\sqcup M_{2}​)\simeq Z(M_{1}​)\otimes Z(M_{2}​)$
> - It respects symmetry (commutations of the [[Functors|tensor products]]) as seen in the diagram of the definition of symmetric [[Monoidal Category|monoidal]] [[Functors|functor]].
 ^def-cat-tqft