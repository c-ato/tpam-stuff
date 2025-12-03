[[2MVA_Level_I_Assessed_Sheet_3.pdf]]

1. 
(a) What is the length of the curve $C$ which is the segment of a circular helix parameterized by $$C = (x(t), y(t), z(t)) = (a \cos(t), a \sin(t), bt)$$ for $0 ≤ t ≤ 3π$ where $a$ and $b$ are positive constants.
$$\underline{r}'=(-a\sin (t),a\cos(t),b)\qquad s=\int ^{3\pi}_{0}\left| \underline{r}'(t) \right|\,dt =\int ^{3\pi}_{0} \sqrt[  ]{ a^{2}\sin ^{2}t+a^{2}\cos ^{2}t+b^{2} } \, dt=3\pi \sqrt[  ]{ a^{2}+b^{2} } $$
(b) What is the mass of this helical segment if its density (mass per unit length) is given by $ρ(x, y, z) = x^{2} + y^{2} + z^{2}$

$$\rho(t)=a^{2}+b^{2}t^{2}\qquad M=\int ^{3\pi}_{0}\left| \underline{r}'(t) \right|\rho(t)\,dt =\int ^{3\pi}_{0} (a^{2}+b^{2}t^{2})\sqrt[  ]{ a^{2}\sin ^{2}t+a^{2}\cos ^{2}t+b^{2} } \, dt$$
$$=(3\pi a^{2} +9\pi^{3}b^{2})\sqrt[  ]{ a^{2}+b^{2} }$$

2. Let $\mathbf{F} = (y^{3} + y, 3xy^{2})$ and let $\mathbf{r} = (x, y)$ be the position vector in $\mathbb{R}^{2}$.
(a) Is $\mathbf{F}$ a conservative field? Explain your answer.

$\mathbf{F}=(P,Q)=(y^{2}+y,3xy^{2})$ and this field is only conservative if $\underline{\nabla}\cdot \mathbf{F}=\frac{ \partial Q }{ \partial x }-\frac{ \partial P }{ \partial y }=0$. $\frac{ \partial P }{ \partial y }=3y^{2}+1$ and $\frac{ \partial Q }{ \partial x }=3y^{2}$ and we see that $\frac{ \partial Q }{ \partial x }-\frac{ \partial P }{ \partial y }=-1\neq 0$ so it is not conservative

(b) Let $C = C_{1} + C_{2}$ be closed curve where $C_{1}$ is the semicircle along $x^{2} + y^{2} = 1$ traversed in the counter-clockwise direction from the point $(1, 0)$ to the point $(−1, 0)$ and $C_{2}$ is the straight line segment from $(−1, 0)$ to $(1, 0)$. Using Green’s Theorem or otherwise calculate $\oint_{C}\mathbf{F}\cdot d\mathbf{r}$.

$$\underline{\nabla}\cdot \mathbf{F}=-1$$
$$\oint_{C}\mathbf{F}\cdot d\mathbf{r}=\iint_{R} \underline{\nabla}\cdot \mathbf{F}\,dA$$
$$=\iint_{R} (-1)\,dA=(-1)\left( \int ^{1}_{0}  \, dr \int ^{\pi}_{0} r \, d\theta \right) =-\frac{\pi}{2}$$
3. Let $\mathbf{F} = (x + y + z, \sin(xz), yx)$ in $\mathbb{R}^{3}$. Calculate $\text{curl}(F) = ∇ \times \mathbf{F}$
$$\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{ \partial  }{ \partial x }  & \frac{ \partial  }{ \partial y } & \frac{ \partial  }{ \partial z }  \\
x+y+z & \sin(xz) & yx 
\end{vmatrix} =(x-x\cos(xz))\mathbf{i}-(y-1)\mathbf{j}+(z\cos(xz)-1)\mathbf{k}$$
4. The field $\mathbf{F} = \left( 2x + \frac{1}{y} , 2y − \frac{x}{y^{2}}  \right)$ is a gradient field in $\mathbb{R}^{2}$. Determine the scalar function $f = f (x, y)$ such that $\mathbf{F} = \nabla f$ . Calculate $\int ^{}_{C} \mathbf{F} \cdot d\mathbf{r}$ where $C$ is the straight line segment from $(1, 1) to (2, 2)$.
$$\mathbf{F}=\left( \frac{ \partial f }{ \partial x } ,\frac{ \partial f }{ \partial y }  \right)=\left( 2x+\frac{1}{y} ,2y- \frac{x}{y^{2}}\right)$$
$$\int ^{}_{} \frac{ \partial f }{ \partial x }  \, dx =x^{2}+c_{1}(y)+\frac{x}{y} =\int ^{}_{} \frac{ \partial f }{ \partial y }  \, dy =y^{2}+c_{2}(x)+\frac{x}{y}$$
$$\implies x^{2}+c_{1}(y)=y^{2}+c_{2}(x) \therefore c_{1}=y^{2}\qquad c_{2}=x^{2}\implies f=x^{2}+y^{2}+\frac{x}{y}$$
$$\int ^{}_{C} \mathbf{F}\cdot d\mathbf{r}=\int ^{}_{C} \nabla f\cdot d\mathbf{r} =f(2,2)-f(1,1)=9-3=6$$
