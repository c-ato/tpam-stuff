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
> For $n\geq 3,\,\text{Spin}(n)$ is [[Connectedness|simply connected]]. For $n=1,\,\text{Spin}(n)\cong\mathbb{Z}_{2}$, and (more importantly for us) $n=2,\,\text{Spin}(2)\cong S^{1}$, the circle group. $\text{Spin}(2)$ is not [[Connectedness|simply connected]] ([[fundamental group]] is $\mathbb{Z}$), but it is the universal covering group of $\text{SO}(2)≅S^{1}$. The map $\rho:S^{1}\to S^{1}$ is given by $z\to z^{2}$ (squaring complex numbers on the unit circle), which is a 2-to-1 map.
 ^def-alg-spin-group

> [!definition|*]- Spin Structure
> A spin structure on $M$ is a pair $(P_{\text{Spin}},f)$, where $P_{\text{Spin}}$ is the [[Spinor Bundles|principal $\text{Spin}(n)$-bundle]], over $M$, and $f:P_{\text{Spin}}\to P_{\text{SO}}$ is a bundle map where the identity map on the base space $M$ is $\pi_{\text{SO}}\circ f=\pi_{\text{Spin}}$.
> 
> $M$ is required to be a $n$-dimensional [[Surfaces|orientable]] Riemannian [[Manifolds|manifold]], $M$, with a [[Spinor Bundles|principal $\text{SO}(n)$-bundle]] of oriented orthonormal frames, $P_{\text{SO}}$, over $M$.
>  
> It is also equivariant with respect to the group action, that is to say $f(p\cdot s)=f(p)\cdot \rho(s)$ $p \in P_{\text{Spin}}$, $s\in \text{Spin}(n)$ and $\rho: \text{Spin}(n)\to \text{SO}(n)$ is the double cover map.
 ^def-top-spin-struct

 