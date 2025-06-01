---
tags:
  - maths
  - sequences
  - series
---
> [!definition|*]- Subsequence
> Let $(n_{k})^{\infty}_{k=1}$ be a strictly increasing sequence of natural numbers. Then the sequence $(a_{n_{k}})^{\infty}_{k=1}$. $(a_{n_{1}}a_{n_{2}},a_{n_{3}}\dots)$ is a subsequence of $(a_{n})$.
 ^def-sas-subseq

>[!theorem|*]- Inherited property of subsequence 
> If $(a_{n})$ converges and $(a_{n_{k}})$ is a subsequence of $(a_{n})$ then $(a_{n_{k}})$ converges and to the same limit
 ^thm-sas-inher-prop-subseq

> [!corollary|*]- Different subsequence limits, mean main subsequence does not converge
> If $(a_{n})$ has convergent subsequences converging to distinct limits, then $(a_{n})$ does not converge.
 ^cor-sas-multi-subseq-lim

> [!theorem|*]- Bolzano - Weiestrass (BWT)
> Every bounded sequence of real numbers has a convergent subsequence.
 ^thm-sas-BW

`\begin{proof}`
By ![[sas note 2#^thm-sas-MCT]]  it is enough to show that every sequence of real numbers has a monotone subsequence.

We begin by defining set $S=\{ n \in \mathbb{N}:a_{n}\geq a_{m},\forall m>n \}$

__Case 1: $S$ is finite__
Let $n_{1}\in \mathbb{N}$ be larger than all ellements of S. In particular $n_{1} \notin S$, and so there exists $n_{2}\in N$ with $n_{2}>n_{1}$ s.t. $a_{n_{1}}<a_{n_{2}}$. Since $n_{2}\notin S\exists n_{3}>n_{2}$ s.t. $a_{n_{2}}<a_{n_{3}}$. Continuing in this way we construct a (strictly) increasing subsequence 

__Case 2: $S$ is infinite__
Since $S$ is infinite, we can write $S=\{ n_{k}: k \in \mathbb{N} \}$, for some strictly increasing sequence ($n_{k}$ of natural numbers. We claim that $(a_{n_{k}})$ is decreasing. To see this, let $k \in \mathbb{N}$. Since $n_{k}\in S$ we have $a_{n_{k}}\geq a_{m}$. In particular, $a_{n_{k}}.+ a_{n_{k+1}}$ since $n_{k+1}>n_{k}$
`\end{proof}`
