---
tags:
  - maths
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
---

> [!definition|*]- Fibre Bundle
> A fibre bundle consists of:
> - The fibre $F$, a [[Topology|topological]] space attached at every point of the base
> - The collection of fibres $E$, the total space of the bundle, and is a [[Topology|topological]] space
> - The base space $X$, a [[Topology|topological]] space beneath the total space
> - The [[Product space|projection]] $\pi: E\to X$ which is a continuous surjective map. For any $x \in X$, $\pi ^{-1}(x)$ is called the fibre over $x$ and is required to be [[Morphisms|homomorphic]] to some standard $F$
> - A local triviality condition, where locally $E$ is [[Morphisms|homomorphic]] to a [[product space]] on a [[Neighbourhoods|neighbourhood]], $U$, of $X$, $\phi_{U}:\pi ^{-1}(U)\to U\times F$
$$\begin{tikzcd} 
\pi^{-1}(U) \arrow[rr, "\phi_{U}"] \arrow[rd, "\pi"] & & U \times F \arrow[ld, "p_1"] \\ & U & 
\end{tikzcd}$$
 ^def-top-fib-bund

> [!definition|*]- Vector bundle
> A fibre bundle where the fibre is a vector space, and an additional restriction where we require for each $x\in U$, $\phi_{U}|_{\pi ^{-1}(x)}:\pi ^{-1}(x)\to \{ x \}\times F$ is a vector space [[Morphisms|isomorphism]].
 ^def-top-vec-bund

> [!definition|*]- Tangent Bundle
> A fibre bundle where the fibre is a [[tangent space]], this requires the base space to be a differentiable [[Manifolds|manifold]].
 ^def-top-tang-bund

> [!definition|*]- Principal $G$-Bundle
> A fibre bundle where the fibre is a [[Topology|topological]] group. In addition the total space $E$ is equipped with:
> - The [[Quotient Space|group action]] is free if $pg=p$, where $p \in E$ and $g\in G\iff g$ is an identity element of $G$ 
>  - A [[Quotient Space|group action]] is transitive on the fibres, that is for $x \in X$, $y_{1},y_{2} \in\pi ^{-1}(x)$, so that for $y_{1}g=y_{2}\exists ! g \in G$
> - The local trivialisation maps are $G$-[[equivariant]]
 ^def-top-princ-bund

> [!definition|*]- Frame Bundle
> 
 ^def-top-fram-bundle

> [!definition|*]- [[Spin Structure|Spinor]] Bundle
> We require a [[spin structure]] which naturally needs $n$-dimensional [[Surfaces|orientable]] Riemannian [[Manifolds|manifold]] $M$
 ^def-top-spin-bund

