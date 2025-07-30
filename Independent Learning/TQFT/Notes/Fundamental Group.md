---
tags:
  - maths

  - maths/topology
---

> [!definition|*]- Fundamental Group 
> Let $S$ be a [[Surfaces|surface]], and let $z ∈ S$ be the base point. Let $\Gamma = \{γ : [0, 1] → S : γ(0) = γ(1) = z\}$ (i.e. closed curves with $z$ as the base point). Under concatenation $*,\Gamma$ forms a group. We define the fundamental group of $S$ based at $z$ to be $\pi_{1}(S, z) = \Gamma/\sim$.
 ^def-top-riem-fund-group

For the [[quotient space]] to be well defined we need $[\gamma]*[\mu]=[\gamma*\mu]$ and have that the null curve is the identity element, and the inverse element is simply the same curve traced in the opposite direction.

> [!theorem|*]- Fundamental Groups of a [[Connectedness|Connected]] Space are [[Equivalence|Equivalent]]
> If $S$ is a [[Connectedness|path-connected]] space, then for any $z_{0}, z_{1} ∈ S$, we have that $\pi_{1}(S, z_{0}) = \pi_{1}(S, z_{1})$. Hence, we shall write simply $\pi_{1}(S)$.
 ^thm-top-riem-fund-gro-conn-spa-equi

> [!definition|*]- Covering Space
> Let $S$ be a space. A covering space is a [[Connectedness|connected]] [[Surfaces|surface]] $\tilde{S}$ with a projection map $p : \tilde{S} → S$ such that $p$ is continuous and surjective, and for every point $x ∈ S$, there exists an open [[Neighbourhoods|neighbourhood]] $U$ of $x$ with $\pi ^{-1}(U )$ being a union of disjoint open sets in $\tilde{S}$. Such a [[Neighbourhoods|neighbourhood]] is called evenly covered. On each of these disjoint open sets, $p$ is a [[Morphisms|homomorphism]] (so we say that the spaces are locally [[Morphisms|homomorphic]]).
 ^def-top-cov-spa

> [!definition|*]- Lift
> Let p : $\tilde{S} → S$ be a cover, and let $γ : [0, 1] → S$ be a curve in $S$. Then a lift of $γ$ is a function $\tilde{\gamma} : [0, 1] → \tilde{S}$ such that $γ = p ◦ \tilde{\gamma}$ If, for any curve $γ : [0, 1] → S$ and any $x ∈ \tilde{S}$ with $p(x) = γ(0)$, there exists a lift of $γ$ to $\tilde{S}$ with initial point $x$, then we say the covering [[Surfaces|surface]] is regular.
 ^def-top-lift

