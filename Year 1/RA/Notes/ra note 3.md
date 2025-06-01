---
tags:
  - maths
  - analysis
---
> [!definition|*]- Differentiation by first principles
> $$ \left . \frac{dy}{dx} \right|_{x=x_{0}} = \lim_{ h\to 0 } \left( \frac{f(x_{0}+h)-f(x_{0})}{h} \right)$$
 ^def-ra-1st-princ

> [!theorem|*]- $\exists f'(x_{0}) \implies f(x_{0})$ is continuous
> If a real function $f$ is differentiable at $x_{0}$, then $f$ is continuous at $x_{0}$.
 ^thm-ra-dif-exist-contin

> [!corollary|*]- $\not\exists f'(x_{0}) \implies f(x_{0})$ is not continuous
> If a real function $f$ is not differentiable at $x_{0}$, then $f$ is not continuous at $x_{0}$.
 ^thm-ra-dif-not-exist-contin

> [!definition|*]- Differentiate over a set
> A real function $f$ is differentiable on a set $X \subset\mathbb{R},$ if it is differentiable at every point in $X$
 ^def-ra-dif-set

![[LectureNotes2024.pdf#page=35&rect=170,524,423,720|LectureNotes2024, p.35]]

> [!corollary|*]- Properties of differentiable on $[a,b]$
> Suppose $f:[a,b]\mapsto \mathbb{R}$ is continuous and differentiable on $(a,b)$.
> - If $f'(x)=0\forall n \in (a,b)$ then $f$ is continuous on $[a,b]$
> - If $f'(x)>0\forall n \in (a,b)$ then $f$ is strictly increasing on $[a,b]$
> - If $f'(x)<0\forall n \in (a,b)$ then $f$ is strictly decreasing on $[a,b]$
>^cor-ra-dif-a-b-prop

> [!theorem|*]- Rolle's Theorem
> Suppose that $f : [a, b] → \mathbb{R}$ is continuous on $[a, b]$, differentiable on $(a, b)$, and $f (a) = f (b)$. Then there exists $c ∈ (a, b)$ such that $f ′(c) = 0$.
 ^thm-ra-rolle-thm

> [!theorem|*]- Generalised Mean Value Theorem
> Suppose that $f,g:[a,b]\mapsto\mathbb{R}$ are continuous on $[a,b]$, differentiable on $(a,b)$ and $g'(x)\neq 0\forall x \in (a,b)$. Then $\exists c\in(a,b)$ s.t. $$\frac{f(b)-f(a)}{g(b)-g(a)}= \frac{f'(c)}{g'(c)}$$ 
 ^thm-ra-gMVT

> [!corollary|*]- L'Hopital's Rule
> Let $I \subset \mathbb{R}$ be an open interval and $x_{0} \in I$. Suppose that $f,g:I\mapsto \mathbb{R}$ are differntiable on $I\setminus \{ x_{0} \}$and $g'(x_{0})\neq 0$ on $I \setminus \{ 0 \}$. Moreover suppose that: 
> $$\lim_{ x \to x_{0} } f(x)=\lim_{ x \to x_{0} } g(x) =0$$
> or that:
> $$\lim_{ x \to x_{0} } f(x)=\pm \infty\qquad\text{and}\qquad \lim_{ x \to x_{0} } g(x) =\pm\infty$$
> so indeterminate form is of $\frac{0}{0}$ or $\pm\frac{\infty}{\infty}$Then
> $$\lim_{ x \to x_{0} } \frac{f(x)}{g(x)}=\lim_{ x \to x_{0} } \frac{f'(x)}{g'(x)}$$
> if the limit on the right exists, is $-\infty$ or is $\infty$
 ^cor-ra-l-hopital-rule

> [!theorem|*]- Taylor's theorem
> Suppose that $f$ and all its derivatives exist on $(a, b)$, and that $x_{0} \in (a, b)$. By Taylor’s Theorem, for all $t$ such that $x_{0} + t \in (a, b)$ and all $n \in N$, we can write
> $$f(x_{0}+t)=\sum^{n}_{k=0} \frac{f^{(k)}(x_{0})}{k!}t^{k}+R_{n}(t)$$
> Where
> $$R_{n}(t)= \frac{f^{(n+1)}(x_{0}+\theta t)}{(n+1)!}t^{n+1}$$
> For some $\theta(t) \in (0, 1)$. If $R_{n}(t) \to 0$ as $n\to \infty$ for all t such that $x_{0} + t \in (a, b)$, then the series
> $$\sum^{\infty}_{k=0} \frac{f^{(k)}(x_{0})}{k!}t^{k}=$$
> converges, to $f (x_{0} + t)$. This series is called the Taylor Series of f centred at $x_{0}$. Sometimes we set $x = x0 + t$, and write
> $$f(x)= \sum^{\infty}_{k=0} \frac{f^{(k)}(x_{0})}{k!}(x-x_{0})^{k}$$
 ^thm-ra-taylor
