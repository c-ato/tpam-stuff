---
tags:
  - maths
  - sequences
  - series
---
> [!theorem|*]- Null Sequence Test
> If the sum of $a_{n}$ converges then $a_{n}\to 0$. We interpret this as a test since if $a_{n}\not\to 0$, then divergent is:$$\sum^{\infty}_{n=1}a_{n}$$
> The converse is **NOT** true.
 ^thm-sas-null-test

> [!theorem|*]- Comparison Test
> Suppose that $0\leq a_{n}\leq b_{n} \forall n \in \mathbb{R}$.
> - If $\sum^{\infty}_{n=1}b_{n}$ converges then $\sum^{\infty}_{n=1}a_{n}$.
> - If $\sum^{\infty}_{n=1}a_{n}$ diverges then $\sum^{\infty}_{n=1}b_{n}$.
 ^thm-sas-compar-test

> [!theorem|*]- D' Alembert's Ratio Test
> Let $a_{n}$ be a sequence of $\mathbb{R^{+}}$ such a that $$\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}=r$$
> Then $\sum^{\infty}_{n=1}a_{n}$
> - converges if $r<1$
> - diverges if $r>1$
> - $r=1$ tells nothing
 ^thm-sas-ratio-test

Useful for when powers and eliminating/simplifying interfering polynomials and/or factorial.

> [!theorem|*]- Root Test
> Let $a_{n}$ be a sequence of non-negative real numbers s.t. $$\lim_{ n \to \infty } a_{n}^{1/n}=r,$$
> Then $\sum^{\infty}_{n=1}a_{n}$
> - converges if $r<1$
> - diverges if $r>1$
> - $r=1$ tells nothing
 ^thm-sas-root-test

> [!Lemma|*]- Family of sum of $\frac{1}{n^{\alpha}}$
> $$c\sum^{\infty}_{n=1} \frac{1}{n^{\alpha}}\to0 \in \alpha\leq 1$$
 ^prp-sas-1-n-a

> [!theorem|*]- Integral Test
> Let $f:[1,\infty)\mathbb{\to R}$ be continuous, decreasing, and positive. Then $$\sum^{\infty}_{n=1}f(n)$$ converges $\iff$ the sequence of integrals $$\overset{ \text{Partial integral} }{ \int ^{n}_{1} f(x) \, dx } $$ converges as $n\to \infty$
 ^thm-sas-int-test

> [!theorem|*]- Alternating series test
> Suppose the non-negative sequence $a_{n}$:
> - is decreasing
> - and converges to zero
> Then $$a_{1}-a_{2}+a_{3}-a_{4}+\dots=\sum^{\infty}_{n=1}(-1)^{n+1}a_{n}\to l$$
 ^thm-sas-alt-ser-test

> [!theorem|*]- Absolute Convergence Test
> A series $\sum^{\infty}_{n=1}a_{n}$ is said to be absolutely convergent if the series $\sum^{\infty}_{n=1}a_{n}$ is convergent in the usual sense.
 ^thm-sas-abs-conv-test

> [!definition|*]- Conditional convergence
> If $\sum^{\infty}_{n=1}a_{n}$ converges, but does not converge absolutely, then it is said to be conditionally convergent
 ^thm-sas-cond-conv

> [!theorem|*]- Dirichlet’s Theorem: rearrangements of series
> Let $\sum^{\infty}_{n=1}a_{n}$ be an absolutely convergent series of real numbers. If ($b_{n}$) is any rearrangement of ($a_{n}$) then: 
> - $\sum^{\infty}_{n=1} b_{n}$is an absolutely convergent series. 
> - $\sum^{\infty}_{n=1} b_{n}=\sum^{\infty}_{n=1} a_{n}$
 ^thm-sas-dirichlet-thm

> [!theorem|*]- Cauchy Product
> Assume $\sum^{\infty}_{n=1} a_{n},sum^{\infty}_{n=1} b_{n}$ are absolutely convergent series of real numbers. Then $$\sum^{\infty}_{n=1} a_{n}b_{n}$$ is absolutely convergent and $$\sum^{\infty}_{n=1} a_{n}b_{n}= \left( \sum^{\infty}_{n=1} a_{n} \right)\times \left( \sum^{\infty}_{n=1} b_{n} \right)= \sum^{\infty}_{k=0}\left( \sum_{n+m=0}a_{n}b_{m} \right)=\sum^{\infty}_{k=0}\left( \sum^{k}_{r=0}a_{r}b_{k-r} \right)$$
 ^thm-sas-sum-prod

> [!definition|*]- Power series
> A power series is an expression of the form 
> $$\sum^{\infty}_{n=0}a_{n}x^{n}$$
> where $a_{n}$ is a sequence of $\mathbb{R}$ (the coefficient of the power series), and $x \in \mathbb{R}$
 ^def-sas-power-series

$$
S=\left\{  x \in \mathbb{R} : \sum^{\infty}_{n=0}a_{n}x^{n}\,converges  \right\}
$$
Then we define a function $f:S\mapsto \mathbb{R}$ by $f(x)=\sum^{\infty}_{n=0}a_{n}x^{n}$

> [!theorem|*]- Convergence of power series
> Given a power series, either it converges absolutely $\forall x \in \mathbb{R}$, or $\exists R\in[0,\infty)$ s.t.:
> - It converges absolutely when $|x|<R$
> - It diverges when $|x|>R$
> 
>Where $R$ is the radius of convergence of the power series. If it is absolutely convergent for all $x \in \mathbb{R}$ then $R=\infty$
>
>This can be restated as $(-R,R)\subseteq S \subseteq [-R,R]$
 ^thm-sas-conv-pow

> [!theorem|*]- Ratio Test for Power Series
> Consider a power series:
> $$\sum^{\infty}_{n=0}a_{n}x^{n}$$
> Suppose that:
> $$\frac{|a_{n+1}|}{|a_{n}|}\to \ell ,\quad as\quad n\to \infty$$
> Then:
> $$R=\left\{ \begin{array}0 0 \quad if\quad\ell=\infty \\ \frac{1}{\ell} \quad if\quad\ell \in \mathbb{R}\setminus \{ 0 \}\\\infty \quad if\quad\ell=0\end{array} \right\} $$
 ^thm-sas-rat-pow-test

> [!theorem|*]- Root Test for Power Series
> Consider a power series:
> $$\sum^{\infty}_{n=0}a_{n}x^{n}$$
> Suppose that:
> $$|a_{n}|^{\frac{1}{n}}\to \ell ,\quad as\quad n\to \infty$$
> Then:
> $$R=\left\{ \begin{array}0 0 \quad if\quad\ell=\infty \\ \frac{1}{\ell} \quad if\quad\ell \in \mathbb{R}\setminus \{ 0 \}\\\infty \quad if\quad\ell=0\end{array} \right\} $$
 ^thm-sas-pow-root-test

> [!theorem|*]- Differentiability of Power Series
> Suppose
> $$\sum^{\infty}_{n=0}a_{n}x^{n}$$
> Is a power series with convergence set $S$. Define the function $f:S\mapsto \mathbb{R}$ by:
> $$f(x)=\sum^{\infty}_{n=0}a_{n}x^{n}$$
> is differentiable and
> $$f'(x)=\sum^{\infty}_{n=0}na_{n}x^{n-1}$$
> > [!remark|*]- 
> > This implies that if 
> > $$\sum^{\infty}_{n=0}a_{n}x^{n}$$
> > has a radius of convergence $R$ then
> > $$\sum^{\infty}_{n=0}na_{n}x^{n-1}$$
> > also has radius of $R$
  ^thm-sas-dif-pow

