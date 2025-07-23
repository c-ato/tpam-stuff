---
tags:
  - maths
  - topology
aliases:
  - euler characteristic
  - good graph
  - good graphs
---

> [!definition|*]- Good Graph
> A good graph on any [[Surfaces|surface]] is a graph, a collection of [[vertices]] and edges connecting them on a [[Surfaces|surface]], such that:
> - There is a [[Vertices|vertex]] at every end of each edge
> - The complement of the graph is homomophic to a disjoint union of disks
> ![[0. Topology Notes (pre project).pdf#page=82&rect=206,569,377,722|0. Topology Notes (pre project), p.82]]
 ^def-top-good-graph
 
> [!definition|*]- Euler Characteristics
> $\chi$ is the Euler Characteristic, $V$ is the number of [[vertices]], $E$ is the number of edges and $F$ is the number of faces a [[Surfaces|surface]] has
> $$\chi=V-E+F$$
> This has the requirements that the [[Surfaces|surface]] is [[Compactness|compact]] and has a good graph.
 ^def-top-eul-char

> [!theorem|*]- Euler Characteristic on Good Graph used.
> Euler Characteristic of any [[Surfaces|surface]] is Independent of the Good Graph used to calculate it.
 ^thm-top-eul-char-good-gra

> [!theorem|*]- Euler Characteristic is Topologically Invariant
> The Euler characteristic is a [[Topology|topological]] invariant that allows us to distinguish whether or not two [[surfaces]] are homomorphic. [[Surfaces]] that have the same Euler characterisitic are not necessarily [[Morphisms|homeomorphic]], but if they are both [[Surfaces|orientable]] (or [[Surfaces|non-orientable]]), then they are. 
 ^thm-eul-char-inv

> [!theorem|*]- Identification Polygons are Good Graphs
> It is important to notice that an identification polygon is a good graph of a [[Surfaces|surface]] that has a [[Vertices|vertex]] at every end of edge and there is exactly one face. Therefore, identification polygons are good graphs on a [[Surfaces|surface]] and can be used to compute the Euler characteristic
 ^thm-top-iden-polyg-good-gra

![[0. Topology Notes (pre project).pdf#page=85&rect=203,479,396,692|0. Topology Notes (pre project), p.85]]