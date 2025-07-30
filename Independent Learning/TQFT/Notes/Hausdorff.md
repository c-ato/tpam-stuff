---
tags:
  - maths
  - maths/topology
aliases:
  - Hausdorffs
  - T1
  - T2
---

> [!definition|*]- Hausdorff $(T_{2})$
> A space is Hausdorff if every two distinct points, $x,y\in X$ have disjoint [[neighbourhoods]] - $\exists O_{x},O_{y}$, open sets, such that $x \in O_{x},y \in O_{y}$ and $O_{x}\cap O_{y}=\varnothing$.
 ^def-top-hausdorff

> [!definition|*]- $T_{1}$
> A [[Topology|topological]] space $X$ is $T_{2}$ if given any pair of distinct points $x, y ∈ X$, there exists an open set $O_{x}$ such that $x ∈ O_{x}$ but $y \notin O_{x}$. A 
 ^def-top-t1

> [!lemma|*]- All $T_{2}$ are $T_{1}$
> $T_{1}$ space is a looser condition than a Hausdorff space so all Hausdorff spaces are $T_{1}$
 ^lem-top-t1-t2

> [!theorem|*]- Points in $T_{1}$ are closed sets
> A [[Topology|topological]] space $X$ is $T_{1}\iff$ points in $X$ are closed sets.
 ^thm-top-t1-point-closed