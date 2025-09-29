---
tags:
  - maths/vectors
  - concepts
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
