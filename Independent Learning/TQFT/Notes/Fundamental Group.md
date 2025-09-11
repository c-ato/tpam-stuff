---
tags:
  - maths/topology
  - concepts
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
> Let $S$ be a space, and let $z ∈ S$ be the base point. Let $\Gamma = \{γ : [0, 1] → S : γ(0) = γ(1) = z\}$ (i.e. closed [[Homotogy|curves]] with $z$ as the base point). Under concatenation $*,\Gamma$ forms a group. We define the fundamental group of $S$ based at $z$ to be $\pi_{1}(S, z) = \Gamma/\sim$, which is the group formed on the quotient space of the set of all homotopy classes of loops based at $z$.
 ^def-top-riem-fund-group

For the [[quotient space]] to be well defined we need $[\gamma]*[\mu]=[\gamma*\mu]$ and have that the null [[Homotogy|curve]] is the identity element, and the inverse element is simply the same [[Homotogy|curve]] traced in the opposite direction.

> [!theorem|*]- Fundamental Groups of a [[Connectedness|Connected]] Space are [[Equivalence|Equivalent]]
> If $S$ is a [[Connectedness|path-connected]] space, then for any $z_{0}, z_{1} ∈ S$, we have that $\pi_{1}(S, z_{0}) \cong \pi_{1}(S, z_{1})$. Hence, we shall write simply $\pi_{1}(S)$.
 ^thm-top-riem-fund-gro-conn-spa-equi

> [!definition|*]- Covering Space
> Let $S$ be a space. A covering space is a [[Connectedness|connected]] space $\tilde{S}$ with a [[Product space|projection]] map $p : \tilde{S} → S$ such that $p$ is continuous and surjective. It also requires for every $x ∈ S$, for there exists an open [[Neighbourhoods|neighbourhood]] $U$, and $p ^{-1}(U )$ to be a union of disjoint open sets in $\tilde{S}$. Such a [[Neighbourhoods|neighbourhood]], $U$, is then called evenly covered. 
> 
> On each of these disjoint open sets, $p$ is a [[Morphisms|homomorphism]] (so we say that the spaces are locally [[Morphisms|homomorphic]]).
 ^def-top-cov-spa

> [!definition|*]- Double Coverings Spaces
> A double cover is a specific type of covering map, where for every point $x \in S$, there are exactly 2 points $y \in \tilde{S}$ that map to $x$ under $p$. 
 ^def-top-doub-cov-spa

> [!definition|*]- Universally Covering Space
> A universal cover of $X$ is defined as a simply connected covering space,  $p:\tilde{X}\to X$. If $p_{1}: \tilde{X}_{1}\to X$ and $p_{2}: \tilde{X}_{2}\to X$ are two universally covering spaces, then there exists a uniquely determined homomorphism $\alpha:\tilde{X}_{1}\to \tilde{X}_{2}$ such that $p_{1}=p_{2} \circ \alpha$
 ^def-top-uni-cov-group

> [!definition|*]- Lift
> Let $p:\tilde{S} → S$ be a cover, and let $γ : [0, 1] → S$ be a [[Homotogy|curve]] in $S$. Then a lift of $γ$ is a function $\tilde{\gamma} : [0, 1] → \tilde{S}$ such that $γ = p ◦ \tilde{\gamma}$.
 ^def-top-lift

> [!theorem|*]- Path Lifting
> For any $\tilde{\gamma}:[0,1]\to \tilde{S}$ and any point $\tilde{x}_{0}\in \tilde{S}$ such that $p(\tilde{x}_{0})=\gamma(0)$, there exists a unique lift $\tilde{\gamma}$ of $\gamma$ to $\tilde{S}$ with initial point $\tilde{\gamma}(0)=\tilde{x}_{0}$.
 ^thm-top-path-lift