---
tags:
  - maths/algebra
  - maths/geometry
  - concepts
aliases:
  - complex
  - imaginary
  - roots of unity
  - argand
  - De Moivre
---

> [!definition|*]- Imaginary number, $i$
> $i^{2}=-1$ or $i=\sqrt[  ]{ -1 }$. The set of imaginary is $\mathbb{I}$.
 ^def-alg-imag

> [!definition|*]- Complex number
> This is $a+bi$ where $a,b \in \mathbb{R}$ are coefficients and $i$ is imaginary, such that $a$ is the real component and $b$ is the imaginary component. Its set is $\mathbb{C}$.
 ^def-alg-complex

> [!definition|*]- Complex plane
> This is a coordinate system that uses the real and imaginary coefficients as the coordinates of the $x$ and $y$ axes, to define a complex number.
 ^def-geo-compl-plane

> [!theorem|*]- De Moivre's Theorem
> $$e^{ i\theta }=\cos \theta+i\sin \theta$$
 ^thm-alg-de-moi

> [!definition|*]- Argand diagram
> This is an alternative coordinate system that does not use axes, but uses angles and radius to radially define a complex number.
 ^def-geo-argand

> [!definition|*]- N-th root of a complex number
> Suppose that $n ≥ 1$ is a natural number. A complex number $w$ is an n-th root of a non-zero complex number $z$, denoted by w = $z^{1/n}$ if $w^{n} = z$. We say that w is a n-th root of unity of $w$ is a n-th root of $1$.
> 
> Generally to find it, convert to exponential form such $z=re^{i\theta}=p^{n}e^{ in \phi }$ s.t. $\phi= \frac{\theta}{n}+k \frac{2\pi}{n},k \in \mathbb{N}$.
> $$\therefore z^{1/n}= r^{1/n}e^{i\frac{\theta+2\pi k}{n}}$$
 ^def-nth-root-complex

$\forall z\in\mathbb{C}\exists n$ distinct n-th roots with equal distance around the origin in an Argand diagram which will differ to neighbouring by $\frac{2\pi}{n}$ and consequently form vertices of a regular n sided polygon 
