---
tags:
  - maths
  - topology
aliases:
  - topological
  - topologies
---

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
> When $X$ is a set and $τ$ is a topology on $X$, we say that the sets in $τ$ are open. Therefore, if $X$ does have a [[Metric space|metric]] (a notion of distance), then $τ =\{\text{all open sets as defined with the ball}\}$ is indeed a topology. We call this topology the Euclidean topology. It is also referred to as the usual or ordinary topology.
 ^def-top-euclidean-top

> [!definition|*]- Induced Topology
> If $Y ⊆ X$ and $τ_{x}$ is a topology on $X$, one can define the Induced topology as $τ_{y} = \{O ⋂ Y |O ∈ τ_{x}\}$.
 ^def-top-induced-top
> [!example|*]- Finite intersection of topology
> Let $X = \mathbb{R}$ with the usual topology. Then certainly in this standard Euclidean topology, $\left( − \frac{1}{n}, \frac{1}{n} \right)$ is an open set for any integer $n$. However, the infinite intersection $⋂^{\infty}_{n=1}1\left( - \frac{1}{n}, \frac{1}{n} \right)$ is the set containing just $0$. Thus, it is a single point set, which is not open in this topology.
 ^exm-top-finit-inters

> [!remark|*]- $X$ and $\varnothing$, are both open and closed
> $\varnothing$ is open $\implies X$ is closed. 
> $X$ is open $\implies \varnothing$ is closed
> $\varnothing$ and $X$ are both open and closed
 ^rmk-top-clopen-empty-X

> [!lemma|*]- Relation of Clopen Subset on an Open Set of the Open Cover
> Let $\mathfrak{F}$ be a family of subsets of $X$ whose union is all of $X$ and $A$ be a nonempty subset of $X$ which is both open and closed and not equal to all of $X$. If each member $\mathfrak{F}$ is connected, then for $Z \in \mathfrak{F}$ either $Z\cap A=\varnothing\lor=Z$.
 ^lem-top-rel-clop-op-set-op-cov
