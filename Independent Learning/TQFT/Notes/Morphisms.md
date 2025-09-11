---
tags:
  - concepts
  - maths/topology
aliases:
  - homomorphisms
  - homomorphic
  - diffeomorphic
  - diffeomorphisms
  - diffeomorphism
  - morphism
  - homomorphism
  - isomorphism
  - isomorphisms
  - isomorphic
  - holomorphism
  - holomorphisms
  - holomorphic
  - automorphism
  - automorphisms
  - automorphic
---
> [!definition|*]- Homomorphisms
> There are 2 [[Equivalence|equivalent]] definitions:
> 1. This is the notion of equality (invariance) in [[topology]].
> A homomorphism is a function $f : X → Y$ between two [[Topology|topological]] spaces $X$ and $Y$ that:
> - is continuous bijective 
> - has a continuous inverse function $f^{-1}$
> 2. Two [[Topology|topological]] spaces $X$ and $Y$ are said to be homomorphic if there are continuous map $f : X → Y$ and $g : Y → X$ such that 
> $$f ◦ g = I_{Y} \qquad \text{and}\qquad g ◦ f = I_{X}$$
>  Moreover, the maps $f$ and $g$ are homeomorphisms and are inverses of each other, so we may write $f^{-1}$ in place of $g$ and $g^{-1}$ in place of $f$. Where $I_{X}$ and $I_{Y}$ denote the identity maps.
 ^def-top-homomo

> [!example|*]- Any open interval of $\mathbb{R}$ is homomorphic to any other open interval. 
> Consider $X = (−1, 1)$ and $Y = (0, 5)$. Let $f : X → Y$ be $$f (x) = \frac{5}{2} (x + 1)$$
> Observe that $f$ is bijective and continuous, being the compositions of addition and multiplication. Moreover, $f^{-1}$ exists and is continuous:$$f ^{-1}(x) = \frac{2}{5} x − 1$$
> Note that neither $[0, 1]$ nor $[0, 1)$ is homomorphic to $(0, 1)$ as such mapping between these intervals, if constructed, will fail to be a bijection due to endpoints.
 ^exm-top-homo-O-2-O

> [!example|*]- There exists homomorphism between a bounded and an unbounded set
> $$f(x)=\frac{1}{x}$$
> Then it follows that $(0, 1)$ and $(1, ∞)$ are homomorphic.
 ^exm-top-homo-fin-inf

> [!example|*]- A Topologist cannot tell the difference between a Circle and Square...
> A circle is given as $S^{1}=\{ (x,y)\in \mathbb{R}^{2}|x^{2}+y^{2}=1 \}$ and a square $T=\{ (x,y)\in \mathbb{R}^{2} \}$. We may define a function $f:S^{1}\mapsto T$ defined by$$f(x,y)=\left( \frac{x}{\left| x \right|+\left| y \right|}, \frac{y}{\left| x \right|+\left| y \right|} \right)$$
> which is continuous, bijective and has a continuous inverse$$f^{-1}(x,y)=\left( \frac{x}{\sqrt[  ]{ x^{2}+y^{2} }}, \frac{y}{\sqrt[  ]{ x^{2}+y^{2} }} \right)$$
> Both circle and square are therefore topologically identical. $S^{1}$ and $T$ are sometimes called simple closed curves (or Jordan curves).
 ^exm-top-circ-squar

> [!example|*]- Circle ($S^{1}$) to $\mathbb{R}^{1}$ 
> $S^{1}$ with a point removed is homomorphic with $\mathbb{R}$. Without loss of generality, suppose we removed the North Pole. Then the stereographic projection is a homomorphism between the real line and the remaining space of $S^{1}$ after a point is omitted. 
> 
> Place the circle “on” the $x$-axis with the point omitted being directly opposite the real line. More precisely, let $S^{1} = \left\{ (x, y) ∈ R | x^{2} +\left( y -\frac{1}{2} \right)^{2} = \frac{1}{4} \right\}$ and suppose the North Pole is $N = (0, 1)$. Using geometry, we may construct $f : S^{1} \setminus N → \mathbb{R}$ by defining $$f (x, y) = \frac{2x}{1-y}$$ $f$ is well-defined and continuous as the domain of $f$ excludes $y = 1$, i.e. the North Pole. With the continuous inverse function $$f^{-1}(x)=\left( \frac{4x}{x^{2}+4}, \frac{x^{2}-4}{x^{2}+4} \right)$$ we have $f ◦ f^{-1} = f^{-1} ◦ f = I$, hence $f$ is a homeomorphism
 ^exm-top-circ-2-R

> [!example|*]- Annulus to open cylinder [[Surfaces|surface]].
> The annulus $A = \{(x, y) ∈ \mathbb{R}^{2} | 1 ≤ x^{2} + y^{2} ≤ 4\}$ is homomorphic to the cylinder $C = \{(x, y, z) ∈ \mathbb{R}^{3} | x^{2} + y^{2} = 1, 0 ≤ z ≤ 1\}$ since there exists continuous function  $f: C → A$ and $g : A → C$ $$f (x, y, z) = ((1 + z)x, (1 + z)y)$$$$g(x, y) = \left( \frac{x}{\sqrt[  ]{ x^{2}+y^{2} }} , \frac{y}{\sqrt[  ]{ x^{2}+y^{2} }} , \sqrt[  ]{ x^{2}+y^{2} } − 1 \right) $$
> such that $f ◦ g = g ◦ f = I$. Thus $f$ and $g$ homomorphisms. Recognise there is a preservation of a hole. 
 ^exm-top-ann-2-cyl

> [!definition|*]- [[Topology|Topological]] Invariant
> A [[Topology|topological]] invariant of a space $X$ is a property that depends solely on the [[topology]] of the space $X$. That is, a property shared by any other space that are homomorphic to $X$. 
> 
> Intuitively, a homeomorphism between $X$ and $Y$ maps points in $X$ that are “close together” to points in $Y$ that are “close together”, and points in $X$ not “close together” to points in $Y$ that are not “close together”.
 ^def-top-invar

> [!theorem|*]- Invariant Homomorphic Properties
> Let $X$ and $Y$ be homomorphic [[Topology|topological]] spaces such that $f:X\mapsto Y$, then if $X$ is [[Connectedness|connected]] or [[Compactness|compact]] or [[Hausdorff]] so is $Y$, where $f$ is injective and continuous.
 ^thm-top-invar-homo-prop

> [!definition|*]- Diffeomorphism
> A map is diffeomorphic if $f$ is bijective, $f:M\to N$ and $f^{-1}:N\to M$. It is also required that $f$ and $f^{-1}$ are both [[Manifolds|smooth]].
 ^def-cat-diffeo

> [!definition|*]- Holomorphic
> Let $R_{1}$ and $R_{2}$ be [[Riemann Surface|Riemann surfaces]] with atlases $A_{1} = \{(\phi_{\alpha}, U_{\alpha})\}$ and $A_{2} = \{(\psi_{\beta} , V_{\beta} )\}$ respectively. A function $f : R_{1} → R_{2}$ is called holomorphic if the composition $ψ_{\beta} ◦ f ◦ \phi ^{-1}_{\alpha} : \phi(U_{\alpha} ∩ f ^{-1}(V_{\beta} )) → ψ(V_{\beta} )$ is holomorphic for each $α$ and $β$.
 ^def-top-riem-holomo

> [!definition|*]- Automorphism
> This is when we have $x,y \in X$ of some structure, satisfies $f:x\to y$ where $f:X\to X$ and $f^{-1}:X\to X$ (if $x=y$ gives the identity). Topologically this is also a homomorphism
 ^def-top-automorphism