---
Note number: 5
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf
Title Stem: Topology
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%20
tags:
  - maths
  - physics
  - topology
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%206" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=27" class="button">Go to PDF Page 27
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%204" class="button">Previous
	</a> 
</div>

Interesting points, kinda relevant to TQFT aspect as well:
- $\mathbb{R}^{2}=\mathbb{R}\times \mathbb{R}$
- $Cyl=S^{1}\times I$ where $I\in z$ and $S^{1}\in(x,y)$
- $Tor=S^{1}\times S^{1}$

> [!definition|*]- Product space
> Let $X,Y$ be arbitrary spaces. A new space can be created by the "product" of these spaces, denoted as $X\times Y$, where $x \in X,y \in Y$ such that $(x,y)\in X\times Y$.
 ^def-top-prod-spa

> [!definition|*]- Projection
> The projection of $X$ in a product topology is defined as $p_{X}: X\times Y\to X$ or point wise as $p_{X}(x,y)=x$
 ^def-top-proj

> [!theorem|*]- Projection Properties of Product Topology
> When $X × Y$ is equipped with the product topology, the projections $p_{X}$ and $p_{Y}$ are continuous functions and are open maps. In addition, the product topology on $X × Y$ is the smallest topology for which the projections are continuous.
 ^thm-top-proj-prod-top

> [!theorem|*]- Composite Function with Projection is Continuous 
> The function $f : Z → X × Y$ is continuous if and only if the composite functions $p_{X} \circ f : Z → X$ and $p_{Y}\circ f : Z → Y$ are continuous.
 ^thm-top-comp-func-proj-contin

![[0. Topology Notes (pre project).pdf#page=29&rect=137,482,460,737|0. Topology Notes (pre project), p.29]]

> [!theorem|*]- Properties of Product Space
> - The product space $X\times Y$ is a Hausdorff space $\iff X\land Y$ are Hausdorff.
> - The product space $X\times Y$ is compact $\iff X\land Y$ are compact.
> - If $X\land Y$ are connected $\implies$ $X\times Y$ is also connected.
 ^thm-top-prop-prod-spa

> [!definition|*]- Partition
> Let $X$ be a topological space such that there exists a family, $\mathcal{P}$, of disjoint non-empty subsets of $X$ satisfying $\bigcup P=X$. Any $P\in\mathcal{P}$ is then defined as a partition of $X$
 ^def-top-part

> [!definition|*]- Identification Space
> Let $X,Y$ be a topological space where points of $Y$ are a subset of $\mathcal{P}$ being the family of partitions, and $\pi: X\to Y$. The topology of $Y$ is the largest when $\pi$ is continuous $\therefore O \subseteq Y$ is open $\iff \pi ^{-1}(O)$ is open in $X$. This topology is called the identification topology on $Y$.
> We call $Y$ an identification space, because all points in $X$ that are sent to the same subset of $Y$ have become the same point.
 ^def-top-ident-spa

![[0. Topology Notes (pre project).pdf#page=30&rect=70,350,475,550|0. Topology Notes (pre project), p.30]]

> [!remark|*]- Set Partition
> A way to make a partition on a set is to define an [[Topology note 2#^lem-top-homo-equiv|equivilance relation]]on the set. 
 ^rmk-top-set-partit

