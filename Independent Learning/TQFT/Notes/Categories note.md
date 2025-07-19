---
tags:
  - maths
  - physics
  - topology
  - quantum
  - category
PDF URI: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2FGoogle%20Gemini.html
Note number: 1
URI base: obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FCategories%20note%20
Title Stem: Categories
---

<div style="display: flex; justify-content: center; gap: 10px;">
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FNotes%2FCategories%20note%202" class="button">Next
	</a> 
	<a 
	href="obsidian://open?vault=tpam%20stuff&file=Independent%20Learning%2FTQFT%2FMaterial%2FGoogle%20Gemini.html class="button>Go to Gemini Chat Log
	</a> 
</div>

> [!definition|*]- Category
> A category, $\mathcal{C}$, needs the following: 
> - $\text{Obj}(\mathcal{C})$ - objects of the category, which the morphisms exist between
> - $\text{Hom}(A,B)$ - a morphisms that "transforms" the domain $A$ to $B$, a function is an example of this $f:A\to B$
> - Composition of morphisms so that if $f:A\to B$ and $g:B\to C$ then $g\circ f:A\to C$ where the codomain of $f$ matches the domain of $g$ and an identity morphism $I:A\to A$. 
> They must also satisfy: 
> - Associativity, where $h:C \to D$ - $(h\circ g)\circ f= h\circ (g\circ f)$
> - An identity morphism for both $I_{A}\circ f=f$ and $f \circ I_{B}$
 ^def-cat

> [!definition|*]- Smooth (Manifold)
> This means that a manifold is infinitely differentiable after it is locally mapped by a chart to a Euclidean space.
 ^def-cat-mani-smoo

> [!definition|*]- Diffeomorphism
> A map is diffeomorphic if $f$ is bijective, $f:M\to N$ and $f^{-1}:N\to M$. It is also required that $f$ and $f^{-1}$ are both smooth.
 ^def-cat-diffeo

> [!definition|*]- Functors
> Let $\mathcal{C}$ and $\mathcal{D}$ be categories, $X,Y$ be of $\mathcal{C}$, $f:X\to Y,g:Y\to X$, and then the functor is $F: \mathcal{C}\to \mathcal{D}$ so that it maps each object in $\mathcal{C}$ to $\mathcal{D}$, $F(X)\implies\text{Obj}(\mathcal{D})$. 
> 
> The same for each morphism $f$ such that $F(f):F(X)\to F(Y)$, while also preserving the identity: $F(I_{\mathcal{C}})=I_{\mathcal{D}}$ and $F(g\circ f)=F(g)\circ F(f)$.
 ^def-cat-functor

> [!definition|*]- Bifunctor
> This is much like a functor but takes two input categories and out puts one. 
> Let $\mathcal{C},\mathcal{D}$ and $\mathcal{E}$ be categories, $F: \mathcal{C} \times \mathcal{D}\to \mathcal{E}$ so that it maps each object in the product category $\mathcal{C}\times\mathcal{D}$ to $\mathcal{E}$, $F(\text{Obj}(\mathcal{C\times D}))\implies\text{Obj}(\mathcal{D})$ with the following properties:
> - The product category objects are pairs of objects $(C,D)$ where $C∈\text{Obj}(\mathcal{C})$ and $D∈\text{Obj}(\mathcal{D})$
> - Its morphisms are pairs of morphisms $(f,g)$ where $f∈\text{Hom}(C_{1}​,C_{2}​)$ and $g∈\text{Hom}(D_{1}​,D_{2}​)$.
> - Composition is component-wise: $F(f_{2}​,g_{2}​)∘(f_{1}​,g_{1}​)=F(f_{2}​∘f_{1}​,g_{2}​∘g_{1}​)$.
> - $F(\text{id}_{\mathcal{C}}​,\text{id}_{\mathcal{D}}​)=\text{id}_{\mathcal{E}}​$
> - $F(I_{\mathcal{C}}, I_{\mathcal{D}})=I_{F(\mathcal{C},\mathcal{D})}$
 ^def-cat-bifunct

> [!definition|*]- Tensor Product
> This binary operator $\otimes$ takes two objects of a single category, $\mathcal{C}$ satisfies the following:
> - $A,B$ of $\mathcal{C}$ to make a new object $A\otimes B$
> - It also needs to satisfy for composition for morphisms: $A',B'$ are of $\mathcal{C}$, $f:A\to A'$ and $g:B\to B'$ such that $f\otimes g:A\otimes B\to A'\otimes B'$
> - Finally for the identity $\text{id}_{A}\otimes \text{id}_{B}=\text{id}_{A\otimes B}$ to be true
 ^def-cat-tens-prod

> [!definition|*]- Bordism Category $(\text{Bord}_{d})$
> As a category this will naturally need objects, morphisms, composition of morphisms, associativity and finally an identity morphism, but there are additional properties which are the following:
> - The objects of this category are closed, orientable, smooth $(d-1)$-dimensional manifolds. Let $\Sigma_{1},\Sigma_{2}$ be two distinct objects of this category, being outgoing and incoming respectively.
> - The morphisms of this category are $d$-dimensional manifolds $M$
> 	- The boundaries $\partial M$ is composed of $\partial_{in} M$ and $\partial_{out}M$ which are disjoint $(\partial M=\partial_{in} M\sqcup\partial_{out}M)$ which is the tensor product of $\text{Bord}_{d}$
> 	- The 2 boundaries are diffeomorphic to $\Sigma_{1}$ and $\Sigma_{2}$, $f: \partial_{in} M\to \Sigma_{1}$ and $g:\partial_{out}M\to\Sigma_{2}$. Overall we may compose and simply write as such $g^{-1}\circ f=M:\Sigma_{1}\to\Sigma_{2}$.
 ^def-cat-bord

> [!definition|*]- Symmetric Monoidal Category
> Once again, as a category it will naturally require objects, morphisms between them, along with morphism composition and an identity morphism. It will also need the additional structures of:
> - A tensor product - a bifunctor
> - A unit object that acts as an identity for the tensor product
> - Associativity isomorphism, for $A,B,C$ of a category satisfies $(A\otimes B)\otimes C$ is isomorphic with $A\otimes (B\otimes C)$ 
> - Identity isomorphism, for $λ_{A}​:I⊗A≅A$ and $ρ_{A}​:A⊗I≅A$
>
> This makes for a monoidal category, but additional properties are required for it to be symmetric. A symmetry isomorphism $\sigma_{x,y}:x \otimes y\to y\otimes x$, $F:A\to A'$ and $G:B\to B'$ satisfies the following:
> $$\begin{array}{ccc}A \otimes B & \xrightarrow{\sigma_{A,B}} & B \otimes A \\\downarrow F\otimes G & & \downarrow G\otimes F \\ A' \otimes B' & \xrightarrow{\sigma_{A',B'}} & B' \otimes  A' \end{array}$$
 ^def-cat-monoid

> [!definition|*]- Symmetric Monoidal Functor
> Let $A,B$ be objects of $\mathcal{C}$, a functor $F: \mathcal{C}\to \mathcal{D}$, a coherence isomorphism ("decomposer") $\psi_{A,B}:F(A \otimes_{\mathcal{C}}B)\to F(A)\otimes_{\mathcal{D}}F(B)$ and finally where $\otimes_{\mathcal{E}}$ is the tensor product of a given category $\mathcal{E}$.
> 
> A symmetric monoidal functor satisfies the following:
> $$\begin{array}{ccc}F(A \otimes_\mathcal{C} B) & \xrightarrow{F(\sigma_{A,B})} & F(B \otimes_\mathcal{C} A) \\\downarrow \psi_{A,B} & & \downarrow \psi_{B,A} \\F(A) \otimes_\mathcal{D} F(B) & \xrightarrow{\sigma_{F(A),F(B)}} & F(B) \otimes_\mathcal{D} F(A)\end{array}$$
 ^def-cat-sym-monoi-funct

> [!definition|*]- TQFT
> This is a symmetric monoidal functor between $Z:\text{Bord}_{d}\to\text{Vect}_{k}$. It will naturally have the properties of a functor:
> - The objects of $\text{Bord}_{d}$, $\Sigma$, of $(d-1)$-dimensions are mapped to a $k$-vector space $Z(\Sigma)\implies Vect_{k}$
> - It also implies the empty manifold maps to the base field $k$, $Z(\varnothing)=k$ (each respectively the unit object,)
> - The $d$-dimension morphisms, $M:\Sigma_{0}\to\Sigma_{1}$, map to $k$-linear maps, $Z(M):Z(\Sigma_{0})\to Z(\Sigma_{1})$. We can then call $Z(M)$ a transition operator (much in the same vein as transition maps of Riemann surfaces)
> - The linear map of a composition of morphisms is the same as the composition of linear maps of morphisms, $Z(M_{1}\circ M_{2})=Z(M_{1})\circ Z(M_{2})$
> - $Z(I_{\Sigma})=I_{Z(\Sigma)}$
> - The map of disjoint unions of $\Sigma$ and $M$ are isomorphic to the tensor product of the maps of each disjoint $\Sigma$ and $M$ respectively, $Z(\Sigma_{1}​\sqcup\Sigma_{2}​)\simeq Z(\Sigma_{1}​)\otimes Z(\Sigma_{2}​)$ and $Z(M_{1}​\sqcup M_{2}​)\simeq Z(M_{1}​)\otimes Z(M_{2}​)$
> - It respects symmetry (commutations of the tensor products) as seen in the diagram of the definition of symmetric monoidal functor
 ^def-cat-tqft

