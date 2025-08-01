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

> [!definition|*]- Vector bundle
> A vector bundle consists of:
> - [[Topology|Topological]] spaces $X$ (base space) and $E$ a collection of vector spaces (total space)
> - A continuous surjective $\pi :E\to X$ (bundle [[Product space|projection]])
> - Fibres $\pi ^{-1}(x)\in E$ so that this forms a vector space itself and ${\pi ^{-1}(x)}$ is called the fibre over $x$. These are all [[Morphisms|isomorphic]] to a fixed fibre $V$, usually of $\mathbb{R}^{k}$ or $\mathbb{C}^{k}$.
> - The local triviality condition so that $\forall x \in X \exists U \subseteq X$, which is a [[Neighbourhoods|neighbourhood]] of $x$, and a [[Morphisms|isomorphism]] $\phi_{U}: \pi ^{-1}(U) \to U\times V$ such that:
> 	- $\phi$ preserves the [[Product space|projection]], so the diagram commutes
> ```tikz 
\usepackage{tikz-cd} \begin{document} \begin{tikzcd} \pi^{-1}(U) \arrow[rr, "\phi_U"] \arrow[rd, "\pi"] & & U \times V \arrow[ld, "p_1"] \\ & U & \end{tikzcd} \end{document}
> ```
> -
> 	- For each $x\in U$, the restriction of $\phi$​ to the fibre over $x$, $x,\phi_{U}|_{\pi ^{-1}(x)}:\pi ^{-1}(x):\to \{ x \}\times V$, is a vector space [[Morphisms|isomorphism]].
 ^def-top-vec-bund

> [!definition|*]- Tangent Bundle
> This is a collection of tangent spaces, $TM$, (generalised tangent line for higher dimensions - tangent line for curve, tangent plane for surfaces, ect) on a differentiable manifold, $M$, and is defined as followed:
> 
 ^def-

> [!definition|*]- Principal $G$-Bundle
> Where $G$ denotes any [[Topology|topological]] groups, $P$ is equipped with:
> - A [[Quotient Space|group action]] of $G$ on $P$ is analogous to $(x,g)h=(x,gh)$ for a [[product space]] as $P$ is locally [[Morphisms|isomorphic]] to $U\times G$ where $U\subseteq X$ is a [[Neighbourhoods|neighbourhood]] of $x$ (where $(x,g)\in P$ and $h\in G\therefore (x,gh)\in P$).
> - A [[Product space|projection]] onto $X$. For a [[product space]], this is just the [[Product space|projection]] onto the first factor, $(x,g)\to x$.
> - It is also a vector bundle and has where it has a base space $X$ and the total space is $P$.
 ^def-top-princ-bund

> [!definition|*]- Frame Bundle
> 
 ^def-top-fram-bundle

> [!definition|*]- Spinor Bundle
> We require a spin structure which naturally needs $n$-dimensional orientable Riemannian manifold $M$
 ^def-top-spin-bund