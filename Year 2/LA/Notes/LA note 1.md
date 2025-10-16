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
 ^thm-la-orthog-lin-indep

> [!definition|*]- Orthogonal basis
> Basis set of $(V,\left< \cdot,\cdot \right>)$ that is also an orthogonal set
 ^def-la-orthog-bas

> [!theorem|*]- Coordinate inner product equality
> Let $(V, ⟨·, ·⟩)$ be an inner product space, with $B=\{ \vec{v_{1}},\vec{v_{2}},\dots,\vec{v_{n}} \}$ as an orthogonal basis of $V$. Then the coordinates $a_{i}$ of any vector $\vec{v}\in V$ is given as $$a_{i}=\frac{\left< \vec{v},\vec{v_{i}} \right> }{\left< \vec{v_{i}},\vec{v_{i}} \right> }$$
 ^thm-la-coord-inn-pro-eq

> [!definition|*]- Orthonormal set
> Let $(V, ⟨·, ·⟩)$ be an inner product space. A set $S$ of non-zero vectors $e_{i}$ is said to be orthonormal if it satisfies: $$\left< \vec{e_{i}},\vec{e_{j}} \right> =\delta_{ij}:=\left\{ \begin{matrix}0& i\neq j \\1 & i=j\end{matrix} \right. \quad\forall i,j \in 1,2,\dots,\left| S \right|$$
 ^def-la-orth-norm-set

> [!definition|*]- Orthonormal basis
> Basis set of $(V,\left< \cdot,\cdot \right>)$ that is also an orthonormal set
 ^def-la-orthog-bas

> [!theorem|*]- Inner product operation
> Let $(V, ⟨·, ·⟩)$ be an inner product space with dimension $n$, such the bases is $B=\{ \vec{e_{i}}:1\leq i\leq n,i \in \mathbb{N} \}$ and is also a orthonormal basis. Then let $\vec{u},\vec{v}$ have the respective coordinates of $a_{i},b_{j}$ with $i,j\in[1,2,..,n]$ so $$\left< \vec{u},\vec{v} \right> =a_{1}b_{1}+a_{2}b_{2}+\dots+a_{n}b_{n}$$
 ^thm-la-inn-prod-op

> [!definition|*]- Orthogonal (vector) projection 
> Let $(V, ⟨·, ·⟩)$ be an inner product space and let $\vec{u}\in V\setminus \{ 0 \}$. The orthogonal projection of $\vec{v}$ onto $\vec{u}$ denoted $\vec{v_{u}}^{\parallel}$ is $$\vec{v_{u}}^{\parallel}:=\frac{\left< \vec{v},\vec{u} \right> }{\left< \vec{u},\vec{u} \right> }\vec{u}$$
 ^def-la-orthog-vec-proj

$$\vec{v}=\vec{v_{u}^{_{\parallel}}}+\vec{v_{u}^{_{\perp}}}\implies \vec{v_{u}^{_{\perp}}}=\vec{v}-\frac{\left< \vec{v},\vec{u} \right> }{\left< \vec{u},\vec{u} \right> }\vec{u}$$

> [!theorem|*]- Orthonormal of a subspace is orthonormal to the span
> Let $(V, ⟨·, ·⟩)$ be an inner product space and let $U$ be a subspace $V$ where $S$ is the spanning set of $U$. Then $$\vec{v} \perp U\iff \vec{v}\perp S$$
 ^thm-la-orthon-sub-orthon-span

> [!theorem|*]- Perpendicular vector of a subspace
> Let $(V, ⟨·, ·⟩)$ be an inner product space and let $U$ be a subspace of $V$ . Let $\vec{v} ∈ V$ . Then there exists a unique vector $\vec{v}^{\parallel}_{U} ∈ U$ such that $\vec{v}^{\perp}_{U} := \vec{v} − \vec{v}^{\parallel}_{U} ⊥ U$ 
 ^thm-la-perp-subspa

> [!definition|*]- Orthogonal (vector) projection (onto a subspace)
> Let $(V, ⟨·, ·⟩)$ be an inner product space and let $U$ be a subspace of $V$ spanned by an orthogonal basis set $B=\{ \vec{u_{i}}:i\in [1,2,\dots,k] \}$. Let $\vec{v}\in V$. The orthogonal projection of $\vec{v}$ onto $U$ is the vector $$\vec{v}_{U}^{\parallel}=\sum^{k}_{i=1} \frac{\left< \vec{v},\vec{u_{i}} \right> }{\left< \vec{u_{i}},\vec{u_{i}} \right> }\vec{u_{i}}$$
 ^def-la-orthog-vec-proj-subspa

> [!definition|*]- Orthogonal complement
> Let $(V, ⟨·, ·⟩)$ be an inner product space and let $U$ be a subspace of $V$. The orthogonal complement of $U$ in $V$ is denoted by $U^{\perp}$ and is defined to be the set of vectors in $V$ perpendicular to $U$ $$U^{\perp}:=\{ \vec{v}\in V: \vec{v}\perp U \}$$
 ^def-la-orthog-comple

> [!lemma|*]- No intersection with orthogonal complement
> $$U\cap U^{\perp}=\{ 0 \}$$
 ^lem-int-orthog

> [!lemma|*]- Direction sum of subspace and its complement is entire vector space
> $$V=U\oplus U^{\perp}$$
 ^lem-