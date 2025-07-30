---
tags:
  - maths
  - physics
  - maths/topology
  - quantum
aliases:
---

> [!definition|*]- Curve
> A curve in a [[Surfaces|surface]] $S$ is a continuous map $γ : [0, 1] → S$. A curve is closed if $γ(0) = γ(1)$, and simple if $γ(x) = γ(y) \implies x = y$ for $x ∈ (0, 1)$ (that is to say, there are no other points of self-intersection).
 ^def-top-curve

> [!definition|*]- Concatenation
> Suppose we have curves, $\gamma_{1},\gamma_{2}$ satisfying $\gamma_{1}(1)=\gamma_{2}(0)$. We may concatenate them as such:$$\gamma_{2}*\gamma_{1}(t)\left\{ \begin{matrix}\gamma_{1}(2t),  & 0\leq t\leq \frac{1}{2} \\\gamma_{2}(2t-1),  & \frac{1}{2}\leq t\leq 1\end{matrix} \right. $$
 ^def-top-surf-conc

> [!definition|*]- Homotogy
> Let $X, Y$ be [[Topology|topological]] spaces. Let $f, g : X → Y$ be continuous. A homotopy is a continuous map $H : [0, 1] × X → Y$ such that for all $x ∈ X, H(0, x) = f (x)$ and $H(1, x) = g(x)$. If such a map exists, $f$ and $g$ are said to be homotopic
 ^def-top-homotogy

$[\gamma]=\{ \mu:[0,1]\to S: \mu \sim \gamma \}$. This denotes the [[equivalence]] class.
