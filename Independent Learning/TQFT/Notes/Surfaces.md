---
tags:
  - maths
  - maths/topology
aliases:
  - genus
  - geni
  - surface
  - orientable
  - non-orientable
  - identification poloygon
  - identification poloygons
---

> [!definition|*]- Surface
> A surface is a [[Topology|topological]] space $S$ such that every point $s ∈ S$ has a [[Neighbourhoods|neighbourhood]] [[Morphisms|homomorphic]] to $\mathbb{R}^{2}$.
 ^def-top-surf

> [!definition|*]- Non-Orientable
> A surface is non-orientable is it contains a mobius band, which is the most simplest of non-orientable surfaces, which others can be constructed of.
> ![[0. Topology Notes (pre project).pdf#page=69&rect=163,556,430,639|0. Topology Notes (pre project), p.69]]
 ^def-top-non-orien

> [!theorem|*]- Surface can be Represented as Polygons (Identification Polygon)
> All closed, [[Compactness|compact]] surfaces can be represented by a $2n$-sided polygon. The pairwise identification of edges of known polygons can be used to build other polygons that are more complex and can represent new surfaces.
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
> Orientability is a means of dividing [[Compactness|compact]] surfaces into two classes, orientable and non-orientable and is used to help us classify surfaces. 
> A surface is considered orientable if a vector $Y$ perpendicular to the surface at point $P$ can be slid along the surface such that it always remains perpendicular to the surface and when it arrives back at $P$ it points in the same direction as when it started.
> Informally, if a surface is orientable if it has a top and bottom or inside and outside which are distinguishable
> ![[0. Topology Notes (pre project).pdf#page=77&rect=70,243,541,748|0. Topology Notes (pre project), p.77]]
 ^def-top-orient

The basic surfaces are the cylinder, sphere and torus belonging to the orientable, whereas the non-orientable basics are the Mobius band, the projection plane and the Klein bottle.

> [!definition|*]- A more Complex Surface Definition.
> A surface $S$ is a [[Connectedness|connected]], [[Countable Spaces|second countable]], [[Hausdorff]] [[Topology|topological]] space with a family of [[Morphisms|homomorphisms]] $\phi_{\alpha} : U_{\alpha} → D_{\alpha}$ from domains $U_{\alpha}$ that form an [[Compactness|open cover]] of $S$ to open subsets $D_{\alpha}$ in the complex plane. 
 ^def-top-riem-surf