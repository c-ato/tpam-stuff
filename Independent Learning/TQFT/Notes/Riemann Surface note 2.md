---
Note number: 2
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F1.%20Riemann%20Surfaces%20(recommended).pdf
Title Stem: Riemann Surface
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FRiemann%20Surface%20note%20
tags:
  - maths
  - physics
  - topology
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FRiemann%20Surface%20note%203" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F1.%20Riemann%20Surfaces%20(recommended).pdf#page=6" class="button">Go to PDF Page 6
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FRiemann%20Surface%20note%201" class="button">Previous
	</a> 
</div>

> [!theorem|*]- Fundamental Groups of a Connected Space are Equivalent
> If $S$ is a path-connected space, then for any $z_{0}, z_{1} ∈ S$, we have that $\pi_{1}(S, z_{0}) = \pi_{1}(S, z_{1})$. Hence, we shall write simply $\pi_{1}(S)$.
 ^thm-top-riem-fund-gro-conn-spa-equi

> [!definition|*]- Covering Space
> Let $S$ be a space. A covering space is a connected surface $\tilde{S}$ with a projection map $p : \tilde{S} → S$ such that $p$ is continuous and surjective, and for every point $x ∈ S$, there exists an open neighbourhood $U$ of $x$ with $\pi ^{-1}(U )$ being a union of disjoint open sets in $\tilde{S}$. Such a neighbourhood is called evenly covered. On each of these disjoint open sets, $p$ is a homeomorphism (so we say that the spaces are locally homomorphic).
 ^def-top-cov-spa

> [!definition|*]- Lift
> Let p : $\tilde{S} → S$ be a cover, and let $γ : [0, 1] → S$ be a curve in $S$. Then a lift of $γ$ is a function $\tilde{\gamma} : [0, 1] → \tilde{S}$ such that $γ = p ◦ \tilde{\gamma}$ If, for any curve $γ : [0, 1] → S$ and any $x ∈ \tilde{S}$ with $p(x) = γ(0)$, there exists a lift of $γ$ to $\tilde{S}$ with initial point $x$, then we say the covering surface is regular.
 ^def-top-lift

