---
tags:
  - maths
  - analysis
---
> [!theorem|*]- Properties of continuous functions on $[a,b]$
> Recall that $f:[a,b]\to \mathbb{R}$ is continuous on a closed interval $[a,b]$ if $f$ is:
> - left continuous at b: $\lim_{ x \to b^{-} }f(x)=f(b)$
> - right continuous at a: $\lim_{ x \to a^{+} }f(x)=f(a)$
 ^thm-ra-cont-a-b

> [!theorem|*]- Boundedness 
> Let $f:[a,b]\to \mathbb{R}$ be continuous. Then $f$ achieves its minimum and maximum on $[a,b]$
 ^thm-ra-bounded

> [!theorem|*]- Min-max
> Let $f : [a, b] → \mathbb{R}$ be continuous. Then $f$ achieves it’s minimum and maximum on $[a, b]$.
 ^thm-ra-min-max

> [!theorem|*]- Bolzano's Theorem on roots of $f:[a,b]$
> Let $f : [a, b] → \mathbb{R}$ be continuous. Suppose that $f (a) < 0$ and $f (b) > 0$. Then there exists $c ∈ (a, b)$ such that $f (c) =0$ 
 ^thm-ra-bolzano

> [!theorem|*]- Intermediate value theorem (IVT)
> Let $f : [a, b] → \mathbb{R}$ be continuous and satisfy $f (a)\neq f (b)$. Then for each $y ∈ (min\{f (a), f (b)\}, max\{f (a), f (b)\}),$ there exists $c ∈ (a, b)$ such that $f (c) =y$
 ^thm-ra-IVT

> [!example|*]- $f(x)= x^{3}+ax^{2}+bx+c$ has one root
> Find $x_{1}$ and $x_{2}$, s.t. $f(x_{1})<0$ and $f(x_{2})>0$
> $$\lim_{ x \to \infty } f(x)=x^{3}\left( 1+\frac{a}{x} +\frac{b}{x^{2}}+\frac{c}{x^{4}}\right)=\infty$$
> $$\lim_{ x \to -\infty } f(x)=x^{3}\left( 1+\frac{a}{x} +\frac{b}{x^{2}}+\frac{c}{x^{4}}\right)=-\infty$$
> $\forall M>0\exists k>0$, s.t. $f(x)<-M$ whenever $x<-k$. Take $x_{1}=-k-1$. $f(x_{1})=f(-k-1)<-M<0$
> 
 ^exm-ra-3rd-poly-has-roots
 