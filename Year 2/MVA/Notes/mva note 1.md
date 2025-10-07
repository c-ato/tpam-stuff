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
> $\nabla()$
 ^thm-