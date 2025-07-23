---
Note number: 1
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F1.%20Riemann%20Surfaces%20(recommended).pdf
Title Stem: Riemann Surface
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FRiemann%20Surface%20note%20
tags:
  - maths
  - physics
  - topology
  - quantum
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FRiemann%20Surface%20note%202" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2F1.%20Riemann%20Surfaces%20(recommended).pdf#page=1" class="button">Go to PDF beginning
	</a> 
</div>

![[Surfaces#^def-top-surf]]

> [!definition|*]- First Countable Spaces
> Let $X$ be a topological space, and $x \in X$ such that there is a countable amount of neighbourhoods for each $x$.
 ^def-top-1st-count-spa

> [!definition|*]- Second Countable Spaces
> Let $X$ be a topological space. It is second countable if there exists some countable collection $\mathcal{U} = \{ U_{i} \}^{\infty}_{i=1}$ of open subsets of $X$ such that any open subset of $X$ can be written as a union of elements of some subfamily of $\mathcal{U}$.
 ^def-top-2nd-count-spa

![[vgla note 7#^def-vgla-def]]

> [!definition|*]- Manifold
> This is a topological space, $X$, that locally resembles Euclidean space near each point, or more formally:
> For each $x \in O_{X} \subset  X \exists f:O_{X}\to O_{\mathbb{R}^{n}}\subset \mathbb{R}^{n}$ where $x$ is an arbitrary point, $O$ is a neighbourhood in its respective space and $n$ is the dimension of $X$.
 ^def-top-mani

> [!theorem|*]- Second Countable are First Countable Spaces
> Second countable $\implies$ first countable.
 ^thm-top-2nd-impl-1st-count-spa

> [!definition|*]- A more Complex Surface Definition.
> A surface $S$ is a connected, second countable, Hausdorff topological space with a family of homomorphisms $\phi_{\alpha} : U_{\alpha} → D_{\alpha}$ from domains $U_{\alpha}$ that form an open cover of $S$ to open subsets $D_{\alpha}$ in the complex plane. 
 ^def-top-riem-surf

> [!definition|*]- Charts and Atlas
> The homeomorphisms of a surface are called charts, and the family they belong to is called an atlas $A$ on $S$. We write $A = \{(\phi_{\alpha}, U_{\alpha})\}$.
 ^def-top-chart-atlas

> [!definition|*]- Transition Maps
> If $U_{\alpha_{1}} ∩ U_{\alpha_{2}} \neq \varnothing$ then $\phi_{\alpha_{2}} ◦ \phi ^{-1} _{\alpha_{1}} : \phi(U_{\alpha_{1}} ) → \phi(U_{\alpha_{2}} )$ is, by composition, a homomorphism. Such a map is called a transition map
 ^def-top-trans

> [!definition|*]- Riemann Surface
> If $R$ is a surface with an atlas $A$, and if all transition maps determined by the atlas are holomorphic, then $R$ is called a Riemann surface. 
 ^def-top-riem-surf

> [!definition|*]- Analytic Atlas
> The atlas of a Riemann Surface is an analytic atlas.
 ^def-top-riem-ana-atl

> [!definition|*]- Holomorphic
> Let $R_{1}$ and $R_{2}$ be Riemann surfaces with atlases $A_{1} = \{(\phi_{\alpha}, U_{\alpha})\}$ and $A_{2} = \{(\psi_{\beta} , V_{\beta} )\}$ respectively. A function $f : R_{1} → R_{2}$ is called holomorphic if the composition $ψ_{\beta} ◦ f ◦ \phi ^{-1}_{\alpha} : \phi(U_{\alpha} ∩ f ^{-1}(V_{\beta} )) → ψ(V_{\beta} )$ is holomorphic for each $α$ and $β$.
 ^def-top-riem-holomo

> [!theorem|*]- Conformally Equivalent Riemann Surfaces
>  if $R_{1}$ and $R_{2}$ are Riemann surfaces with a biholomorphic map $f$ between them (that is to say, a holomorphic map with a holomorphic inverse), we say that $R_{2}$ and $R_{2}$ are conformally equivalent.
>  This is a means of classifying Riemann Surfaces.
 ^thm-top-riem-conf-equiv

> [!proposition|*]- Conformal equivalence is an equivalence relation.
 ^prp-top-riem-conf-equiv

> [!definition|*]- Maximal Atlas
> If we have two equivalent atlases on a surface $S$, then their union is also an atlas on $S$ and belongs to the same equivalence class. By combining all atlases on $S$, we may obtain a maximal atlas on $S$.
 ^def-top-max-atl

> [!theorem|*]- Complex Subset is Riemann Surface
> Any open connected subset of the complex plane is a Riemann surface.
 ^thm-top-riem-compl-sub-surf

> [!definition|*]- Automorphism
> This is when we have $x,y \in X$ of some structure, satisfies $f:x\to y$ where $f:X\to X$ and $f^{-1}:X\to X$ (if $x=y$ gives the identity). Topologically this is also a homomorphism
 ^def-top-automorphism

> [!theorem|*]- Riemann Surface on Holomorphic Automorphism
> Let $R$ be a Riemann surface, and let $G$ be a group of holomorphic automorphisms acting on $R$. Then $R/G$ under the quotient topology inherits a natural analytic atlas
 ^thm-top-riem-surf-holo-auto-anal-atl

> [!definition|*]- Curve
> A curve in a surface $S$ is a continuous map $γ : [0, 1] → S$. A curve is closed if $γ(0) = γ(1)$, and simple if $γ(x) = γ(y) \implies x = y$ for $x ∈ (0, 1)$ (that is to say, there are no other points of self-intersection).
 ^def-top-curve

> [!definition|*]- Concatenation
> Suppose we have curves, $\gamma_{1},\gamma_{2}$ satisfying $\gamma_{1}(1)=\gamma_{2}(0)$. We may concatenate them as such:$$\gamma_{2}*\gamma_{1}(t)\left\{ \begin{matrix}\gamma_{1}(2t),  & 0\leq t\leq \frac{1}{2} \\\gamma_{2}(2t-1),  & \frac{1}{2}\leq t\leq 1\end{matrix} \right. $$
 ^def-top-surf-conc

> [!definition|*]- Homotogy
> Let $X, Y$ be topological spaces. Let $f, g : X → Y$ be continuous. A homotopy is a continuous map $H : [0, 1] × X → Y$ such that for all $x ∈ X, H(0, x) = f (x)$ and $H(1, x) = g(x)$. If such a map exists, $f$ and $g$ are said to be homotopic
 ^def-top-homotogy

$[\gamma]=\{ \mu:[0,1]\to S: \mu \sim \gamma \}$. This denotes the equivalence class.

> [!definition|*]- Fundamental Group 
> Let $S$ be a surface, and let $z ∈ S$ be the base point. Let $\Gamma = \{γ : [0, 1] → S : γ(0) = γ(1) = z\}$ (i.e. closed curves with $z$ as the base point). Under concatenation $*,\Gamma$ forms a group. We define the fundamental group of $S$ based at $z$ to be $\pi_{1}(S, z) = \Gamma/\sim$.
 ^def-top-riem-fund-group

For the quotient space to be well defined we need $[\gamma]*[\mu]=[\gamma*\mu]$ and have that the null curve is the identity element, and the inverse element is simply the same curve traced in the opposite direction.
