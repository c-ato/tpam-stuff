---
tags:
  - maths
  - physics
  - maths/topology
  - quantum
  - maths/category
aliases:
  - TQFTs
  - tqft
  - tqfts
  - TFT
  - tfts
  - spin tqft
  - stqft
---
> [!definition|*]- Topological Quantum Field Theory (TQFT)
> This is a symmetric [[Monoidal Category|monoidal]] [[Functors|functor]] between a [[Bordisms|bord]] and vector space $Z:\text{Bord}_{d}\to\text{Vect}_{k}$. It will naturally have the properties of a [[Functors|functor]]:
> - The objects of $\text{Bord}_{d}$, $\Sigma$, of $(d-1)$-dimensions are mapped to a $k$-vector space $Z(\Sigma)\implies Vect_{k}$
> - It also implies the empty [[Manifolds|manifold]] maps to the base field $k$, $Z(\varnothing)=k$ (each respectively the unit object,)
> - The $d$-dimension [[morphisms]], $M:\Sigma_{0}\to\Sigma_{1}$, map to $k$-linear maps, $Z(M):Z(\Sigma_{0})\to Z(\Sigma_{1})$. We can then call $Z(M)$ a transition operator (much in the same vein as [[Riemann Surface|transition maps]] of [[Riemann Surface|Riemann surfaces]])
> - The linear map of a composition of [[morphisms]] is the same as the composition of linear maps of [[morphisms]], $Z(M_{1}\circ M_{2})=Z(M_{1})\circ Z(M_{2})$
> - $Z(I_{\Sigma})=I_{Z(\Sigma)}$
> - The map of disjoint unions of $\Sigma$ and $M$ are [[Morphisms|isomorphic]] to the [[Functors|tensor product]] of the maps of each disjoint $\Sigma$ and $M$ respectively, $Z(\Sigma_{1}​\sqcup\Sigma_{2}​)\simeq Z(\Sigma_{1}​)\otimes Z(\Sigma_{2}​)$ and $Z(M_{1}​\sqcup M_{2}​)\simeq Z(M_{1}​)\otimes Z(M_{2}​)$
> - It respects symmetry (commutations of the [[Functors|tensor products]]) as seen in the diagram of the definition of symmetric [[Monoidal Category|monoidal]] [[Functors|functor]].
 ^def-cat-tqft

> [!definition|*]- $2$D Spin TQFT ($2$D-sTQFT)
> This is a symmetric [[Monoidal Category|monoidal]] [[Functors|functor]] between a spin [[Bordisms|bordism]] and super vector space $Z:\text{Bord}^{\text{Spin}}_{2 }\to\text{sVect}_{k}$. 
> The bordism will have two distinct spin structures:
> - Neveu-Schwarz, a loop in the spin bundle for its spin structure $s_{NS}$, which is perioidic
> - Ramond, a path in the spin bundle of its spin structure that results in a sign change, $s_{R}$, which is anti-periodic
> It will naturally have the properties of a [[Functors|functor]], while also respect the grading of the super vector space using the aforementioned spin structures:
> - The objects of $\text{Bord}^{\text{Spin}}_{d}$ are pairs $(\Sigma,s)$, where $s$ is one of the aforementioned spin structures, and $\Sigma$ 


> [!definition|*]- $2$D Spin TQFT ($2$D-sTQFT)
> This is much like a TQFT that it is a functor, albeit from the category of spin bordisms to super vector spaces, $Z:Bord_{2}^{spin}\to sVect_{k}$. Specifically the spin bordism's manifold is equipped with a spin structure, $s$, and will be described as a pair, $(\Sigma,s)$ where $\Sigma$ is an object of the $Bord_{2}$ category like $S_{1}$.
> These will have two distinct spin structures: Neveu-Schwarz, a loop in the spin bundle for its spin structure $s_{NS}$, which is perioidic; Ramond, a path in the spin bundle of its spin structure that results in a sign change, $s_{R}$, which is anti-periodic.
> $$Z(\Sigma,s_{NS})=A_{NS}\qquad Z(\Sigma,S_{R})=A_{R}$$
> Unlike in regular TQFTs we can no longer describe the state spaces through a single vector space, but with a pair, as shown above. This easily lends itself to the structure that a super vector space has, $A=A_{NS}+A_{R}$, where $A_{NS}$ behaves equivalently to $A_{\bar{0}}$ and $A_{R}$ to $A_{\bar{1}}$.
 ^def-cat-stqft
 