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

