---
tags:
  - maths/topology
  - maths/vectors
  - maths/algebra
aliases:
  - spinor
  - spinors
---
> [!definition|*]- Spinors
> These are elements of a complex vector space, $v \in V$, which can be linearly mapped to Euclidean space, $F:V\to X$. By applying a infinitesimal rotation on $F(v)\in X$, the spinor is transformed linearly. What is required of this rotation is that a spinor transforms to its negative when it rotates $360°$.
 ^def-vec-spinor

> [!definition|*]- Spin Group
> A spin group is a [[Lie group]] with the underlying [[Manifolds|manifold]] being a [[Fundamental Group|double cover]] of $\text{SO}(n)$. This is denoted as $\text{Spin}(n)$. 
> 
> For $n\geq 3,\,\text{Spin}(n)$ is [[Connectedness|simply connected]]. For $n=1,\,\text{Spin}(n)\cong\mathbb{Z}_{2}$, and (more importantly for us) $n=2,\,\text{Spin}(2)\cong S^{1}$. $\text{Spin}(2)$ is not [[Connectedness|simply connected]] ([[fundamental group]] is $\mathbb{Z}$, but it is the universal covering group of $\text{SO}(2)≅S^{1}$. The map $\rho:S^{1}\to S^{1}$ is given by $z\to z^{2}$ (squaring complex numbers on the unit circle), which is a 2-to-1 map.
 ^def-alg-spin-group

> [!definition|*]- Spin Structure
> We require a $n$-dimensional [[Surfaces|orientable]] Riemannian [[Manifolds|manifold]], $M$, with a [[Spinor Bundles|principle $\text{SO}(n)$-bundle]] of oriented orthonormal frames, $P_{\text{SO}}(M)$, over $M$.
> 
> A spin structure on $M$ is a pair $(P_{\text{Spin}}(M),f)$, where $P_{\text{Spin}}(M)$ is the [[Spinor Bundles|principle $\text{Spin}(n)$-bundle]] and $f:P_{\text{Spin}}(M)\to P_{\text{SO}}(M)$ is a bundle map that satisfies, the identity map on the base space $M$, $\pi_{\text{SO}}\circ f=\pi_{\text{Spin}}$, where $\pi$ is a projection map onto $M$. 
> 
> It is also equivariant with respect to the group action $f(p\cdot s)=f(p)\cdot \rho(s)$ $p \in P_{\text{Spin}}(M)$, $s\in \text{Spin}(n)$ and $\rho: \text{Spin}(n)\to \text{SO}(n)$
 ^def-top-spin-struct

 