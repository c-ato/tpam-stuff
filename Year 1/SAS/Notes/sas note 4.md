---
tags:
  - maths
  - sequences
  - series
---
$$
\sum^{\infty}_{n=1} \frac{1}{n(n+1)}\implies \sum^{N}_{n=1} \frac{1}{n(n+1)}=\sum^{N}_{n=1}\left( \frac{1}{n}-\frac{1}{n+1} \right)=\left( \frac{1}{1}-\frac{1}{2} \right)+\dots \left( \frac{1}{N}-\frac{1}{N+1} \right)
$$
$$
=1-\frac{1}{N+1}\to1\,as\,N\to \infty
$$

> [!definition|*]- Convergent Series
> A series $\sum^{\infty}_{n=1}a_{n}$ of reals, converges to a real number $S$ if its sequence of partial sums $S_{N}$ given by $S_{N}=\sum^{N}_{n=1}a_{n}$ converges to $S$
 ^def-sas-conve-series

> [!definition|*]- Geometric Series
> A geometric series is a series of the form $\sum^{\infty}_{n=0}r^{n}$ for some real number $(r)$. $=1+r+r^{2}\dots$ Given by $S_{N}= \frac{1-r^{N+1}}{1-r};r\neq 1$.
> Observe:
> - If $|r|<1\implies S_{N}\to \frac{1}{1-r}$
> - If $|r|>1\implies(S_{n})$ does not converge, being unbounded
> Upshot:
> $$\sum^{\infty}_{n=0}r^{n}= \frac{1}{1-r} \impliedby |r|<1$$
 ^def-sas-geo-seriess

> [!theorem|*]- Linearity of summation
> If $\sum^{\infty}_{n=1}a_{n}$ and $\sum^{\infty}_{n=1}b_{n}$ converge, $\lambda,\mu \in \mathbb{R},$ then $$\sum^{\infty}_{n=1}(\lambda a_{n}+\mu b_{n})=\lambda\sum^{\infty}_{n=1}a_{n}+\mu\sum^{\infty}_{n=1}b_{n}$$
 ^thm-sas-lin-sum

`\begin{proof}`Let
$$
S_{N}=\sum^{\infty}_{n=1}a_{n}
$$
and
$$
T_{N}=\sum^{\infty}_{n=1}b_{n}
$$
$$
\sum^{\infty}_{n=1}a_{n} \to S\,\quad \sum^{\infty}_{n=1}b_{n}\to T
$$
Now $$
\sum^{N}_{n=1}(\lambda a_{n}+\mu b_{n})=\lambda S_{N}+\mu T_{N}
$$
which converfes to $\lambda S+\mu T$ by AoL.
`\end{proof}`