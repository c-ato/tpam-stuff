---
tags:
  - topology
  - maths
  - physics
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%203" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=11" class="button">Go to PDF Page 11
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%201" class="button">Previous
	</a> 
</div>

> [!definition|*]- Limit points
> A point $z$ is a limit point for a set $A$ if every open set $U$ containing $z$ intersects $A$ in a point other than $z$.
> 
> The point $z$ may or may not be in $A$
 ^def-top-lim-point

> [!example|*]- Open unit disk $D=\{ (x,y):x^{2}+y^{2}<1 \}$ and $z=(1,0)$
> $z$ is not an element of $D$ as $1^{2}+0^{2}=1$ which is not $<1$
 
> [!theorem|*]- Closed (Set)
> A set $C$ is closed $\iff$ it contains all of its limit points.
 ^thm-top-closed-set

> [!example|*]- Let $A = \mathbb{Z}$, a subset of $\mathbb{R}$. This is a closed set because it does contain all of its limit points; no point is a limit point! A set that has no limit points is closed, by default, because it contains all of its limit points.
 ^exm-int-clos-lim

> [!definition|*]- Topology
> A topology $τ$ on a set $X$ consists of subsets of $X$ satisfying the following properties:
> - The empty set $\varnothing$ and the space $X$ are both sets in the topology.
> - The union of any collection of sets in $τ$ is contained in $τ$.
> - The intersection of any finitely many sets in $τ$ is also contained in $τ$.
 ^def-top-top

> [!definition|*]- Topological Space
> A topological space is a pair $(X, τ )$ where $X$ is a set and $τ$ is a set of subsets of $X$ satisfying certain axioms. $τ$ is called a topology
 ^def-top-top-space

> [!definition|*]- Euclidean Topology
> When $X$ is a set and $τ$ is a topology on $X$, we say that the sets in $τ$ are open. Therefore, if $X$ does have a metric (a notion of distance), then $τ =\{\text{all open sets as defined with the ball}\}$ is indeed a topology. We call this topology the Euclidean topology. It is also referred to as the usual or ordinary topology.
 ^def-top-euclidean-top

> [!definition|*]- Induced Topology
> If $Y ⊆ X$ and $τ_{x}$ is a topology on $X$, one can define the Induced topology as $τ_{y} = \{O ⋂ Y |O ∈ τ_{x}\}$.
 ^def-top-induced-top

> [!example|*]- Finite intersection of topology
> Let $X = \mathbb{R}$ with the usual topology. Then certainly in this standard Euclidean topology, $\left( − \frac{1}{n}, \frac{1}{n} \right)$ is an open set for any integer $n$. However, the infinite intersection $⋂^{\infty}_{n=1}1\left( - \frac{1}{n}, \frac{1}{n} \right)$ is the set containing just $0$. Thus, it is a single point set, which is not open in this topology.
 ^exm-top-finit-inters

> [!definition|*]- Closed (Set) - Revised  
> A set $C$ is closed if $X-C$ is open.
 ^def-top-close-revis

`\begin{proof}` A closed set includes all its limit points,

Let $C$ be closed. In the trivial case where $C$ does not have any limit points, this holds. $C'$ is the complement and hence open as $C$ is closed by definition $X-C'=C$

Now suppose that $z$ is a limit point of $C$ and for contradiction, assume that $z\notin C$. This means that $z\in C'$ which is a contraction as by the definition of an open set there exists a subset $U\subseteq C'$ which would not intersect $C$ as $C'\cap C=\varnothing$ and by transitivity of a set $U\cap C=\varnothing$ and hence $z$ is not a limit point of $C$. $\therefore$ by contradiction $z \in C$ so all limit points $z$ are contained in $C$ a closed set.`\end{proof}`

> [!remark|*]- $X$ and $\varnothing$, are both open and closed
> $\varnothing$ is open $\implies X$ is closed. 
> $X$ is open $\implies \varnothing$ is closed
> $\varnothing$ and $X$ are both open and closed
 ^rmk-top-clopen-empty-X

> [!definition|*]- Continuity 
> A function $f : X \mapsto  Y$ is continuous $\iff$ the pre-image of any open (closed) set in $Y$ is open (closed) in $X$.
 ^def-top-continuity

> [!definition|*]- Neighbourhood
> Given a point $x \in X$, we call a subset $N \subseteq X$ a neighbourhood of $X$ if we can find an open set $O$ such that $x ∈ O ⊆ N$.
> - A function $f : X → Y$ is continuous if for any neighbourhood $V\subseteq Y$ there is a neighbourhood $U\subseteq X$ such that $f (U) ⊆ V$ 
> - A composition of 2 continuous functions is continuous.
 ^def-top-neigh

> [!definition|*]- Homomorphisms
> This is the notion of equality (invariance) in topology.
> 
> A homomorphism is a function $f : X → Y$ between two topological spaces $X$ and $Y$ that:
> - is continuous bijective 
> - has a continuous inverse function $f^{-1}$
 ^def-top-homomorphisms

> [!definition|*]- Homomorphisms (Alternative)
> Two topological spaces $X$ and $Y$ are said to be homomorphic if there are continuous map $f : X → Y$ and $g : Y → X$ such that $$f ◦ g = I_{Y} \qquad \text{and}\qquad g ◦ f = I_{X}$$ Moreover, the maps $f$ and $g$ are homeomorphisms and are inverses of each other, so we may write $f^{-1}$ in place of $g$ and $g^{-1}$ in place of $f$. Where $I_{X}$ and $I_{Y}$ denote the identity maps.
 ^def-top-homo-alt

> [!lemma|*]- Equivalence relation of Homomorphisms on Topological Spaces
> - Reflexivity: $X$ is homomorphic to $X$.
> - Symmetry: If $X$ is homomorphic to $Y$, then $Y$ is homomorphic to $X$.
> - Transitivity: If $X$ is homomorphic to $Y$ , and $Y$ is homomorphic to $Z$, then $X$ is homomorphic to $Z$.
> These are called homomorphism classes.
 ^lem-top-homo-equiv

> [!example|*]- Any open interval of $\mathbb{R}$ is homomorphic to any other open interval. 
> Consider $X = (−1, 1)$ and $Y = (0, 5)$. Let $f : X → Y$ be $$f (x) = \frac{5}{2} (x + 1)$$
> Observe that $f$ is bijective and continuous, being the compositions of addition and multiplication. Moreover, $f^{-1}$ exists and is continuous:$$f ^{-1}(x) = \frac{2}{5} x − 1$$
> Note that neither $[0, 1]$ nor $[0, 1)$ is homomorphic to $(0, 1)$ as such mapping between these intervals, if constructed, will fail to be a bijection due to endpoints.
 ^exm-top-homo-O-2-O

> [!example|*]- There exists homomorphism between a bounded and an unbounded set
> $$f(x)=\frac{1}{x}$$
> Then it follows that $(0, 1)$ and $(1, ∞)$ are homomorphic.
 ^exm-top-homo-fin-inf

