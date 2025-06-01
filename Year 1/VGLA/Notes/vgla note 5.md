---
tags:
  - maths
  - algebra
---
> [!definition|*]- Permutation
> A bijective function that takes a set and rearranges it:
> $$\sigma:\{ 1\dots n \}\to \{ 1\dots n \}$$
> The set of all permutations of a set is denoted by $S_{n}$ and is called the symmetric group on the set
 ^def-vgla-permu
  
> [!definition|*]- Identity permutation
> This is a permutation that gives that the same set denoted by $\sigma_{Id}$
 ^def-vgla-permu-id

> [!definition|*]- Inverse permutation
> Suppose that there is a permutation s.t. $i,j\in\{ 1\dots n \}$ with $i<j$ and $\sigma(i)>\sigma(j)$ the pair $(i,j)$ is called an inversion of $\sigma$
> Define $N:S_{N}\to \mathbb{N_{0}}$ by 
> $$N(\sigma)\left| \{ (i,j):(i,j)\text{ is an inversion of }\sigma \} \right| $$
> So $N(\sigma)$ is the number of inversions in $\sigma$.
> A permutation $\sigma \in S_{n}$ is an odd permutation $\iff N(\sigma)$ is odd. A permutation which is not odd is even.  
 ^def-vgla-permu-invs

> [!definition|*]- Determinant
> Let $\mathbf{A}\in\mathcal{M_{nm}}(\mathbb{R})$. The determinant of $\mathbf{A}=[a_{ij}]$, denoted by $\\det(A)$ or $|A|$is given by
> $$\sum_{\sigma \in S_{n}}(-1)^{N(\sigma)}\prod^{n}_{i=1}a_{\sigma(i)i}$$
 ^def-vgla-determ

> [!definition|*]- Transpose matrix
> $A^{T}=[b_{ij}]\in \mathcal{M}_{nm}(\mathbb{R})$ of $A=[a_{ij}]\in \mathcal{M_{nm}}(\mathbb{R})$ is the matrix with $b_{ij}=a_{ji}$
 ^def-vgla-transp-mat

> [!theorem|*]- Transpose identity
> $$(A_{1}\cdot A_{2}\cdot A_{3}\dots A_{k})^{T}=A_{k}^{T}\cdot A_{k-1}^{T}\dots A_{2}^{T}+A_{1}^{T}$$
 ^thm-vgla-transp-mat-ident

> [!theorem|*]- Transpose determinent identity
> $\det(A)=\det(A^{T})$
 ^thm-vgla-transp-mat-det-ident

ERO on matrix:
Multiply a a row or column by $\lambda$ causes $\det(A)\to\lambda \det(A)$. A matrix with a row or column of $0\implies\det(A)=0$. Swapping rows or columns the determinant $\det(A)\to-\det(A)$. A matrix with 2 same rows or columns will have $\det(A)=0$. Add multiple of a row or column to another: $\det(A)=\det (A)$
