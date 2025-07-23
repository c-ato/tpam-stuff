---
tags:
  - maths

  - topology

aliases:
  - vertex
---

> [!definition|*]- Vertices
> An $n$-vertex in a subset $L$ of a [[Topology|topological]] space $S$ is an element $v ∈ L$ such that there exists some [[Neighbourhoods|neighbourhood]] $N_{0} ⊆ S$ of $v$ where all [[neighbourhoods]] $N ⊆ N_{0}$ of $v$ satisfy the following properties: 
> - $N ∩ L$ is connected. 
> - The set formed by removing $v$ from $N ∩ L$, i.e., $\{a ∈ N ∩ L | a \neq v\}$, is not connected, and is composed of exactly $n$ disjoint sets, each of which is connected
 ^def-top-verti

> [!theorem|*]- Invariance of vertices
> We can say that for a given $n ≥ 3$, the number of $n$-vertices is a [[Topology|topological]] invariant because [[Morphisms|homeomorphisms]] preserve connectedness. Thus, the connected set around a vertex must map to another connected set, and the set of $n$ disjoint, connected pieces must map to another set of $n$ disjoint connected pieces
 ^thm-top-invar-verti

> [!remark|*]- $2$-Vertices
> The number of $2$-vertices is not useful as every curve has an infinite number of 2-vertices and is generally not very useful in distinguishing between [[Topology|topological]] objects.
 ^rmk-top-2-verti

> [!remark|*]- Holes and $1$-vertices
> A single hole has a property of having $0$ $1$-vertices (and $\infty$ $2$-vertices) and it then makes sense that you cannot shrink a hole to a point as this then has only $1$ $0$-vertices which clearly does not preserve the topologically invariant property of $n$-vertices. 
 ^rmk-top-circ-2-point

> [!corollary|*]- [[Topology|Topological]] Classification of Letters of the Alphabet
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

> [!definition|*]- Disjoint [[Neighbourhoods]]
> Let $X$ be a [[Topology|topological]] space. Let $x,y \in X$. We say that $x$ and $y$ can be separated by [[neighbourhoods]] if there exists a [[Neighbourhoods|neighbourhood]] $U$ of $x$ and a [[Neighbourhoods|neighbourhood]] $V$ of $y$ such that $U$ and $V$ are disjoint i.e. $U ⋂ V = ∅$.
 ^def-top-disj-neigh