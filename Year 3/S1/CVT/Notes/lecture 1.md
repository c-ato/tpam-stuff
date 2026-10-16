priory: Taylor's Theorem

> [!theorem|*]- Taylor's Theorem
> 
 ^thm-tay
 
Derivative in complex had multiple angles at which we can limit, which provides additional restrictions to a function, otherwise we may choose arbituary disappearing functions within a real function.

$$\frac{df}{dz}=\lim_{ z \to 0 }  \frac{f(z+\delta z)}{\delta z}$$
using $\delta z=r e^{ i\theta }$

Continue this and take in terms of const, $\sin$ and $\cos$ terms and we want $\theta$ dependence to disappear obtaining below
> [!theorem|*]- Cauchy-Riemann Equations
> $$\frac{ \partial X }{ \partial x } =\frac{ \partial Y }{ \partial y } \qquad \frac{ \partial X }{ \partial y } =- \frac{ \partial Y }{ \partial x }\qquad \frac{ \partial f }{ \partial x } +i\frac{ \partial f }{ \partial y }=0 $$
 ^thm-cvt-cauchy-riem-eq

from Cauchy-Riemann
$$\frac{ \partial X }{ \partial x } =\frac{ \partial Y }{ \partial y } \implies \frac{ \partial^{2} X }{ \partial x^{2} } =\frac{ \partial^{2} Y }{ \partial y\partial x }=\frac{ \partial^{2} Y }{ \partial x\partial y }=-\frac{ \partial^{2} X }{ \partial y^{2} }  $$
and also 
$$\frac{ \partial^{2} Y }{ \partial x^{2} } =-\frac{ \partial^{2} Y }{ \partial y^{2} } $$
