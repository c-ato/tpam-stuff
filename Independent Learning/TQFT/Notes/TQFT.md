---
tags:
  - concepts
  - maths/topology
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
> This is a symmetric [[Monoidal Category|monoidal]] [[Functors|functor]] between a [[Bordisms|bord]] and vector space $Z:\text{Bord}_{n}\to\text{Vect}_{k}$. It will naturally have the properties of a [[Functors|functor]]:
> - The objects of $\text{Bord}_{n}$, $\Sigma$, of $(n-1)$-dimensions are mapped to a $k$-vector space $Z(\Sigma)\implies Vect_{k}$
> - It also implies the empty [[Manifolds|manifold]] maps to the base field $k$, $Z(\varnothing)=k$ (each respectively the unit object,)
> - The $n$-dimension [[morphisms]], $M:\Sigma_{0}\to\Sigma_{1}$, map to $k$-linear maps, $Z(M):Z(\Sigma_{0})\to Z(\Sigma_{1})$. We can then call $Z(M)$ a transition operator (much in the same vein as [[Riemann Surface|transition maps]] of [[Riemann Surface|Riemann surfaces]])
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
> - The objects of $\text{Bord}^{\text{Spin}}_{n}$ are pairs $(\Sigma,s)$, where $s$ is one of the aforementioned spin structures, and $\Sigma$ 


> [!definition|*]- Spin TQFT (sTQFT)
> This is much like a TQFT that it is a functor, albeit from the category of spin bordisms to super vector spaces, $Z:Bord_{n}^{spin}\to sVect_{k}$.
> These will have two distinct spin structures: 
> - Neveu-Schwarz, a loop in the spin bundle for its spin structure, $s_{NS}$, which is periodic, $Z(\Sigma,s_{NS})=A_{\bar{0}}$, this is also denoted as $A_{NS}$ sometimes.
> - Ramond, a path in the spin bundle of its spin structure that results in a sign change, $s_{R}$, which is anti-periodic, $Z(\Sigma,s_{R})=A_{\bar{1}}$, this is also denoted as $A_{R}$ sometimes.
> 
> The functor maps to a graded vector space. It is then easily seen how sTQFTs are equivalent to a sFA where the total state space can be constructed as, $A=A_{NS}\oplus A_{R}$, where specifically $A_{NS}$ behaves equivalently to $A_{\bar{0}}$ and $A_{R}$ to $A_{\bar{1}}$.
> Additionally the functor, $Z$, fulfils the following properties and respects the grading.
> - The objects of $\text{Bord}_{n}^{\text{Spin}}$, $(\Sigma,s)$, of $(n-1)$-dimensions are mapped to a super vector space that respects the grading $Z(\Sigma,s)\to sVect_{k}$
> - It also implies the empty [[Manifolds|manifold]] maps to the base field $k$, $Z(\varnothing)=k$ (each respectively the unit object,) where $k \in A_{\bar{0}}$
> - The $n$-dimension [[morphisms]], $M:(\Sigma_{in},s_{in})\to(\Sigma_{out},s_{out})$, map to a super linear map, $Z(M):Z(\Sigma_{in},s_{in})\to Z(\Sigma_{out},s_{out})$. We can then call $Z(M)$ a transition operator 
> - The linear map of a composition of [[morphisms]] is the same as the composition of linear maps of [[morphisms]], $Z(M_{1}\circ M_{2})=Z(M_{1})\circ Z(M_{2})$
> - $Z(I_{(\Sigma,s)})=I_{Z(\Sigma,s)}$ where $I_{Z(\Sigma,s)}\in A_{\bar{0}}$
> - The map of disjoint unions of $(\Sigma,s)$ and $M$ are [[Morphisms|isomorphic]] to the super [[Functors|tensor product]] of the maps of each disjoint $\Sigma$ and $M$ respectively, $Z((\Sigma_{1}​,s_{1})\sqcup(\Sigma_{2},s_{2})​)\simeq Z(\Sigma_{1}​,s_{1})\otimes_{s} Z(\Sigma_{2}​,s_{2})$ and $Z(M_{1}​\sqcup M_{2}​)\simeq Z(M_{1}​)\otimes_{s} Z(M_{2}​)$
> - It respects supersymmetry of the super tensor product
 ^def-cat-stqft
 