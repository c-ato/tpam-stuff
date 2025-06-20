---
Note number: 4
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
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%205" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=24" class="button">Go to PDF Page 24
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%203" class="button">Previous
	</a> 
</div>

> [!definition|*]- Compact Set
> A space is compact if every open cover has a finite subcover. (This is equivalent to “closed” and “bounded” in an Euclidean Space).
 ^def-top-comp

> [!example|*]- Compact set
> Suppose $X$ is a Hausdorff space, and we have a point $x$ in $X$ and a finite subset $A$ of $X$ not containing $x$. Then we can separate $x$ and $A$ by neighbourhoods: for each a in $A$, let $U(x)$ and $V(a)$ be disjoint neighbourhoods containing $x$ and $a$, respectively. Then the intersection of all the $U(x)$ and the union of all the $V(a)$ are the required neighbourhoods of $x$ and $A$.
 ^exm-top-comp

 > [!remark|*]- Infinite Subset in Compact Sets
> Note that if $A$ is infinite, the proof fails, because the intersection of arbitrarily many neighbourhoods of $x$ might not be a neighbourhood of $x$. The proof can be ”rescued”, however, if $A$ is compact: we simply take a finite subcover of the cover $V (a)$ of $A$. In this way, we see that in a Hausdorff space, any point can be separated by neighbourhoods from any compact set not containing it. In fact, repeating the argument shows that any two disjoint compact sets in a Hausdorff space can be separated by neighbourhoods.
 ^rmk-top-inf-A-comp

> [!theorem|*]- Compactness is Invariant on a Continuous Function
> If $f$ is a continuous function, then the image of the compact set under $f$ is also compact.
 ^thm-top-inv-comp-cont-func

> [!theorem|*]- Transitivity of Compactness on Closed Subsets
> Any closed subset $C$ of a compact space $K$ is also compact.
 ^thm-top-trans-clos-subset

> [!theorem|*]- One-Point Compactification (of Non-Compact Space) 
> For any non-compact space $X$ the one-point compactification of $X$ is obtained by adding one extra point $∞$ and defining the open sets of the new space to be the open sets of $X$ together with the sets of the form $G ∪ ∞$, where $G$ is an open subset of $X$ such that $X \setminus G$ is compact.
 ^thm-top-comp-ification

> [!theorem|*]- Compact Neighbourhood to Compact Space
> Any locally compact (every point is contained in a compact neighbourhood) Hausdorff space can be turned into a compact space by adding a single point to it, by means of one-point compactification. The one-point compactification of $\mathbb{R}$ is homomorphic to the circle $S^{1}$; the one-point compactification of $\mathbb{R}^{2}$ is homomorphic to the sphere $S^{2}$. Using the one-point compactification, one can also easily construct compact spaces which are not Hausdorff, by starting with a non-Hausdorff space.
 ^thm-top-comp-neigh-2-comp-spa

> [!definition|*]- Connectedness 
> 2 definitions:
> 1. A space $X$ is connected if it is not the union of a pair of disjoint non-empty open sets. Equivalently, a space is connected if the only sets that are simultaneously open and closes are the whole space and the empty set.
> 
> 2. A topological space $X$ is said to be disconnected if it is the union of two disjoint non-empty open sets. Otherwise, $X$ is said to be connected.
 ^def-top-connectedness

> [!example|*]- Closed interval $[0,2]$ 
> The closed interval $[0, 2]$ is connected; it can, for example, be written as the union of $[0, 1)$ and £, but the second set is not open in the topology of $[0, 2]$. On the other hand, the union of $[0, 1)$ and $(1, 2]$ is disconnected; both of these intervals are open in the topological space $[0, 1) ∪ (1, 2]$.
 ^exm-top-connect

> [!theorem|*]- Connectedness is Invariant on a Continuous Function
> Let $X$ and $Y$ be topological spaces. If $f: X → Y$ is a continuous function, then the image of a connected subset $C \in X$ under $f$ is also connected.
 ^thm-top-invar-connect

Note the above theorem implies that connectedness is a topological invariant. It can also be considered a generalization of the intermediate value theorem. Connectedness is one of the principal topological properties that is used to distinguish topological spaces. A stronger notion is that of a path-connected space, which is a space where any two points can be joined by a path

> [!theorem|*]- Path-connected space
> A path-connected space is connected.
 ^thm-top-path-connect-spa

> [!example|*]- $\sin\left( \frac{1}{x} \right)$ is Connected but not Path-Connected  
> Consider the space defined as the graph of the function $\sin\left( \frac{1}{x} \right)$ over the interval $(0, 1]$ extended by the single point $(0,0)$. This set is then equipped with the topology induced from the Euclidean plane. It is connected but not path-connected. It is the continuous image of a locally compact space (namely, let $V$ be the space $-1 ∪ (0, 1]$, and use the map $f$ from $V$ to $T$ defined by $f(-1) = (0, 0)$ and $f(x) = \left( x, \sin\left( \frac{1}{x} \right) \right)$, but is not locally compact itself.
 ^exm-top-conn-nimpl-path-conn

