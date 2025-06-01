---
tags:
  - maths
  - analysis
---
> [!definition|*]- Limit of functions
> We will define what we mean by
> $$\lim_{ x \to x_{0} }f(x)=\ell$$
> Let $f$ be a real function. Suppose $b<x_{0}<c$ and $f$ is defined on $(b,c)\setminus \{ x_{0} \}$. We say the limit of $f$ as $x\to x_{0}$ is $\ell \in \mathbb{R}\iff \forall\epsilon>0,\exists\delta>0$ s.t. $|f(x)-\ell|<\epsilon$ whenever $0<|x-x_{0}|<\delta$. In this case, we write $\lim_{ x \to x_{0} }f(x)=\ell.$
 ^def-ra-lim

> [!theorem|*]- Squeeze Theorem
> Suppose that $f , g$ and $h$ are real functions, and that for some $α > 0$, $$f (x) ≤ h(x) ≤ g(x)$$ $\forall x ∈ (x_{0} − α, x_{0} + α) \setminus {x_{0}}$, and that for some $A ∈ \mathbb{R}, \lim_{ x \to x_{0} } f (x) = \lim_{ x \to x_{0} } g(x) = A$. Then $\lim_{ x \to x_{0} } h(x) = A$.
 ^thm-ra-squeeze

proof of :
$$
\lim_{ x \to x_{0} } f(x)=A,\lim_{ x \to x_{0} } g(x)=B
$$
$$
\lim_{ x \to x_{0} } f(x)g(x)=\lim_{ x \to x_{0} } f(x)\lim_{ x \to x_{0} } g(x)=AB
$$
 $$
\exists \delta \wedge  \epsilon>0
$$
 $$
|f(x)g(x)-AB|<\delta,|f(x)g(x)+f(x)B-f(x)B-AB|=|f(x)(g(x)+B)-B(f(x)-A)|
$$
$$
\leq |f(x)(g(x)+B)|-|B(f(x)-A)|
$$
$$
|f(x)(g(x)+b)|\leq\epsilon
$$
> [!theorem|*]- Change of variable
> $$\lim_{ y \to y_{0} } f(y)=A,\lim_{ x \to x_{0} } g(x)=y_{0}. \text{ when }g(x)\neq y_{0}\implies x\neq x_{0}$$
> $$\lim_{ x \to x_{0} } f(g(x))=A$$
 ^thm-

> [!theorem|*]- Properties of limits
> Let $f$ and $g$ be real functions. In the following, the abbreviation $\lim$ denotes the limit with any one of the following situations: as $x → x_{0}$, as $x → x_{0}^{-}$ , as $x → x_{0}^{+}$ , $x → ∞$, or as $x → −∞$. 
> - Uniqueness. If $\lim f (x) = a$ and $\lim f (x) = b$, then $a = b$
> - Squeeze theorem. If $f (x) ≤ g(x) ≤ h(x)$ and both $\lim f (x) = \lim h(x) = ℓ$ exist, then $\lim g(x) = ℓ$.
> - Boundedness. If $\lim x→ x_{0} f (x)$ exists, then there exists $δ > 0$, such that $f$ is bounded on $( x_{0} − δ,  x_{0}) ∪ ( x_{0},  x_{0} + δ)$
> - Algebra of limits. Suppose $\lim f (x)$ and $\lim g(x)$ exist and $c ∈ \mathbb{R}$ is a constant. Then:  
> 	- $\lim cf (x) = c \lim f (x)$
> 	- $\lim(f (x) ± g(x)) = \lim f (x) ± \lim g(x)$
> 	- $\lim[f (x)g(x)] = \lim f (x) \lim g(x)$
> 	- $\lim \frac{f(x)}{g(x)} = \frac{\lim f(x)}{\lim g(x)}$, provided $g(x)̸ = 0$ and $\lim g(x)̸ = 0$.
> 	- If $f (x) ≥ 0$ or $f (x) > 0$, then $\lim f (x) ≥ 0$ if the limit exists.
 ^thm-

> [!theorem|*]- Existence of a function's limit from a sequence's limit
> Let $f$ be a real function. The following statements are equivalent:
> - $\lim_{ x \to x_{0} }f(x)=l$
> - for any sequence $\{ x_{n} \}\subset Dom(f)$ satisfying $x_{n}\neq x_{0}$ as $x_{n}\to x_{0}$ as $n\to \infty$ we have $\lim_{ x \to x_{0} }f(x)$ does not exist
 ^thm-ra-funct-lim-seq-lim

> [!corollary|*]- Non-existence of a function's limit from a sequence's limit
> Let $f$ be a real function. The following statements are equivalent:
> - $\lim_{ x \to x_{0} }f(x)=l$
> - for any sequence $\{ x_{n} \}\subset Dom(f)$ satisfying $x_{n}\neq x_{0},\forall n \in\mathbb{N}$ as $n\to \infty \wedge\lim_{ n \to \infty }f(x_{n})$ does not exist. Then $\lim_{ x \to x_{0} }f(x)$ does not exist
 ^cor-ra-non-func-lim-non-seq-lim

> [!definition|*]- Continuous functions
> Let $f$ be a real function. Suppose there exists $\delta>0$ s.t. $(x_{0}-\delta,x_{0}+\delta)$ is a subset of $Dom(f)$. We say $f$ is continuous at $x_{0}$ if $$\lim_{ x \to x_{0} } f(x)=f(x_{0})$$ If $f$ is continuous at all $x \in Dom(f)$, then we say $f$ is a continuous function. Moreover, if $\lim_{ x \to x_{0} }f(x)\neq f(x_{0})$ we say that f is discontinuous at $x_{0}$
> 
> This requires that:
> - $f(x_{0})$ is defined
> - $\lim_{ x \to x_{0} }f(x)$ exists
> - $\lim_{ x \to x_{0} }f(x)=f(x_{0})$
 ^def-ra-continuous

> [!theorem|*]- Properties of continuous functions
> Let $f$ and $g$ be real:
> - if $f$ and $g$ are continuous at $x_{0}$, then $f(x)\pm g(x),f(x)g(x),$ and $f\left( \frac{x}{g(x)} \right)$ with $g(x_{0})\neq 0$ are all continuous at $x_{0}$
> - if $f$ and $g$ are continuous at $g(x_{0})$ and $x_{0}$, respectively, then $$\lim_{ x \to x_{0} } f(g(x))=f(g(x_{0}))$$
> - if $f$ is continuous on $[a,b]$ and $f^{-1}$ is its inverse, then $f^{-1}$ is also continuous
> - it follows that $\exists \epsilon>0,\delta>0$ s.t.:
> 	- $$
|f(x)-f(x_{0})|<\epsilon\quad |x-x_{0}|<\delta
$$^thm-ra-prop-cont-funct

