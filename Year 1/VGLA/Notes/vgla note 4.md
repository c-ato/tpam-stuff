---
tags:
  - maths
  - geometry
  - algebra
---
> [!definition|*]- Conics
> These are a family of curves defined by the intersection of a plain and a cone in $\mathbb{R}^{3}$. The standard conics are circles, parabola and hyperbola. Degenerate cases are obtained from signle point or a single line or pair of intersecting lines.
 ^def-vgla-conics

![[1VGLA_AU.pdf#page=109&rect=88,516,488,717|1VGLA_AU, p.100]]

> [!definition|*]- Parabola
> Standard equation with focus at point $F$ with coordinates $(0,p)$ and directrix $y=-p$ with $p>0$ is given by
> $$x^{2}=4py$$
> More generally
> $$y=ax^{2}+bx+c$$^def-vgla-parabola

`\begin{proof}`
$$
y=ax^{2}+bx+x \iff y=a\left( x- \frac{b}{2a} \right)^{2}+\left( c- \frac{b^{2}}{4a} \right)
$$
$$
\implies \underbrace{ y-\left( c-\frac{b^{2}}{4a} \right) }_{ :=Y }=a\underbrace{ \left( x+\frac{b}{2a} \right)^{2} }_{ :=X }
$$
In the form $(X,Y)$, following the standard equation, it takes the form $P\left( -\frac{b}{2a} , c- \frac{b^{2}}{4a}\right)$
$$
X^{2}=4PY
$$
Where $P= \frac{1}{4a}$
`\end{proof}`

> [!theorem|*]- Parametric equation
> For parabola with focus at $(0,p)$ and directrix $y=-p$ with $p>0$ are
> $$\left\{ \begin{matrix}x=2pt, \\y=pt^{2},\end{matrix} \right. \qquad t\in \mathbb{R} $$
 ^thm-vgla-para-eq

> [!theorem|*]- Polar equation of parabola
> The polar equation of a parabola with focus at $O(0, 0)$ and directrix $y = −p$, with $p > 0$, is
> $$r(\theta)= \frac{p}{1-\sin \theta}$$
 ^thm-vgla-pol-eq-parab

> [!definition|*]- Ellipse equation
> The standard equation of an ellipse with foci at $F_{1}(c, 0)$ and $F_{2}(−c, 0)$, with $c > 0$, is given by 
> $$\frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} = 1$$
> where $2a = | \overrightarrow{PF_{1}}| + |\overrightarrow{PF_{1}}|$ (the sum of the distances of a point on the ellipse to both foci) and $b^{2}=a^{2}-c^{2}$
 ^def-vgla-ellipse-eq

> [!theorem|*]- Polar equation of ellipse
> $$r(\theta)= \frac{ed}{1+e\cos \theta}$$
 ^thm-vgla-pol-eq-ellip

`\begin{proof}`
$$
\frac{(x+\sqrt[  ]{ a^{2}-b^{2} })^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1
$$
let $c=\sqrt[  ]{ a^{2}-b^{2} }$
$$
b^{2}(x+c)^{2}+a^{2}y^{2}=a^{2}b^{2}
$$
$$
b^{2}(r^{2}\cos ^{2}\theta+2cr\cos \theta+c^{2})+a^{2}r^{2}\sin ^{2}\theta=a^{2}b^{2}
$$
$$
r^{2}(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta)+r(2b^{2}c\cos \theta)+\underset{ -b^{4} }{ (b^{2}c^{2}-a^{2}b^{2}) }=0
$$
$$
r= \frac{-2b^{2}c\cos \theta\pm \sqrt[  ]{ (2b^{2}c\cos \theta)^{2}+4(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta)b^{4} }}{2(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta)}
$$
$$

r= \frac{-2b^{2}c\cos \theta\pm \sqrt[  ]{ (2b^{2}c\cos \theta)^{2}+4(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta)b^{4} }}{2(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta+a^{2}\cos ^{2}\theta-a^{2}\cos ^{2}\theta)}
$$

$$
r= \frac{-2b^{2}c\cos \theta\pm \sqrt[  ]{ (2b^{2}c\cos \theta)^{2}+4(b^{2}\cos ^{2}\theta+a^{2}\sin ^{2}\theta)b^{4} }}{2(a^{2}-c^{2}\cos ^{2}\theta)}
$$
$$
r= \frac{-2b^{2}c\cos \theta\pm 2b^{2}a}{2(a+c\cos \theta)(a-c\cos \theta)}
$$
$\because r>0$
$$
r= \frac{-b^{2}c\cos \theta+b^{2}a}{(a+c\cos \theta)(a-c\cos \theta)}
$$
$$
\therefore r= \frac{b^{2}}{(a+c\cos \theta)}= \frac{\frac{b^{2}}{a}}{1+\frac{c\cos \theta}{a}}= \frac{\frac{b^{2}}{a}}{1+e\cos \theta}
$$

`\end{proof}`

> [!definition|*]- Eccentricity of ellipse
> The eccentricity of an ellipse (when expressed in a coordinate system in standard form) is defined to be
> $$e= \frac{c}{a}=\frac{\sqrt[  ]{ a^{2}-b^{2} }}{a}<1$$
 ^def-vgla-ellip-eccent

> [!definition|*]- Hyperbola equation
> $$\frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1$$
> Where $2a$ is the difference of the distance of a point $P$ on the hyperbola to the two foci and $b^{2}=c^{2}-a^{2}>0$
 ^def-

Rearrange hyperbola equation to 
$$
y^{2}= \frac{b^{2}x^{2}}{a^{2}}-b^{2}
$$
$$
y^{2}\sim \frac{b^{2}x^{2}}{a^{2}}\implies y=\frac{b}{a}x\qquad \text{and}\qquad y=-\frac{b}{a}x
$$
This gives the asymptote as the $b^{2}$ constant is dominated as $x$ gets larger on the rhs

> [!definition|*]- Eccentricity of a hyperbola
> $$e= \frac{c}{a}=\frac{\sqrt[  ]{ a^{2}+b^{2} }}{a}>1$$
 ^def-vgla-eccen-hyper
> [!definition|*]- Directrices of hyperbola
> $$x= \pm \frac{a}{e}$$
 ^def-vgla-direct-hyperb

Rotation of parabola and hyperbola can be followed by differentiation of the trig function which causes $90°$ rotation