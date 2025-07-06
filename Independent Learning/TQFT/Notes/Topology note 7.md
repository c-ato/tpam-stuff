---
Note number: 7
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
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%208" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F0.%20Topology%20Notes%20(pre%20project).pdf#page=58" class="button">Go to PDF Page 58
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FTopology%20note%206" class="button">Previous
	</a> 
</div>

![[Topology note 4#^def-top-connectedness]] 

> [!theorem|*]- Properties of connectedness
> The following conditions on a space $X$ are equivalent:
>  - $X$ is connected
>  - The only subsets of $X$ which are both open and closed are $X$ and the $\varnothing$
>  - $X$ cannot be expressed as the union of two disjoint nonempty open sets 
>  - There is no onto continuous function from $X$ to a discrete space which contains more than one point
> 
> Let $X$ be a topological space and let $Z$ be a subset of $X$. If $Z$ is connected and dense in $X$, then $X$ is connected.
> Let $\mathfrak{F}$ be a family of subsets of a space $X$ whose union is all of $X$. If each member of $F$ is connected, and if no two members of $\mathfrak{F}$ are separated from on another in $X$, then $X$ is connected.  
 ^thm-top-equiv-conn

> [!lemma|*]- Relation of Clopen Subset on an Open Set of the Open Cover
> Let $\mathfrak{F}$ be a family of subsets of $X$ whose union is all of $X$ and $A$ be a nonempty subset of $X$ which is both open and closed and not equal to all of $X$. If each member $\mathfrak{F}$ is connected, then for $Z \in \mathfrak{F}$ either $Z\cap A=\varnothing\lor=Z$.
 ^lem-top-rel-clop-op-set-op-cov

> [!definition|*]- Path-Connectedness
> A path in a topological space $X$ is a continuous function $γ : [0, 1] → X$. A space is path-connected if any two points in the space can be joined by a path.
 ^def-top-path-conn

> [!theorem|*]- Connectedness on Euclidean Space
> A connected open subset of a euclidean space is path-connected.
 ^thm-top-con-eucli-spa

> [!definition|*]- Surface
> A surface is a topological space $S$ such that every point $s ∈ S$ has a neighbourhood homomorphic to $\mathbb{R}^{2}$.
 ^def-top-surf

> [!definition|*]- Non-Orientable
> A surface is non-orientable is it contains a mobius band, which is the most simplest of non-orientable surfaces, which others can be constructed of.
> ![[0. Topology Notes (pre project).pdf#page=69&rect=163,556,430,639|0. Topology Notes (pre project), p.69]]
 ^def-top-non-orien

> [!theorem|*]- Surface can be Represented as Polygons (Identification Polygon)
> All closed, compact surfaces can be represented by a $2n$-sided polygon. The pairwise identification of edges of known polygons can be used to build other polygons that are more complex and can represent new surfaces.
 ^thm-top-surf-polyg

![[0. Topology Notes (pre project).pdf#page=73&rect=142,280,467,442|0. Topology Notes (pre project), p.73]]

> [!definition|*]- Cutting
> Cutting a surface is breaking it down into more manageable pieces. Any cut can be repaired by gluing things back together. Cutting is not a homeomorphism, unless it is followed by gluing the edges of the cut as they were before the cut
 ^def-top-cut

> [!definition|*]- Gluing
> Gluing is the inverse of cutting.
 ^def-top-glue

> [!definition|*]- Surgery
> This is the process of gluing and cutting
 ^def-top-surgery

![[0. Topology Notes (pre project).pdf#page=74&rect=206,116,391,246|0. Topology Notes (pre project), p.74]]

![[0. Topology Notes (pre project).pdf#page=75&rect=204,604,396,710|0. Topology Notes (pre project), p.75]]

![[0. Topology Notes (pre project).pdf#page=75&rect=196,420,396,540|0. Topology Notes (pre project), p.75]]

![[0. Topology Notes (pre project).pdf#page=75&rect=122,182,464,305|0. Topology Notes (pre project), p.75]]

> [!definition|*]- Genus
> This is the number of holes a shape has according to the identification polygon of its surface: $\chi=2g-2$
 ^def-top-genus

![[0. Topology Notes (pre project).pdf#page=76&rect=207,480,392,737|0. Topology Notes (pre project), p.76]]

> [!proposition|*]- General form of $n$ tori (genus $n$ surface) glued together.
> $a_{1}b_{1}a_{1}^{-1}a_{1}^{-1}a_{2}b_{2}a_{2}^{-1}a_{2}^{-1}\dots a_{n-1}b_{n-1}a_{n-1}^{-1}a_{n-1}^{-1}a_{n}b_{n}a_{n}^{-1}a_{n}^{-1}$
 ^prp-top-n-genus

> [!definition|*]- Orientability
> Orientability is a means of dividing compact surfaces into two classes, orientable and non-orientable and is used to help us classify surfaces. 
> A surface is considered orientable if a vector $Y$ perpendicular to the surface at point $P$ can be slid along the surface such that it always remains perpendicular to the surface and when it arrives back at $P$ it points in the same direction as when it started.
> Informally, if a surface is orientable if it has a top and bottom or inside and outside which are distinguishable
> ![[0. Topology Notes (pre project).pdf#page=77&rect=70,243,541,748|0. Topology Notes (pre project), p.77]]
 ^def-top-orient

The basic surfaces are the cylinder, sphere and torus belonging to the orientable, whereas the non-orientable basics are the Mobius band, the projection plane and the Klein bottle.

> [!definition|*]- Euler Characteristics
> $\chi$ is the Euler Characteristic, $V$ is the number of vertices, $E$ is the number of edges and $F$ is the number of faces a surface has
> $$\chi=V-E+F$$
> This has the requirements that the surface is compact and has a good graph.
 ^def-top-eul-char

> [!definition|*]- Good Graph
> A good graph on any surface is a graph, a collection of vertices and edges connecting them on a surface, such that:
> - There is a vertex at every end of each edge
> - The complement of the graph is homomophic to a disjoint union of disks
> ![[0. Topology Notes (pre project).pdf#page=82&rect=206,569,377,722|0. Topology Notes (pre project), p.82]]
 ^def-top-good-graph
