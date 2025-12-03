> [!definition|*]- Spectrum
> $$sp(f):=\{ \lambda \in \mathbb{F} :f(\mathbf{v})=\lambda \mathbf{v},\mathbf{v}\in V \}$$
 ^def-la-spectrum

Eigenvectors are not unique.

Two interpretation of analysis: $\det(\lambda I_{n}-A)=0$ and $\underline{x} \in ker(\lambda I_{n}-A)$

> [!definition|*]- Characteristic Polynomial
> Let $A \in \mathbb{F}^{n\times n}$. The characteristic polynomial of $A$ is the polynomial $p_{A}\in \mathcal{P}_{n}(\mathbb{F})$  defined via $$p_{A}(t)=\det(tI-A)$$
 ^def-la-char-polyn

With this the EVP (eigenvalue problem) is equivalent to finding the roots of $p_{A}(t)$ such that $p(\lambda)=0$

> [!theorem|*]- Fundamental Theorem of Algebra
> All polynomials $p \in \mathcal{P}_{n}(\mathbb{R})$ has a zero in $\mathbb{C}$ for any $n \in \mathbb{N}$
 ^thm-la-fund-thm-alg

infers that $n$ complex eigenvalues, $\lambda_{i }\in \mathbb{C}\forall i\leq n\in \mathbb{N}$ for 

> [!definition|*]- Irreducible polynomial
>  A monic quadratic polynomial with real coefficients $p ∈ \mathcal{P}_{2}(\mathbb{R})$ is called irreducible if it has the form $$p(t) = (t − z)(t - \bar{z}) = t − 2\mathrm{Re}(zt) + |z|^{2} $$
>  with $z ∈ \mathbb{C}$ and $\mathrm{Im}(z) \neq 0$
 ^def-la-irred-poly

> [!definition|*]- Algebraic Multiplicity
> Where $V$ is an $n$-dimensional vector space and $f \in \mathcal{L}(V)$. The algebraic multiplicity of an eigenvector $\lambda_{k}$ of $f$ is $\alpha_{k}$. Where $\alpha:sp(f)\to \{ 1,2,\dots,n \}$
 ^def-la-alg-multi

 > [!definition|*]- Eigenspace
> The subspace $E_{\lambda}$ is the eigenspace of $f$ associated with eigenvalues such that $E_{\lambda}:= ker(f-\lambda Id_{V})$
 ^def-la-eigen-spa

> [!definition|*]- Geometric multiplicity
> The geometric multiplicity of $\lambda$ is denoted as $\gamma(\lambda)$ and is the dimension of the eigenspace associated with it: $\gamma(\lambda):=\dim kerE_{\lambda}$
 ^def-la-geo-mult

> [!definition|*]- Defective matrix
> We say a matrix $A \in \mathbb{C}^{n\times n}$ is defective if it does not have $n$ linearly independent eigenvectors. Or mathematically
> $$\sum^{k}_{i=1}\gamma(\lambda_{i})<n$$
 ^def-la-defec-mat

> [!theorem|*]- Eigenvalue decomposition and canonical form
> Let $A \in \mathbb{C}^{n\times n}$ be a square, non-defective matrix. Then $A$ is diagonalisable with canonical form $A = X^{-1}DX$, where $$D_{ii} = λ_{i} ∈ \mathbb{C},\qquad\mathbf{c}_{i}(X) = \mathbf{x}_{i} ∈ \mathbb{C} ^{n}, \qquad i = 1, 2, \dots , n$$
> where $(\mathbf{v}_{i},\lambda_{i})$ are eigenpairs of A for $1\leq i\leq n$.
 ^thm-la-eig-decomp

> [!proposition|*]- Invariant Subspace
> Where $f\in \mathcal{L}(V)$ and $U\leq V$, with $\dim U=k$ and $\dim V=n$. Then $U$ is $f$-invariant $\iff$ it has a block triangular matrix representation of the form:
> $$A=\begin{bmatrix}A_{U}&B \\O&C\end{bmatrix}$$
> where $A_{U}\in \mathbb{C}^{k\times k},O\in \mathbb{C}^{(n-k)\times k},B\in \mathbb{C}^{k\times (n-k)},C\in \mathbb{C}^{(n-k)\times (n-k)}$
 ^prp-la-invar-subspa

> [!proposition|*]- 
> Where $\lambda=a+bi$
> $$\text{sp}\begin{bmatrix}\lambda &  \\& \bar{\lambda}\end{bmatrix}=\text{sp}\begin{bmatrix}a & b \\-b& a\end{bmatrix}$$
 ^prp-

complex vector broken into real and imaginary components are linearly independent

> [!theorem|*]- Real decompostion of $A$
> Let $A \in \mathbb{R}^{n\times n}$ be non-defective. Then $A=MDM^{-1}$ where
 ^thm-