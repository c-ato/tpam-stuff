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
> This means that a manifold is infinitely differentiable after $f$ is mapped by a local chart to Euclidean space.
 ^def-cat-mani-smoo

> [!definition|*]- Diffeomorphism
> A map is diffeomorphic if $f$ is bijective, $f:M\to N$ and $f^{-1}:N\to M$. It is also required that $f$ and $f^{-1}$ are both smooth.
 ^def-cat-diffeo

> [!definition|*]- Bordism Category $(\text{Bord}_{d})$
> - The objects of this category are closed, orientable, smooth $(d-1)$-dimensional manifolds. Let $\Sigma_{1},\Sigma_{2}$ be two distinct objects of this category.
> - The morphisms of this category are $d$-dimensional manifolds $M$, with boundaries $\partial M$ being composed of $\partial_{in} M$ and $\partial_{out}M$. The boundary $M$ is then defined as $\partial M=\partial_{in} M\sqcup\partial_{out}M$. The 2 boundaries are diffeomorphic to $\Sigma_{1}$ and $\Sigma_{2}$, $f: \partial_{in} M\to \Sigma_{1}$ and $g:\partial_{out}M\to\Sigma_{2}$. Overall we may compose and simply write as such $g^{-1}\circ f=M:\Sigma_{1}\to\Sigma_{2}$.
> - It will also need to be able to compose as typical of categories and have an identity morphism.
 ^def-cat-bord

> [!definition|*]- Functors
> Let $\mathcal{C}$ and $\mathcal{D}$ be categories, $X,Y$ be $\text{Obj}(\mathcal{C})$, $f:X\to Y,g:Y\to X$, and then the functor $F: \mathcal{C}\to \mathcal{D}$ so that it maps each object in $\mathcal{C}$ to $\mathcal{D}$, $F(X)\implies\text{Obj}(\mathcal{D})$. 
> The same for each morphism $f$ such that $F(f):F(X)\to F(Y)$, while also preserving the identity(ies): $F(I_{\mathcal{C}})=I_{\mathcal{D}}$ and $F(g\circ f)=F(g)\circ F(f)$.
 ^def-cat-functor

> [!definition|*]- Bifunctor
> This is much like a functor but takes two input categories and out puts one. 
> Let $\mathcal{C},\mathcal{D}$ and $\mathcal{E}$ be categories, $F: \mathcal{C} \times \mathcal{D}\to \mathcal{E}$ so that it maps each object in the product category $\mathcal{C}\times\mathcal{D}$ to $\mathcal{E}$, $F(\text{Obj}(\mathcal{C\times D}))\implies\text{Obj}(\mathcal{D})$ with the following properties:
> - The product category objects are pairs of objects $(C,D)$ where $C∈\text{Obj}(\mathcal{C})$ and $D∈\text{Obj}(\mathcal{D})$
> - Its morphisms are pairs of morphisms $(f,g)$ where $f∈\text{Hom}(C_{1}​,C_{2}​)$ and $g∈\text{Hom}(D_{1}​,D_{2}​)$.
> - Composition is component-wise: $(f_{2}​,g_{2}​)∘(f_{1}​,g_{1}​)=(f_{2}​∘f_{1}​,g_{2}​∘g_{1}​)$.
> - $F(\text{id}_{\mathcal{C}}​,\text{id}_{\mathcal{D}}​)=\text{id}_{\mathcal{E}}​$
> - $I_{\mathcal{C}}\otimes I_{\mathcal{D}}=I_{\mathcal{C}\otimes \mathcal{D}}$
 ^def-

> [!definition|*]- Tensor Product
> This takes objects of a category, $A,B$, to make a new object $A\otimes B$. It also needs to satisfy for composition for morphisms $f:A\to A'$ and $g:B\to B'$: $f\otimes g:A\otimes B\to A'\otimes B'$, and for the identity $\text{id}_{A}\otimes \text{id}_{B}=\text{id}_{A\otimes B}$.
 ^def-cat-tens-prod

> [!definition|*]- Monoidal Category
> As a category it will naturally require objects, morphisms between them, along with morphism composition and an identity morphism. It will also need the additional structures of:
> - A tensor product - a bifunctor
> - A unit object that acts as an identity for the tensor product
> - Associativity isomorphism, for $A,B,C$ of a category satisfies $(A\otimes B)\otimes C$ is isomorphic with $A\otimes (B\otimes C)$ 
> - Identity isomorphism, for $λ_{A}​:I⊗A≅A$ and $ρ_{A}​:A⊗I≅A$
 ^def-cat-monoid

