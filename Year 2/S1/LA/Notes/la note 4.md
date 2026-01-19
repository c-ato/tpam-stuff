> [!proposition|*]- Inner product as vectors and transposed vector (covector)
> $$\left< f(\mathbf{v}),\mathbf{w} \right>  _{W}=\left< A\mathbf{v},\mathbf{w} \right>  _{W}=\mathbf{y}^{T}A\mathbf{x}$$
> Where $\mathbf{v}=x_{1}\mathbf{v_{1}}+\dots+x_{n}\mathbf{v_{n}}$ and $\mathbf{w}=y_{1}\mathbf{w_{1}}+\dots+y_{n}\mathbf{w_{n}}$
 ^prp-la-inn-vec-covec

> [!definition|*]- Adjoint map
> Let $V$ and $W$ be equipped with an inner product space and $f^{*}:W\to V$ which is the adjoint of $f$ such that:
> $$\left< f^{*}(\underline{w}),\underline{v} \right>_{V} =\left< \underline{w},f(\underline{v}) \right> _{W}\qquad \text{(implicit)}$$
> $$f^{*}(\underline{w})=\sum_{i=1}^{n}\left< \underline{w},f(\underline{v}_{i}) \right>_{W}  \underline{v}_{i}\qquad \text{(explicit)}$$
 ^def-la-adjo-map

> [!theorem|*]- Property of adjoint map
> $f^{*}$ is linear, unique and the adjoint of the adjoint is $(f^{*})^{*}=f$
 ^thm-la-prop-adj

> [!definition|*]- Self Adjoint
> $f=f^{*}$
 ^def-la-self-adj

$\implies A=A^{T}$ or in other words, symmetric

> [!proposition|*]- Spectral results for self ajoint maps
> Where $f$ is a self-adjoint map on $V$. Then the eigenpair of $f$ satisfy:
> - $\lambda$ are real
> - $\underline{v}$ can be taken to be real
 ^prp-

 > [!proposition|*]- 
> $$ker(f^{*})=(\mathrm{Im}f)^{T}$$
 ^prp-

> [!corollary|*]- 
> $ker f = (\mathrm{Im}f^{*})^{\perp}$
> $(ker f^{*})^{\perp} = \mathrm{Im}f$
> $(ker f)^{\perp}=\mathrm{Im} f^{*}$
 ^cor-la-

> [!theorem|*]- Real Spectrum Theorem
> Where $f$ is a self ajoint map with respect to an inner product on $V$. Then
> - $f$ is diagonalisable with real eigenvectors
> - With eigenvectors that can be taken to be real and orthonormal, with respect to $\left< \cdot,\cdot \right>$
 ^thm-la-real-spec-thm

> [!corollary|*]- 
> $A$ is symmetric so then is diagonisable with real eigenpairs $q_{i}$ which are orthonormal. Moreover, $$A=QDQ^{T}$$
> where $D=d_{ii}=\lambda_{i}$ for $i\leq n\in \mathbb{N}$
 ^cor-