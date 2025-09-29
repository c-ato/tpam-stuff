---
tags:
  - maths/algebra
  - concepts
aliases:
  - function
  - bijective
  - injective
  - image
  - pre-image
---

> [!definition|*] Functions
> A function f from $X\mapsto Y$where X and Y are sets, consist of 3 things
> - $X=dom(f)$ is the domain of f
> - $Y=codom(f)$ is the co-domain of f
> - A well defined rule that assigns every element $x \in X$ with an element $f(x) \in Y$
 ^def-funct

> [!definition|*] Image (range) of a function
> $$\{ f(x):x \in X \}$$
 ^def-range-image

> [!definition|*] Pre-image (of $B:B\subseteq Y$)
> $$f^{-1}(x)=\{ x \in X: f(x) \in B \}$$
 ^def-domain-preimage

If f and g are two functions, they are equal if: $dom(f)=dom(g)$, $co-dom(f)=co-dom(g)$ and rule for f = rule of g

If $f:X\mapsto Y$ and $g: Y \mapsto Z$, then we can derive a function from $X \mapsto Z$ by $x \mapsto g(f(x))$, denoted as $g\cdot f$

> [!definition|*] Surfective functions
> Let $f:X→Y$. We say that $f$ is **onto** (or **surjective** or that $f$ is a surjection) $\iff$ for every $y∈Y$, there is at least one $x∈X$ such that $f(x)=y$
 ^def-funct-surfective

> [!theorem|*] Surjective functions
> Let $f:X\to Y$. Then $f$ is onto $\iff$ $\operatorname{ran}(f)=\operatorname{codom}(f) \iff f(X)=Y$.
> ^thm-surjective

- The other condition we require for $f$ to be a function is that the rule assigning points in $Y$ to points in $X$ should be well-defined and that for each $x$ there should be a unique $y$ in $Y$ such that $f(x)=y$. For this to be true of $f^{-1}$, we require that if $y_1=y_2$, then $f^{-1}(y_1)=f^{-1}(y_2)$. From the definition of $f^{-1}$, if it is defined, and $f(x_1)=y_1$ and $f(x_2)=y_2$, then $f^{-1}$ is well-defined, iff whenever $f(x_1)=f(x_2)$, then $x_1=x_2$. This is the same as saying that for all $y\in Y$, there is at most one $x \in X$ such that $f(x)=y$.

> [!definition|*] Injective (one-to-one) functions
> Let $f:X→Y$. We say that $f$ is **one-to-one** (or **injective** or that $f$ is an injection) $\iff$ for every $y∈Y$, there is at most one $x∈X$ such that $f(x)=y$.
 ^def-funct-1-2-1

> [!theorem|*] Injective
> Let $f:X\to Y$. The following are equivalent:
>
>1. $f$ is one-to-one;
>    
>2. if $x_1\neq x_2$, then $f(x_1)\neq f(x_2)$;
>    
>3. if $f(x_1)=f(x_2)$, then $x_1=x_2$.
 >^thm-injective

> [!definition|*] Bijective functions
> Let $f:X→Y$. We say that $f$ is bijective (or that $f$ is an bijection) $\iff$ it is both an injection and a surjection.
 ^def-funct-bijective

> [!theorem|*] Bijective
> Let $f:X\to Y$. The inverse of $f$, $f^{-1}:Y\to X$ exists $\iff f$ is a bijection.
>
> In this case, $$f^{-1}\circ f(x)=f^{-1}(f(x))=x\qquad\text{and}\qquad f\circ f^{-1}(y)=f(f^{-1}(y))=y$$
 >^thm-bijective
 
