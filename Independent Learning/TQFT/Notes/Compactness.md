---
tags:
  - maths
  - maths/topology
aliases:
  - compact
  - compactification
  - open cover
  - subcover
  - open covers
  - subcovers
  - compacted
---

> [!definition|*]- Open Cover
> Let $X$ be a [[Topology|topological]] space, an open cover is then a family of open subsets of $X$ whom union is $X$. 
 ^def-top-open-cov

> [!definition|*]- Subcover
> If $\mathcal{F}$ is an open cover of $X$ and $\mathcal{F}'$ is a subfamily of $\mathcal{F}$ and $\bigcup \mathcal{F'}=X$, then $\mathcal{F'}$ is called a subcover of $X$
 ^def-top-subcov

![[0. Topology Notes (pre project).pdf#page=38&rect=178,507,420,701|0. Topology Notes (pre project), p.38]]
Union of purple and yellow is the open cover $\mathcal{F}$ and purple is subcover $\mathcal{F'}$

> [!example|*]- Open cover with no subcover $(\mathbb{R}^{2})$
> Let $\mathcal{F}$ be the set of open balls (circles) of $r=1$ who's centres have integer coordinates, $\mathcal{F}:=\{ (x+n,y+m)|x^{2}+y^{2}\leq 1|n,m\in \mathbb{Z} \}$. This family covers the plane, but if a single ball is removed the family no long covers the entire space and hence this famaily has no proper subcovers.
 ^exm-top-open-cov-no-subcov

> [!theorem|*]- Generalised Heine-Borel Theorem
> In $\mathbb{R}^{n}$ with Euclidean [[topology]], compact sets are precisely the closed and bounded sets of $\mathbb{R}^{n}$
 ^thm-top-gen-hb

> [!theorem|*]- Real function defined in compact space
> A continuous, real-valued function defined on a compact space is bounded and attains its bounds.
 ^thm-top-re-funct-comp-spa-bound

> [!definition|*]- Compactness
> There are 2 [[Equivalence|equivalent]] definitions:
> 1. A space is compact if every open cover has a finite subcover. (This is [[Equivalence|equivalent]] to “closed” and “bounded” in an Euclidean Space).
> 2. A [[Topology|topological]] space $X$ is compact if every collection of closed sets $\mathcal{C_{\alpha}}\in X$ such that $\bigcap \mathcal{C_{\alpha}}=\varnothing,\exists$ a finite collection of closed subsets $\mathcal{C}_{1},\mathcal{C}_{2},\dots,\mathcal{C}_{n}$ such that $\bigcap \mathcal{C_{n}}=\varnothing$.
 ^def-top-comp

> [!example|*]- Compact set
> Suppose $X$ is a [[Hausdorff]] space, and we have a point $x$ in $X$ and a finite subset $A$ of $X$ not containing $x$. Then we can separate $x$ and $A$ by [[neighbourhoods]]: for each a in $A$, let $U(x)$ and $V(a)$ be disjoint [[neighbourhoods]] containing $x$ and $a$, respectively. Then the intersection of all the $U(x)$ and the union of all the $V(a)$ are the required [[neighbourhoods]] of $x$ and $A$.
 ^exm-top-comp

 > [!remark|*]- Infinite Subset in Compact Sets
> Note that if $A$ is infinite, the proof fails, because the intersection of arbitrarily many [[neighbourhoods]] of $x$ might not be a [[Neighbourhoods|neighbourhood]] of $x$. The proof can be ”rescued”, however, if $A$ is compact: we simply take a finite subcover of the cover $V (a)$ of $A$. In this way, we see that in a [[Hausdorff]] space, any point can be separated by [[neighbourhoods]] from any compact set not containing it. In fact, repeating the argument shows that any two disjoint compact sets in a [[Hausdorff]] space can be separated by [[neighbourhoods]].
 ^rmk-top-inf-A-comp

> [!theorem|*]- Compactness is Invariant on a Continuous Function
> If $f$ is a continuous function, then the image of the compact set under $f$ is also compact.
 ^thm-top-inv-comp-cont-func

> [!theorem|*]- Transitivity of Compactness on Closed Subsets
> Any closed subset $C$ of a compact space $K$ is also compact.
 ^thm-top-trans-clos-subset

> [!definition|*]- One-Point Compactification
> The one-point compactification $\tilde{X}$ of a [[Topology|topological]] space $X$ is the set $X ∪ \{∞\}$ (where $∞$ is a single point called ”the point at infinity”) with the following [[topology]]:
> - if $∞ \notin U$ , then $U$ is open in $\tilde{X}\iff$ it is open in $X$
> - if $∞ \in U$ , then $U$ is open in $\tilde{X}\iff$ its complement is compact
 ^def-top-one-point-comp
 
![[0. Topology Notes (pre project).pdf#page=51&rect=173,426,426,574|0. Topology Notes (pre project), p.51]]

> [!theorem|*]- One-Point Compactification (of Non-Compact Space) 
> For any non-compact space $X$ the one-point compactification of $X$ is obtained by adding one extra point $∞$ and defining the open sets of the new space to be the open sets of $X$ together with the sets of the form $G ∪ ∞$, where $G$ is an open subset of $X$ such that $X \setminus G$ is compact.
 ^thm-top-comp-ification

> [!theorem|*]- Compact [[Neighbourhoods|Neighbourhood]] to Compact Space
> Any locally compact (every point is contained in a compact [[Neighbourhoods|neighbourhood]]) [[Hausdorff]] space can be turned into a compact space by adding a single point to it, by means of one-point compactification. The one-point compactification of $\mathbb{R}$ is [[Morphisms|homomorphic]] to the circle $S^{1}$; the one-point compactification of $\mathbb{R}^{2}$ is [[Morphisms|homomorphic]] to the sphere $S^{2}$. Using the one-point compactification, one can also easily construct compact spaces which are not [[Hausdorff]], by starting with a non-[[Hausdorff]] space.
 ^thm-top-comp-neigh-2-comp-spa

> [!theorem|*]- Properties of One-Point Compactification
> For any open set $U ⊂ \tilde{X}$, $U ∩ X$ is open in $X$.
> ![[0. Topology Notes (pre project).pdf#page=52&rect=193,566,406,741|0. Topology Notes (pre project), p.52]]
> If $X$ is not compact, then $X$ is [[Morphisms|homomorphic]] to an open dense set in $\tilde{X}$.
> $\tilde{X}$ is compact.
> ![[0. Topology Notes (pre project).pdf#page=53&rect=175,567,425,740|0. Topology Notes (pre project), p.53]]
> $\tilde{X}$ is [[Hausdorff]].
> If none of the components of $X$ is compact, then $\tilde{X}$ is [[Connectedness|connected]].
> ![[0. Topology Notes (pre project).pdf#page=53&rect=128,128,468,282|0. Topology Notes (pre project), p.53]]
> If $X$ is [[Morphisms|homomorphic]] to $Y$ , $\implies\tilde{X}$ is [[Morphisms|homomorphic]] to $\tilde{Y}$.
> ![[0. Topology Notes (pre project).pdf#page=55&rect=132,559,472,733|0. Topology Notes (pre project), p.55]]
 ^thm-top-prop-opc