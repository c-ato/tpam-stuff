---
tags:
  - maths
  - maths/topology
aliases:
  - covering space
  - cover
  - double cover
  - covers
  - double covers
  - lift
  - lifting
---

> [!definition|*]- Fundamental Group 
> Let $S$ be a [[Surfaces|surface]], and let $z ∈ S$ be the base point. Let $\Gamma = \{γ : [0, 1] → S : γ(0) = γ(1) = z\}$ (i.e. closed [[Homotogy|curves]] with $z$ as the base point). Under concatenation $*,\Gamma$ forms a group. We define the fundamental group of $S$ based at $z$ to be $\pi_{1}(S, z) = \Gamma/\sim$.
 ^def-top-riem-fund-group

For the [[quotient space]] to be well defined we need $[\gamma]*[\mu]=[\gamma*\mu]$ and have that the null [[Homotogy|curve]] is the identity element, and the inverse element is simply the same [[Homotogy|curve]] traced in the opposite direction.

> [!theorem|*]- Fundamental Groups of a [[Connectedness|Connected]] Space are [[Equivalence|Equivalent]]
> If $S$ is a [[Connectedness|path-connected]] space, then for any $z_{0}, z_{1} ∈ S$, we have that $\pi_{1}(S, z_{0}) = \pi_{1}(S, z_{1})$. Hence, we shall write simply $\pi_{1}(S)$.
 ^thm-top-riem-fund-gro-conn-spa-equi

> [!definition|*]- Covering Space
> Let $S$ be a space. A covering space is a [[Connectedness|connected]] [[Surfaces|surface]] $\tilde{S}$ with a [[Product space|projection]] map $p : \tilde{S} → S$ such that $p$ is continuous and surjective. It also requires for every $x ∈ S$, for there exists an open [[Neighbourhoods|neighbourhood]] $U$, and $\pi ^{-1}(U )$ to be a union of disjoint open sets in $\tilde{S}$. Such a [[Neighbourhoods|neighbourhood]], $U$, is then called evenly covered. 
> 
> On each of these disjoint open sets, $p$ is a [[Morphisms|homomorphism]] (so we say that the spaces are locally [[Morphisms|homomorphic]]).
 ^def-top-cov-spa

> [!definition|*]- Double Coverings Spaces
> A double cover is a specific type of covering map, where for every point $x \in S$, there are exactly 2 points $y \in \tilde{S}$ that map to $x$ under $p$. 
 ^def-top-doub-cov-spa

> [!definition|*]- Universally Covering Group
> Let $p:\tilde{X}\to X$ be a [[Connectedness|simply connected]] cover. If $\beta\varepsilon\to X$ is another [[Connectedness|simply connected]] covering, then there exists a uniquely determined homeomorphism $\alpha:\tilde{X}\to E$
 ^def-top-uni-cov-group

> [!definition|*]- Lift
> Let p : $\tilde{S} → S$ be a cover, and let $γ : [0, 1] → S$ be a [[Homotogy|curve]] in $S$. Then a lift of $γ$ is a function $\tilde{\gamma} : [0, 1] → \tilde{S}$ such that $γ = p ◦ \tilde{\gamma}$ If, for any [[Homotogy|curve]] $γ : [0, 1] → S$ and any $x ∈ \tilde{S}$ with $p(x) = γ(0)$, there exists a lift of $γ$ to $\tilde{S}$ with initial point $x$, then we say the covering [[Surfaces|surface]] is regular.
 ^def-top-lift
