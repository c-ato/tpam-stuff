---
tags:
  - maths
  - topology
aliases:
  - connected
  - path-connected
  - path connected
---

> [!definition|*]- Closure of a set
> There are 3 [[Equivalence|equivalent]] definitions:
> 1. $F$ are closed sets and $\bar{A}=\bigcap \{ F|A\subseteq F \}$
> 2. $\bar{A}=A\cup A'$ where $A'$ is the set of all [[limit points]] of $A$.
> 3. $U$ are [[neighbourhoods]] of $x$ and $\bar{A}=\{ x| U\cap A\neq \varnothing \}$
 ^def-top-closure

 > [!definition|*]- Dense set
> There are 2 definitions:
> 4. $A$ is dense in $B$ if $B\subseteq \bar{A}$, wher $\bar{A}$ denotes the closure of $A$.
> 5. $A$ is dense in $B$ if for every $x \in B$, every [[Neighbourhoods|neighbourhood]] of $x$ contains a point in $A$
 ^def-top-dense-set

> [!definition|*]- Connectedness 
> There are 4 definitions:
> 6. A space $X$ is connected if it is not the union of a pair of disjoint non-empty open sets. 
> 7. A space is connected if the only sets that are simultaneously open and closes are the whole space and the empty set.
> 8. A [[Topology|topological]] space $X$ is said to be disconnected if it is the union of two disjoint non-empty open sets. Otherwise, $X$ is said to be connected.
> 9. A space $X$ is connected if whenever it is decomposed as the union $A ∪ B$ of two nonempty subsets then $\bar{A} ∩ B\neq \varnothing$ or $A ∩ \bar{B} \neq \varnothing$
 ^def-top-connectedness

> [!example|*]- Closed interval $[0,2]$ 
> The closed interval $[0, 2]$ is connected; it can, for example, be written as the union of $[0, 1)$ and £, but the second set is not open in the [[topology]] of $[0, 2]$. On the other hand, the union of $[0, 1)$ and $(1, 2]$ is disconnected; both of these intervals are open in the [[Topology|topological]] space $[0, 1) ∪ (1, 2]$.
 ^exm-top-connect

> [!theorem|*]- Connectedness is Invariant on a Continuous Function
> Let $X$ and $Y$ be [[Topology|topological]] spaces. If $f: X → Y$ is a continuous function, then the image of a connected subset $C \in X$ under $f$ is also connected.
 ^thm-top-invar-connect

Note the above theorem implies that connectedness is a [[Topology|topological]] invariant. It can also be considered a generalization of the intermediate value theorem. Connectedness is one of the principal [[Topology|topological]] properties that is used to distinguish [[Topology|topological]] spaces. A stronger notion is that of a path-connected space, which is a space where any two points can be joined by a path


> [!definition|*]- Path-Connectedness
> A path in a [[Topology|topological]] space $X$ is a continuous function $γ : [0, 1] → X$. A space is path-connected if any two points in the space can be joined by a path.
 ^def-top-path-conn

> [!theorem|*]- Connectedness on Euclidean Space
> A connected open subset of a euclidean space is path-connected.
 ^thm-top-con-eucli-spa

> [!theorem|*]- Path-Connected is Connected
> A path-connected space is connected.
 ^thm-top-path-connect-spa

> [!example|*]- $\sin\left( \frac{1}{x} \right)$ is Connected but not Path-Connected  
> Consider the space defined as the graph of the function $\sin\left( \frac{1}{x} \right)$ over the interval $(0, 1]$ extended by the single point $(0,0)$. This set is then equipped with the [[topology]] induced from the Euclidean plane. It is connected but not path-connected. It is the continuous image of a locally [[Compactness|compact]] space (namely, let $V$ be the space $-1 ∪ (0, 1]$, and use the map $f$ from $V$ to $T$ defined by $f(-1) = (0, 0)$ and $f(x) = \left( x, \sin\left( \frac{1}{x} \right) \right)$, but is not locally [[Compactness|compact]] itself.
 ^exm-top-conn-nimpl-path-conn

> [!theorem|*]- Properties of connectedness
> The following conditions on a space $X$ are [[Equivalence|equivalent]]:
>  - $X$ is connected
>  - The only subsets of $X$ which are both open and closed are $X$ and the $\varnothing$
>  - $X$ cannot be expressed as the union of two disjoint nonempty open sets 
>  - There is no onto continuous function from $X$ to a discrete space which contains more than one point
> 
> Let $X$ be a [[Topology|topological]] space and let $Z$ be a subset of $X$. If $Z$ is connected and dense in $X$, then $X$ is connected.
> Let $\mathfrak{F}$ be a family of subsets of a space $X$ whose union is all of $X$. If each member of $F$ is connected, and if no two members of $\mathfrak{F}$ are separated from on another in $X$, then $X$ is connected.  
 ^thm-top-equiv-conn
