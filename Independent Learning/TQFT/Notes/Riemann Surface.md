---
tags:
  - concepts
  - maths/topology
aliases:
  - riemann surfaces
  - atlas
  - chart
  - charts
  - transition map
  - transition maps
---

> [!definition|*]- Charts and Atlas
> The homeomorphisms of a [[Surfaces|surface]] are called charts, and the family they belong to is called an atlas $A$ on $S$. We write $A = \{(\phi_{\alpha}, U_{\alpha})\}$.
 ^def-top-chart-atlas

> [!definition|*]- Transition Maps
> If $U_{\alpha_{1}} ∩ U_{\alpha_{2}} \neq \varnothing$ then $\phi_{\alpha_{2}} ◦ \phi ^{-1} _{\alpha_{1}} : \phi(U_{\alpha_{1}} ) → \phi(U_{\alpha_{2}} )$ is, by composition, a [[Morphisms|homomorphism]]. Such a map is called a transition map
 ^def-top-trans

> [!definition|*]- Riemann [[Surfaces|Surface]]
> A Riemann surface $R$ is a [[Connectedness|connected]], [[Countable Spaces|second countable]], [[Hausdorff]] [[Topology|topological]] space with a family of [[Morphisms|homomorphisms]] $\phi_{\alpha} : U_{\alpha} → D_{\alpha}$ from domains $U_{\alpha}$ that form an [[Compactness|open cover]] of $S$ to open subsets $D_{\alpha}$ in the complex plane. 
> It also needs an atlas $A$, and if all transition maps determined by the atlas are [[Morphisms|holomorphic]], then $R$ is called a Riemann [[Surfaces|surface]]. 
 ^def-top-riem-surf

> [!definition|*]- Analytic Atlas
> The atlas of a Riemann [[Surfaces|Surface]] is an analytic atlas.
 ^def-top-riem-ana-atl

> [!theorem|*]- Conformally [[Equivalence|Equivalent]] Riemann [[Surfaces]]
>  if $R_{1}$ and $R_{2}$ are Riemann [[surfaces]] with a biholomorphic map $f$ between them (that is to say, a [[Morphisms|holomorphic]] map with a [[Morphisms|holomorphic]] inverse), we say that $R_{2}$ and $R_{2}$ are conformally [[Equivalence|equivalent]].
>  This is a means of classifying Riemann [[Surfaces]].
 ^thm-top-riem-conf-equiv

> [!proposition|*]- Conformal [[equivalence]] is an [[equivalence]] relation.
 ^prp-top-riem-conf-equiv

> [!definition|*]- Maximal Atlas
> If we have two [[Equivalence|equivalent]] atlases on a [[Surfaces|surface]] $S$, then their union is also an atlas on $S$ and belongs to the same [[equivalence]] class. By combining all atlases on $S$, we may obtain a maximal atlas on $S$.
 ^def-top-max-atl

> [!theorem|*]- Complex Subset is Riemann [[Surfaces|Surface]]
> Any open [[Connectedness|connected]] subset of the complex plane is a Riemann [[Surfaces|surface]].
 ^thm-top-riem-compl-sub-surf

> [!theorem|*]- Riemann [[Surfaces|Surface]] on [[Morphisms|Holomorphic]] [[Morphisms|Automorphism]]
> Let $R$ be a Riemann [[Surfaces|surface]], and let $G$ be a group of [[Morphisms|holomorphic]] [[Morphisms|automorphisms]] acting on $R$. Then $R/G$ under the quotient [[topology]] inherits a natural analytic atlas
 ^thm-top-riem-surf-holo-auto-anal-atl

