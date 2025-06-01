---
tags:
  - maths
  - analysis
---

|           | Differentiability                        | Continuous                     | Integrable              |
| --------- | ---------------------------------------- | ------------------------------ | ----------------------- |
| Geometric | Tangent                                  | Connectivity                   | Area                    |
| Analysis  | $\lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h}$ | $\lim_{ x \to x }f(x)\to f(c)$ | $\int ^{a}_{b} f \, dx$ |
> [!definition|*]- Supremum
> Suppose $X\subseteq \mathbb{R}$ bounded above.
> 1) An upper bound for $X$ is any $M\in \mathbb{R}$ such that $x\leq M\forall x \in \mathbb{R}$
> 2) The supremum of $X\, (\sup(X)$ is the least upper bound
 ^def-ra-supremum

> [!definition|*]- Infremum
> Suppose $X\subseteq \mathbb{R}$ bounded below.
> 1) A lower bound for $X$ is any $M\in \mathbb{R}$ such that $x\geq M\forall x \in \mathbb{R}$
> 2) The infremum of $X\, (\inf(X)$ is the greatest lower bound
 ^def-ra-infremum

> [!axiom|*]- Completeness Axiom
> If $X\subseteq \mathbb{R}$ is bounded above and not empty, then $\sup(X)\in \mathbb{R}$
 ^axm-ra-completeness-axm

> [!claim|*]- $\sup[a,b)=b$
> `\begin{proof}`
> Observe that $x\leq b \forall \xi n[a,b)$, so $b$ is an upper bound for $[a,b)$ or $a<b-\varepsilon<b-\frac{\varepsilon}{2} \in[a,b)$. So $b-\varepsilon$ is not upper bound $\therefore$ $b=\sup(a,b]$
> `\end{proof}`
 ^clm-ra-supre-(a,b]

> [!assumption|*]- 
> $-\infty<a<b<\infty$
> $f:[a,b]\to[0,\infty)$ is bounded
 ^asm-ra

> [!definition|*]- Partition
> A partition of $P$ of $[a,b]$ is a finite set $P=\{ x_{0},x_{1},x_{2}\dots x_{n} \}$ s.t. $a=x_{0}<x_{1}<x_{2}<\dots<x_{n}=b$ where $n \in \mathbb{N}$.
 ^def-ra-partion

$$
\sum^{b}_{i=0}  
$$