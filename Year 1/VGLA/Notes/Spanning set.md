---
tags:
  - maths/vectors
  - concepts
aliases:
---

> [!definition|*]- Spanning set
> If $u_{1}, u_{2},\dots, u_{k} ∈ V$, with $V$ a vector space over $\mathbb{F}$, then the subset of $V$ consisting of all possible linear combination of $u_{1}, u_{2},\dots, u_{k}$ is called their span and is denoted
> $$\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}=\{ \lambda_{1}\mathbf{u}_{1}+\lambda_{2} \mathbf{u}_{2}+\dots+\lambda_{k}\mathbf{u}_{k}|\lambda_{1},\lambda_{2},\dots,\lambda_{k} \in \mathbb{F} \}$$
> If $U=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, then we say that $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$ is a spanning set for $U$ or that $\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$ spans $U$
 ^def-vgla-spanning-set

> [!theorem|*]- Spanning set is a subspace
> Suppose that $U=\text{span}\{ \mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \}$, where for a vector space $V$ over $\mathbb{F}$ we have $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \in V$. Then,
> - $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k} \in U$
> - $U$ is a subspace of $V$, and
> - $U$ is the smallest subspace of $V$ that contains $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k}$ in the sense that if $\tilde{U}$ is another subspace of $V$, which contains $\mathbf{u}_{1},\mathbf{u}_{2},\dots,\mathbf{u}_{k}$, then $U\subseteq \tilde{U}$
 ^thm-spanning-set-subspace
