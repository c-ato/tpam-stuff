---
tags:
  - maths
  - maths/topology
aliases:
  - product spaces
  - projection
  - projections
  - project
  - projected
---

> [!definition|*]- Product space
> Let $X,Y$ be arbitrary spaces. A new space can be created by the "product" of these spaces, denoted as $X\times Y$, where $x \in X,y \in Y$ such that $(x,y)\in X\times Y$.
 ^def-top-prod-spa

> [!definition|*]- Projection
> The projection of $X$ in a product [[topology]] is defined as $p_{X}: X\times Y\to X$ or point wise as $p_{X}(x,y)=x$
 ^def-top-proj

> [!theorem|*]- Projection Properties of Product [[Topology]]
> When $X × Y$ is equipped with the product [[topology]], the projections $p_{X}$ and $p_{Y}$ are continuous functions and are open maps. In addition, the product [[topology]] on $X × Y$ is the smallest [[topology]] for which the projections are continuous.
 ^thm-top-proj-prod-top

> [!theorem|*]- Composite Function with Projection is Continuous 
> The function $f : Z → X × Y$ is continuous if and only if the composite functions $p_{X} \circ f : Z → X$ and $p_{Y}\circ f : Z → Y$ are continuous.
 ^thm-top-comp-func-proj-contin

![[0. Topology Notes (pre project).pdf#page=29&rect=137,482,460,737|0. Topology Notes (pre project), p.29]]

> [!theorem|*]- Properties of Product Space
> - The product space $X\times Y$ is a [[Hausdorff]] space $\iff X\land Y$ are [[Hausdorff]].
> - The product space $X\times Y$ is [[Compactness|compact]] $\iff X\land Y$ are [[Compactness|compact]].
> - If $X\land Y$ are [[Connectedness|connected]] $\implies$ $X\times Y$ is also [[Connectedness|connected]].
 ^thm-top-prop-prod-spa
 
> [!definition|*]- Basis of Product Space [[Topology]]
> The base, $\beta$ of a product space [[topology]] $X\times Y$ is all sets $U\times V$ where $U$ is an open set $\in X$ and $V$ is an open set $\in Y$. 
 ^def-top-prod-spa-base

![[0. Topology Notes (pre project).pdf#page=46&rect=182,302,411,533|0. Topology Notes (pre project), p.46]]