---
tags:
  - maths
  - topology
  - physics
  - quantum
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf
Note number: "3"
Title Stem: Topology
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%20
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%204" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=16" class="button">Go to PDF Page 16
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%202" class="button">Previous
	</a> 
</div>

> [!example|*]- A Topologist cannot tell the difference between a Circle and Square...
> A circle is given as $S^{1}=\{ (x,y)\in \mathbb{R}^{2}|x^{2}+y^{2}=1 \}$ and a square $T=\{ (x,y)\in \mathbb{R}^{2} \}$. We may define a function $f:S^{1}\mapsto T$ defined by$$f(x,y)=\left( \frac{x}{\left| x \right|+\left| y \right|}, \frac{y}{\left| x \right|+\left| y \right|} \right)$$
> which is continuous, bijective and has a continuous inverse$$f^{-1}(x,y)=\left( \frac{x}{\sqrt[  ]{ x^{2}+y^{2} }}, \frac{y}{\sqrt[  ]{ x^{2}+y^{2} }} \right)$$
> Both circle and square are therefore topologically identical. $S^{1}$ and $T$ are sometimes called simple closed curves (or Jordan curves).
 ^exm-top-circ-squar

> [!example|*]- Circle ($S^{1}$) to $\mathbb{R}^{1}$ 
> $S^{1}$ with a point removed is homomorphic with $\mathbb{R}$. Without loss of generality, suppose we removed the North Pole. Then the stereographic projection is a homomorphism between the real line and the remaining space of $S^{1}$ after a point is omitted. 
> 
> Place the circle “on” the $x$-axis with the point omitted being directly opposite the real line. More precisely, let $S^{1} = \left\{ (x, y) ∈ R | x^{2} +\left( y -\frac{1}{2} \right)^{2} = \frac{1}{4} \right\}$ and suppose the North Pole is $N = (0, 1)$. Using geometry, we may construct $f : S^{1} \setminus N → \mathbb{R}$ by defining $$f (x, y) = \frac{2x}{1-y}$$ $f$ is well-defined and continuous as the domain of $f$ excludes $y = 1$, i.e. the North Pole. With the continuous inverse function $$f^{-1}(x)=\left( \frac{4x}{x^{2}+4}, \frac{x^{2}-4}{x^{2}+4} \right)$$ we have $f ◦ f^{-1} = f^{-1} ◦ f = I$, hence $f$ is a homeomorphism
 ^exm-top-circ-2-R

> [!example|*]- Annulus to open cylinder surface.
> The annulus $A = \{(x, y) ∈ \mathbb{R}^{2} | 1 ≤ x^{2} + y^{2} ≤ 4\}$ is homomorphic to the cylinder $C = \{(x, y, z) ∈ \mathbb{R}^{3} | x^{2} + y^{2} = 1, 0 ≤ z ≤ 1\}$ since there exists continuous function  $f: C → A$ and $g : A → C$ $$f (x, y, z) = ((1 + z)x, (1 + z)y)$$$$g(x, y) = \left( \frac{x}{\sqrt[  ]{ x^{2}+y^{2} }} , \frac{y}{\sqrt[  ]{ x^{2}+y^{2} }} , \sqrt[  ]{ x^{2}+y^{2} } − 1 \right) $$
> such that $f ◦ g = g ◦ f = I$. Thus $f$ and $g$ homomorphisms. Recognise there is a preservation of a hole. 
 ^exm-top-ann-2-cyl

> [!theorem|*]- Invariant Homomorphic Properties
> Let $X$ and $Y$ be homomorphic topological spaces. If $X$ is connected or compact or Hausdorff, then so is $Y$.
 ^thm-top-invar-homo-prop

> [!definition|*]- Vertices
> An $n$-vertex in a subset $L$ of a topological space $S$ is an element $v ∈ L$ such that there exists some neighbourhood $N_{0} ⊆ S$ of $v$ where all neighbourhoods $N ⊆ N_{0}$ of $v$ satisfy the following properties: 
> - $N ∩ L$ is connected. 
> - The set formed by removing $v$ from $N ∩ L$, i.e., $\{a ∈ N ∩ L | a \neq v\}$, is not connected, and is composed of exactly $n$ disjoint sets, each of which is connected
 ^def-top-verti

> [!theorem|*]- Invariance of vertices
> We can say that for a given $n ≥ 3$, the number of $n$-vertices is a topological invariant because homeomorphisms preserve connectedness. Thus, the connected set around a vertex must map to another connected set, and the set of $n$ disjoint, connected pieces must map to another set of $n$ disjoint connected pieces
 ^thm-top-invar-verti

> [!remark|*]- $2$-Vertices
> The number of $2$-vertices is not useful as every curve has an infinite number of 2-vertices and is generally not very useful in distinguishing between topological objects.
 ^rmk-top-2-verti

> [!remark|*]- Holes and $1$-vertices
> A single hole has a property of having $0$ $1$-vertices (and $\infty$ $2$-vertices) and it then makes sense that you cannot shrink a hole to a point as this then has only $1$ $0$-vertices which clearly does not preserve the topologically invariant property of $n$-vertices. 
 ^rmk-top-circ-2-point

> [!corollary|*]- Topological Classification of Letters of the Alphabet
> | Letters                | Holes | 3-Vertices | 4-Vertices |
| ---------------------- | ----- | ---------- | ---------- |
| C, G, I, J, L, M, N, S | 0     | 0          | 0          |
| D, O                   | 1     | 0          | 0          |
| E, F, T, Y             | 0     | 1          | 0          |
| P                      | 1     | 1          | 0          |
| H, K                   | 0     | 2          | 0          |
| A, R                   | 1     | 2          | 0          |
| B                      | 2     | 2          | 0          |
| X                      | 0     | 0          | 1          |
| Q                      | 1     | 0          | 1          |
 ^cor-top-let-alp

> [!definition|*]- Topological Invariant
> A topological invariant of a space $X$ is a property that depends solely on the topology of the space $X$. That is, a property shared by any other space that are homomorphic to $X$. 
> 
> Intuitively, a homeomorphism between $X$ and $Y$ maps points in $X$ that are “close together” to points in $Y$ that are “close together”, and points in $X$ not “close together” to points in $Y$ that are not “close together”.
 ^def-top-invar

> [!definition|*]- Disjoint Neighbourhoods
> Let $X$ be a topological space. Let $x,y \in X$. We say that $x$ and $y$ can be separated by neighbourhoods if there exists a neighbourhood $U$ of $x$ and a neighbourhood $V$ of $y$ such that $U$ and $V$ are disjoint i.e. $U ⋂ V = ∅$.
 ^def-top-disj-neigh

> [!definition|*]- Hausdorff
> A space is Hausdorff if every two distinct points have disjoint neighbourhoods.
 ^def-top-hausdorff

> [!example|*]- $T1$
> A  topological space is called $T1$ if for any pairs of point $x,y ∈ X$, there is an open set $O_{x}$ such that $x ∈ O_{x}$ and $y$ isn’t. Hausdorff are $T1$ but the vice versa is not always true. A simple example is an infinite set endowed with the cofinite topology.
 ^exm-top-hausdorff

> [!definition|*]- Compact Set
> A space is compact if every open cover has a finite subcover. (This is equivalent to “closed” and “bounded” in an Euclidean Space).
 ^def-top-comp

> [!example|*]- Compact set
> Suppose $X$ is a Hausdorff space, and we have a point $x$ in $X$ and a finite subset $A$ of $X$ not containing $x$. Then we can separate $x$ and $A$ by neighbourhoods: for each a in $A$, let $U(x)$ and $V(a)$ be disjoint neighbourhoods containing $x$ and $a$, respectively. Then the intersection of all the $U(x)$ and the union of all the $V(a)$ are the required neighbourhoods of $x$ and $A$.
 ^exm-top-comp

 > [!remark|*]- Infinite Subset in Compact Sets
> Note that if $A$ is infinite, the proof fails, because the intersection of arbitrarily many neighbourhoods of $x$ might not be a neighbourhood of $x$. The proof can be ”rescued”, however, if $A$ is compact: we simply take a finite subcover of the cover $V (a)$ of $A$. In this way, we see that in a Hausdorff space, any point can be separated by neighbourhoods from any compact set not containing it. In fact, repeating the argument shows that any two disjoint compact sets in a Hausdorff space can be separated by neighbourhoods.
 ^rmk-top-inf-A-comp
