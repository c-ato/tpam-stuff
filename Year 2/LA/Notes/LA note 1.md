> [!definition|*]- Finite-dimensional vector space
> A Vector space $V$ is finite dimensional if it has a finite spanning set, otherwise $V$ is called infinite dimensional
 ^def-LA-fini-dim-vec-soa

> [!theorem|*]- Dimension of Vector Space Sum
> Let $U,V$ be two subspaces of a finite dimensional vector space. Then
> $$\dim(U+V)=\dim (U)+\dim(V)-\dim(U\cap V)$$
 ^thm-la-dir-sum-dim

> [!corollary|*]- Dimension of direct sum
> Let $U,V$ be two subspaces of a finite dimensional vector space and define $X=U+V$, then
> $$X=U\oplus V\implies \dim(X)=\dim(U)+\dim(V)$$
 ^cor-

![[Basis#^def-vgla-coord]] 

> [!proposition|*]- Coordinate map
> Let $B=\{ \vec{v}_{1},\vec{v}_{2},\dots,\vec{v}_{n} \}$ then $\vec{v}=\lambda_{1}\vec{v}_{1}+\lambda_{2}\vec{v_{2}+\dots+\lambda_{n}\vec{v_{n}}}$. The coordinate map is then defined as $\varphi:V\to \mathbb{F}^{n}$.
> This is also a bijective that satisfy the linearity condition: $\varphi(a\mathbf{x}+b\mathbf{y})=a\varphi(\mathbf{x})+b\varphi(\mathbf{y})$ 
 ^prp-la-coord-map


> [!definition|*]- Inner Product
> Let $V(\mathbb{R})$ be a real vector space. A real inner product is a function $\left< \cdot,\cdot \right>:V\times V\to \mathbb{R}$ which satisfies:
> - Symmetry, $\left< \vec{v},\vec{w} \right>=\left< \vec{w},\vec{v} \right>$
> - Linearity, $\left< a\vec{u}+b \vec{v},\vec{w} \right>=a \left< \vec{u},\vec{w} \right>+b\left< \vec{v},\vec{w} \right>$
> - Non-negative, $\left< \vec{v},\vec{v} \right> \geq 0$ where $\left< \vec{v},\vec{v} \right>=0 \iff \vec{v}=0$
 ^def-la-inner-prod

> [!definition|*]- Complex inner product
> Let $V(\mathbb{C})$ be a complex vector space. A real inner product is a function $\left< \cdot,\cdot \right>:V\times V\to \mathbb{C}$ which satisfies:
> - Symmetry, $\left< \vec{v},\vec{w} \right>=\overline{\left< \vec{v},\vec{w} \right>}$
> - Linearity, $\left< a\vec{u}+b \vec{v},\vec{w} \right>=a \left< \vec{u},\vec{w} \right>+b\left< \vec{v},\vec{w} \right>$
> - Non-negative, $\left< \vec{v},\vec{v} \right> \geq 0$ where $\left< \vec{v},\vec{v} \right>=0 \iff \vec{v}=0$
 ^def-la-comp-inner-prod

> [!definition|*]- Inner product spaces
> A vector space $V (\mathbb{F})$ equipped with an inner product $⟨·, ·⟩ : V × V → \mathbb{F}$ is called an inner product space.
 ^def-la-inn-prod-spa

> [!definition|*]- Length/norm of vectors
> Let $V (\mathbb{F})$ be an inner product space equipped with an inner product $⟨·, ·⟩$. For any vector $\vec{v} ∈ V$ we denote its length or norm by $∥\vec{v}∥$ and define it via$$\mid\mid \vec{v}\mid \mid=\sqrt[  ]{ \left< \vec{v},\vec{v} \right>  }$$ 
 ^def-la-norm

> [!theorem|*]- Cauchy-Schwarz Inequality
> Let $∥·∥$ denote the norm induced by a real inner product on a vector space $V (\mathbb{R})$. Then $$\left| \left< \vec{u},\vec{v} \right>  \right|\leq \left| \left| \vec{u} \right| \right|\left| \left| \vec{v} \right| \right|$$
 ^thm-la-cauchy-schwarz

> [!theorem|*]- Triangle inequality
> Let $V(\mathbb{R}$ be an inner product space. Then for any $\vec{u},\vec{v}\in V$ there holds $$\left| \left| \vec{u}+\vec{v} \right| \right|\leq \left| \left| \vec{u} \right| \right|+\left| \left| \vec{v} \right| \right|$$
 ^thm-la-trian-ineq

> [!theorem|*]- Length of scaled vector
> Let $V (\mathbb{R})$ be an inner product space. Then for any $v ∈ V$ and $a ∈ \mathbb{R}$, there holds $$\left| \left| a \vec{u} \right| \right|=\left| a \right|\left| \left| \vec{u} \right| \right|$$
 ^thm-la-len-sca-vec

> [!definition|*]- Vector angle 
> Let $V (\mathbb{F})$ be an inner product space equipped with an inner product $⟨·, ·⟩$. The angle $α$ between two non-zero vectors $\vec{u}, \vec{v} ∈ V$ is defined via $$\cos\alpha= \frac{\left< \vec{u},\vec{v} \right> }{\left| \left| \vec{u} \right| \right|\left| \left| \vec{v} \right| \right|}$$
 ^def-la-vec-ang

> [!definition|*]- Orthogonal vectors
> Let $V (\mathbb{R})$ denote an inner product space. Then the nonzero vectors $\vec{u}, \vec{v} ∈ V$ are said to be orthogonal if $⟨u, v⟩ = 0$. We write $\vec{u} ⊥ \vec{v}$.
 ^def-la-orthog-vec

> [!definition|*]- Orthogonal set
> Let $(V, ⟨·, ·⟩)$ be an inner product space. Let $S = \{v_{1}, v_{2}, \dots , v_{k}\}$ be a set of nonzero vectors in $V$ . Then $S$ is said to be orthogonal if for all $i \neq j$ $$⟨\vec{v_{i}}, \vec{v_{j}} ⟩ = 0$$
 ^def-la-orthog-set

> [!theorem|*]- Orthogonal set is linearly independent
> 
 ^thm-la-orthog-lin-indep

> [!definition|*]- Orthogonal basis
> Basis set of $(V,\left< \cdot,\cdot \right>)$ that is also an orthogonal set
 ^def-la-orthog-bas
