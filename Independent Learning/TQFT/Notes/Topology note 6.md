---
Note number: 6
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf
Title Stem: Topology
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%20
tags:
  - maths
  - topology
  - physics
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

> [!theorem|*]- Real function defined in compact space
> A continuous, real-valued function defined on a compact space is bounded and attains its bounds.
 ^thm-top-re-funct-comp-spa-bound

> [!definition|*]- Basis of Product Space Topology
> The base, $\beta$ of a product space topology $X\times Y$ is all sets $U\times V$ where $U$ is an open set $\in X$ and $V$ is an open set $\in Y$. 
 ^def-top-prod-spa-base

![[0. Topology Notes (pre project).pdf#page=46&rect=182,302,411,533|0. Topology Notes (pre project), p.46]]

> [!theorem|*]- Metric spaces are Hausdorff
> If a topological space $(X, τ )$ is metrizable, then it is Hausdorff.
 ^thm-top-metri-haus

> [!definition|*]- $T_{1}$
> A topological space $X$ is $T_{2}$ if given any pair of distinct points $x, y ∈ X$, there exists an open set $O_{x}$ such that $x ∈ O_{x}$ but $y \notin O_{x}$. A 
 ^def-top-t1

> [!lemma|*]- All $T_{2}$ are $T_{1}$
> $T_{1}$ space is a looser condition than a Hausdorff space so all Hausdorff spaces are $T_{1}$
 ^lem-top-t1-t2

> [!theorem|*]- Points in $T_{1}$ are closed sets
> A topological space $X$ is $T_{1}\iff$ points in $X$ are closed sets.
 ^thm-top-t1-point-closed

> [!definition|*]- One-Point Compactification
> The one-point compactification $\tilde{X}$ of a topological space $X$ is the set $X ∪ \{∞\}$ (where $∞$ is a single point called ”the point at infinity”) with the following topology:
> - if $∞ \notin U$ , then $U$ is open in $\tilde{X}\iff$ it is open in $X$
> - if $∞ \in U$ , then $U$ is open in $\tilde{X}\iff$ its complement is compact
 ^def-top-one-point-comp
 
![[0. Topology Notes (pre project).pdf#page=51&rect=173,426,426,574|0. Topology Notes (pre project), p.51]]

> [!definition|*]- Closure of a set
> There are 3 equivalent definitions:
> 1. $F$ are closed sets and $\bar{A}=\bigcap \{ F|A\subseteq F \}$
> 2. $\bar{A}=A\cup A'$ where $A'$ is the set of all limit points of $A$.
> 3. $U$ are neighbourhoods of $x$ and $\bar{A}=\{ x| U\cap A\neq \varnothing \}$
 ^def-top-closure

 > [!definition|*]- Dense set
> There are 2 definitions:
> 4. $A$ is dense in $B$ if $B\subseteq \bar{A}$, wher $\bar{A}$ denotes the closure of $A$.
> 5. $A$ is dense in $B$ if for every $x \in B$, every neighbourhood of $x$ contains a point in $A$
 ^def-top-dense-set

> [!theorem|*]- Properties of One-Point Compactification
> For any open set $U ⊂ \tilde{X}$, $U ∩ X$ is open in $X$.
> ![[0. Topology Notes (pre project).pdf#page=52&rect=193,566,406,741|0. Topology Notes (pre project), p.52]]
> If $X$ is not compact, then $X$ is homomorphic to an open dense set in $\tilde{X}$.
> $\tilde{X}$ is compact.
> ![[0. Topology Notes (pre project).pdf#page=53&rect=175,567,425,740|0. Topology Notes (pre project), p.53]]
> $\tilde{X}$ is Hausdorff.
> If none of the components of $X$ is compact, then $\tilde{X}$ is connected.
> ![[0. Topology Notes (pre project).pdf#page=53&rect=128,128,468,282|0. Topology Notes (pre project), p.53]]
> If $X$ is homomorphic to $Y$ , $\implies\tilde{X}$ is homomorphic to $\tilde{Y}$.
> ![[0. Topology Notes (pre project).pdf#page=55&rect=132,559,472,733|0. Topology Notes (pre project), p.55]]
 ^thm-top-prop-opc