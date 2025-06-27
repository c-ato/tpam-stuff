---
Note number: 6
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
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%207" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=34" class="button">Go to PDF Page 34
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%205" class="button">Previous
	</a> 
</div>

> [!definition|*]- Group Action
> If $G$ is a group and $X$ is a set or topological space, then the group action $G\times X\to X$ is given by $g,x\mapsto g\cdot x$. They must also satisfy:
> - The group action behaves well to composition: $(gh)\cdot x=g(h\cdot x)\forall g,h\in G,x \in X$.
> - The group action posses an identity action: $e\cdot x=x\forall x \in X$
 ^def-vgla-group-action

> [!definition|*]- Orbits and Quotient Space
> The effect of the group action is therefore to partition a space into orbits, which are sets of points that can be connected by elements of the group. That is, the points $x, y\in X$, a topological space, are in the same orbit if there is some $g ∈ G$, a group, such that $g · x = y$. Each orbit is therefore an equivalence class under the group operation, and the space of such orbits is called a quotient space.
 ^def-top-orb-quot-spa

![[0. Topology Notes (pre project).pdf#page=36&rect=61,218,536,601|0. Topology Notes (pre project), p.36]]

> [!definition|*]- Open Cover
> Let $X$ be a topological space, an open cover is then a family of open subsets of $X$ whom union is $X$. 
 ^def-top-open-cov

> [!definition|*]- Subcover
> If $\mathcal{F}$ is an open cover of $X$ and $\mathcal{F}'$ is a subfamily of $\mathcal{F}$ and $\bigcup \mathcal{F'}=X$, then $\mathcal{F'}$ is called a subcover of $X$
 ^def-top-subcov

![[0. Topology Notes (pre project).pdf#page=38&rect=178,507,420,701|0. Topology Notes (pre project), p.38]]
Union of purple and yellow is the open cover $\mathcal{F}$ and purple is subcover $\mathcal{F'}$

> [!example|*]- Open cover with no subcover $(\mathbb{R}^{2})$
> Let $\mathcal{F}$ be the set of open balls (circles) of $r=1$ who's centres have integer coordinates, $\mathcal{F}:=\{ (x+n,y+m)|x^{2}+y^{2}\leq 1|n,m\in \mathbb{Z} \}$. This family covers the plane, but if a single ball is removed the family no long covers the entire space and hence this famaily has no proper subcovers.
 ^exm-top-open-cov-no-subcov

![[Topology note 4#^def-top-comp]] 

> [!theorem|*]- Generalised Heine-Borel Theorem
> In $\mathbb{R}^{n}$ with Euclidean topology, compact sets are precisely the closed and bounded sets of $\mathbb{R}^{n}$
 ^thm-top-gen-hb


![[Topology note 3#^def-top-hausdorff]] 