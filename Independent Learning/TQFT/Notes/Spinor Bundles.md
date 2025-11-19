---
tags:
  - concepts
  - maths/topology
  - maths/vectors
aliases:
  - spinor bundle
  - vector bundle
  - vector bundles
  - principle bundle
  - principle bundles
  - principal bundle
  - principal bundles
  - frame
  - frames
  - orthonormal frames
  - orthonormal frame
  - orthonormal frame bundle
  - orthonormal frame bundles
  - frame bundle
  - frame bundles
---

> [!definition|*]- Fibre Bundle
> A fibre bundle consists of:
> - The fibre $F$, a [[Topology|topological]] space attached at every point of the base
> - The collection of fibres $E$, the total space of the bundle, and is a [[Topology|topological]] space
> - The base space $X$, a [[Topology|topological]] space beneath the total space
> - The [[Product space|projection]] $\pi: E\to X$ which is a continuous surjective map. For any $x \in X$, $\pi ^{-1}(x)$ is called the fibre over $x$ and is required to be [[Morphisms|homomorphic]] to some standard $F$
> - A local triviality condition, where locally $E$ is [[Morphisms|homomorphic]] to a [[product space]] on a [[Neighbourhoods|neighbourhood]], $U$, of $X$, $\phi_{U}:\pi ^{-1}(U)\to U\times F$

^0ea0de
$$\begin{tikzcd} 
\pi^{-1}(U) \arrow[rr, "\phi_{U}"] \arrow[rd, "\pi"] & & U \times F \arrow[ld, "p_1"] \\ & U & 
\end{tikzcd}$$
 ^def-top-fib-bund

> [!definition|*]- Vector bundle
> A fibre bundle where the fibre is a vector space, and an additional restriction where we require for each $x\in U$, $\phi_{U}|_{\pi ^{-1}(x)}:\pi ^{-1}(x)\to \{ x \}\times F$ is a vector space [[Morphisms|isomorphism]].
 ^def-top-vec-bund

> [!definition|*]- Tangent Bundle
> A vector bundle where the vector space is a [[tangent space]], this requires the base space to be a differentiable [[Manifolds|manifold]].
 ^def-top-tang-bund

> [!definition|*]- Principal $G$-Bundle
> A fibre bundle where the fibre is a [[Topology|topological]] group. In addition the total space $E$ is equipped with:
> - The [[Quotient Space|group action]] is free if $pg=p$, where $p \in E$ and $g\in G\iff g$ is an identity element of $G$ 
>  - A [[Quotient Space|group action]] is transitive on the fibres, that is for $x \in X$, $y_{1},y_{2} \in\pi ^{-1}(x)$, so that for $y_{1}g=y_{2}\exists ! g \in G$
> - The local trivialisation maps are $G$-[[equivariant]]
 ^def-top-princ-bund

> [!definition|*]- Frame Bundle
>  A principal $G$-bundle where:
>  - The base space is instead a manifold, $M$
>  - A single frame is a linear transformation from the basis of $\mathbb{R}^{n}$ to the ordered basis of the tangent space, $T_{x}M$ that is associated at a point $x$ of the base space, $p:\mathbb{R}^{n}\to E_{x}$.
>  - $G=GL(n,\mathbb{R})$ and group action of $GL$ on a frame at $x$ is another frame of $x$, $p\cdot g=p\circ g: \mathbb{R}^{n}\to E_{x},g \in GL(n,\mathbb{R})$. The collection of all frames at $x$ is $F_{x}$.
>  - The total space is the collection of all frames, $F(M)=\bigsqcup_{x \in M}F_{x}$
 ^def-top-fram-bundle

> [!definition|*]- Orthonormal Frame Bundle
> This is the sub-bundle of the frame bundle where we restrict the frames by restricting the general linear group into either the orthogonal group, $O(n)$, or the special orthogonal group, $\text{SO}(n)$. This typically requires a Riemannian manifold. As this is equivalent to principal $G$-bundles and the total space will be denoted as $P_{O}$ or $P_{SO}$.
 ^def-top-orth-fram-bundle

> [!definition|*]- Associated Bundle
> This is constructed from a principal bundle $f: E\to X$ and a vector space such that the associated bundles total space is the group action on the vector space, $E\times_{G}V$ and the fibres of this bundle are copies of $V$. This also requires the equivalence relation $(e,v)\sim (eg,g^{-1}v)$ for $e \in E, v \in V$, and $g \in G$.
 ^def-top-assoc-bund

> [!definition|*]- [[Spin Structure|Spinor]] Bundle
> We require a [[spin structure]] which naturally needs $n$-dimensional [[Surfaces|orientable]] Riemannian [[Manifolds|manifold]] $M$ allowing for orthonormal frame bundles, $P_{\text{SO}}$ in the spin representation.
> This is a complex vector bundle over $M$. The spinor bundle is then defined as an associated bundle to the principal $\text{Spin}(n)$-bundle using spin representation
 ^def-top-spin-bund

