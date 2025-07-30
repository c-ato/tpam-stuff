---
tags:
  - maths
  - maths/topology
  - maths/category
aliases:
  - monoidal
  - monoid
  - monoids
---

> [!definition|*]- (Symmetric) Monoidal [[Categories|Category]]
> Once again, as a [[Categories|category]] it will naturally require objects, [[morphisms]] between them, along with [[Morphisms|morphism]] composition and an identity [[Morphisms|morphism]]. It will also need the additional structures of:
> - A [[Functors|tensor product]] 
> - A unit object that acts as an identity for the [[Functors|tensor product]]
> - Associativity [[Morphisms|isomorphism]], for $A,B,C$ of a [[Categories|category]] satisfies $(A\otimes B)\otimes C$ is [[Morphisms|isomorphic]] with $A\otimes (B\otimes C)$ 
> - Identity [[Morphisms|isomorphism]], for $λ_{A}​:I⊗A≅A$ and $ρ_{A}​:A⊗I≅A$
>
> This makes for a monoidal [[Categories|category]], but additional properties are required for it to be symmetric. A symmetry [[Morphisms|isomorphism]] $\sigma_{x,y}:x \otimes y\to y\otimes x$, $F:A\to A'$ and $G:B\to B'$ satisfies the following:
> $$\begin{array}{ccc}A \otimes B & \xrightarrow{\sigma_{A,B}} & B \otimes A \\\downarrow F\otimes G & & \downarrow G\otimes F \\ A' \otimes B' & \xrightarrow{\sigma_{A',B'}} & B' \otimes  A' \end{array}$$
 ^def-cat-monoid

> [!definition|*]- Symmetric Monoidal [[Functors|Functor]]
> Let $A,B$ be objects of $\mathcal{C}$, a [[Functors|functor]] $F: \mathcal{C}\to \mathcal{D}$, a coherence [[Morphisms|isomorphism]] ("decomposer") $\psi_{A,B}:F(A \otimes_{\mathcal{C}}B)\to F(A)\otimes_{\mathcal{D}}F(B)$ and finally where $\otimes_{\mathcal{E}}$ is the [[Functors|tensor product]] of a given [[Categories|category]] $\mathcal{E}$.
> 
> A symmetric monoidal [[Functors|functor]] satisfies the following:
> $$\begin{array}{ccc}F(A \otimes_\mathcal{C} B) & \xrightarrow{F(\sigma_{A,B})} & F(B \otimes_\mathcal{C} A) \\\downarrow \psi_{A,B} & & \downarrow \psi_{B,A} \\F(A) \otimes_\mathcal{D} F(B) & \xrightarrow{\sigma_{F(A),F(B)}} & F(B) \otimes_\mathcal{D} F(A)\end{array}$$
 ^def-cat-sym-monoi-funct
