> [!definition|*]- Spherical coordinates $(\rho,\phi,\theta)$
> $\rho=\sqrt[  ]{ x^{2}+y^{2}+z^{2} }\qquad \phi=\arccos\left( \frac{z}{\rho} \right)\qquad\theta=\arctan\left( \frac{y}{z} \right)$ where $\rho$ is the radius, where $\theta$ is the angle made with $x$-axis with $zy$ plane and is equivalent to polar coordinate $\theta$, and $\phi$ is the angle made with the $z$-axis with the $xy$ plane.
> Or $r=\rho \sin\phi\qquad \theta=\theta\qquad z=\rho \cos \phi$
 ^def-mva-sph-coord

> [!definition|*]- Taylor expansion
> $f(x) = f(a) + f'(a)(x-a) + f''(a) \frac{(x-a)^{2}}{2!} + \dots$
 ^def-mva-tayl

> [!theorem|*]- Weierstrass Extreme Value Theorem
> A closed domain inlcudes its boundary and a bounded domain means the distance from any point in the domain to the origin in finite.
> $f$ being continuous $\implies f$ attains max in $D$
> $D$ is closed $\implies f$ obtains min in $D$
> $D$ is bounded $\implies f$is bounded in $D$ 
 ^thm-mva-WEV

> [!definition|*]- Saddle, stationary and singular points
> $f:D \subseteq \mathbb{R}^{n}\to \mathbb{R}$, at a point $a\in D$ is called:
> stationary if $\nabla f(a)=0$
> singular if $\nabla f$ does not exist at $a$
> saddle, if $\nabla^{2}(a)=0=\nabla (a)$
 ^def-mva-stat-sad-sing-point

> [!theorem|*]- Fermat's Theorem
> If $f$ has a local extremum at the point $a\in D$, then $a$ must be one of the following:
> - A stationary point of $f$, 
> - A singular point of $f$
> - Or a boundary point of $D$
 ^thm-mva-ferm

> [!definition|*]- Hessian Matrix and leading minors
> Suppose $f(x,y)$ is a sufficiently smooth function, then the Hessian matrix of $f$ at $(a,b)$ is defined as 
> $$H=\left\{ \begin{pmatrix}f_{xx}  & f_{xy} \\ f_{yx}  & f_{yy}\end{pmatrix} \right. $$
> Where the derivatives are evaluated at $(a,b)$. 
> Its leading minors are defined as: $\det H_{1}\equiv \det (f_{xx})=f_{xx}$
> So $\det H=f_{x x}f_{yy}-f_{xy}^{2}$
 ^def-mva-hess-mat

> [!theorem|*]- Leading minor test
> - If $\det H>0$, and if $\det H_{1}<0$ then $a$ is a local max, or else other wise
> - If $\det H<0$ it is a saddle point
> - If $\det H=0$ further investigation is required
 ^thm-mva-minor-test

> [!proposition|*]- Constrained extrema and Lagrange multiplier
> $L(x,y,\lambda)=f(x,y)+\lambda g(x,y)$ is the Lagrange function where $\lambda$ is the Lagrange multiplier so stationary equations for the constrained problems are 
> $$\nabla L=0 \iff \left\{ \begin{matrix}\frac{ \partial L }{ \partial x } = \frac{ \partial f }{ \partial x } +\lambda \frac{ \partial g }{ \partial x } =0 \\\frac{ \partial L }{ \partial y } =\frac{ \partial f }{ \partial y } +\lambda \frac{ \partial g }{ \partial y } =0\end{matrix} \right. $$
> Combined with $g(x,y)=0$, while assuming $\nabla g\neq 0$
 ^prp-mva-lag-mult

