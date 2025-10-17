notation of "little o":
Suppose $\lim_{ x\to x } \frac{f(x)}{g(x)}=0$, then $f(x)=og(x)$ as $x\to c$ - $f$ is little $o$ of $g$ as $x$ approaches $c$ - this simply means that the decay of $f$ is faster than $g$.

$\vec{a}=a_{1}\mathbf{i}+a_{2}\mathbf{j}+a_{3}\mathbf{k},\vec{b}=b_{1}\mathbf{i}+b_{2}\mathbf{j}+b_{3}\mathbf{k}$
$\vec{a}\cdot \vec{b}=\left| \vec{a} \right|\left| \vec{b} \right|\cos \theta=a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}$
$\vec{a}\times \vec{b}=\left| \vec{a} \right|\left| \vec{b} \right|\sin \theta \vec{n}=\begin{bmatrix}\mathbf{i} & \mathbf{j} & \mathbf{k} \\ a_{1} & a_{2} & a_{3} \\ b_{1} & b_{2} & b_{3}\end{bmatrix}=(a_{2}b_{3}-a_{3}b_{2})\mathbf{i}+(a_{1}b_{3}-a_{3}b_{1})\mathbf{j}+(a_{1}b_{2}-a_{2}b_{1})\mathbf{k}$
where $\vec{n}$ is the normal vector.

$\vec{a}\perp\vec{b}\iff \vec{a}\cdot \vec{b}=0\iff \cos \theta=0$
$\vec{a}\parallel\vec{b}\iff \vec{a}\times\vec{b}=0\iff \sin\theta=0$

$\vec{r}=\vec{a}+t \vec{d}\forall t\in \mathbb{R}$

$\vec{r}\cdot \vec{n}=\vec{a}\cdot \vec{n}$

curve: $\vec{r}=\vec{r}(t)=x(t)\mathbf{i}+y(t)\mathbf{j}+z(t)\mathbf{k},t\in[a,b]$

> [!definition|*]- Tangent Vector
> $$\vec{T}=\lim_{ \Delta t \to 0} \frac{\vec{PQ}}{\Delta t}=\lim_{ \Delta t\to 0 } \frac{\vec{r}(t+\Delta t)-\vec{r}(t)}{\Delta}= \frac{ dx }{ dt } \mathbf{i}+\frac{ dy }{ dt } \mathbf{j}+\frac{ dz }{ dt } \mathbf{k}\equiv \frac{d\vec{r}}{dt}=\vec{r}'=\vec{r}_{t} $$
 ^def-mva-tang-vec

If $\vec{r}'$ is smooth then $\vec{r}'\neq 0$ 

> [!definition|*]- Gradient Operator
> This is a linear operator that acts on a function to make it a vector and gives the corresponding gradient as a vector. 
> $$\nabla f(a)=\text{grad}f(a)\equiv \frac{ \partial f(a) }{ \partial x } \mathbf{i}+\frac{ \partial f(a) }{ \partial y } \mathbf{j}+\frac{ \partial f(a) }{ \partial z } \mathbf{k}$$
 ^def-mva-grad

> [!theorem|*]- Linearity of $\nabla$
> Let $x,y$ be functions and $a,b$ be constants. Then the following is true$$\nabla(ax+by)=a\nabla x+b\nabla y$$
 ^thm-mva-lin-del

> [!theorem|*]- Gradient as normal for level surface
> Let $f(x,y,z)$ be sufficiently smooth and $\vec{a}$ be a point on the level surface $f(x, y, z) = k$ for some constant $k$. If $\nabla f(\vec{a})\neq 0$, then the vector $\nabla f(\vec{a})$ is normal to the level surface at the point $\vec{a}$.
> That is $\nabla f\cdot \vec{r}'=0$ or $\nabla f \perp \vec{r}'$ where $\vec{r}'$ is the surface tangent vector, based on the derivative of parameterized variables 
 ^thm-mva-grad-is-norm-lvl-surf

> [!definition|*]- Directional Derivative
> This is the rate change of a function, $f$ in the direction of a vector, $\vec{u}$ where $\vec{u}$ is a unit vector at a point $\vec{a}=(a,b,c)$:
> $$\lim_{ t \to 0 } \frac{f(a+tu_{1},b+tu_{2},c+tu_{3})}{t}\equiv D_{u}(a,b,c)$$
> or alternatively:
> $$D_{u}f=\vec{u}\cdot \nabla f(a,b,c)$$
 ^def-mva-dir-deriv

> [!theorem|*]- Linearity of directional derivative
> $D_{u}(\lambda f+\mu g)=\lambda D_{u}f+\mu D_{u}g$
 ^thm-mva-lin-dir-deriv

> [!theorem|*]- Steepest ascent theorem
> Let $\vec{u}$ be a unit vector, 
> $$D_{u}f(a)=\left| \nabla f(\vec{a}) \right|\cos \theta \because\left| \vec{u} \right|=1$$
 ^thm-mva-ste-asc

> [!theorem|*]- Fubini theorem
> Let $D:=\{ (x,y):a\leq x\leq b,y_{1}(x)\leq y\leq y_{2}(x) \}=\{ (x,y):e\leq y\leq f,x_{1}(y)\leq x\leq x_{2}(y) \}$, where, $y_{1}(x),y_{2}(x),x_{1}(y),x_{2}(y)$ are smooth, then:
> $$\iint_{D}f(x,y)dxdy=\int ^{b}_{a}\left( \int ^{y_{2}(x)}_{y_{1}(x)} f(x,y)  \, dy  \right)  \, dx = \int ^{d}_{c} \left( \int ^{x_{2}(y)}_{x_{1}(y)} f(x,y) \, dx  \right) \, dy $$
 ^thm-mva-fubini

> [!theorem|*]- Fubini theorem for triple integrals
> $$\iiint_{E}f(x,y,z)dxdydz=\iint_{D}F(x,z)dxdz$$
 ^thm-mva-fubini-thm-tripl

> [!theorem|*]- Even and odd functions in symmetric domains
> If $D$ is symmetric to $x$ and $f(x,y)$ is odd in $x$, then $\iint_{D}f(x,y)dxdy=0$
> If $D$ is symmetric to $x$ and $f(x,y)$ is even in $x$, then $\iint_{D}f(x,y)dxdy=2\iint_{D_{half}}f(x,y)d\times dy$
 ^thm-mva-even-odd-sym-dom

> [!theorem|*]- Change of integration variable
> $$\int ^{b}_{a} f(x) \, dx=\int ^{\beta}_{\alpha} f(x(u)) \, x_{u}du  $$
 ^thm-mva-change-int-var

polar coordinates:
$r=\sqrt[  ]{ x^{2}+y^{2} }$ and $\tan \theta=\frac{y}{x}$

$x=r\cos \theta$ and $y=r\sin \theta$

$dxdy=r d\theta dr$
