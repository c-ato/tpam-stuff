---
tags:
  - physics
  - optics
---
![[lecture 2-R.pdf#page=5&rect=4,72,302,456|lecture 2-R, p.5]]

---

$$
y(x,t)=A\cos(kx-\omega t)\implies v=(x,y)=\frac{dy(x,t)}{dt}
$$
$$
=\frac{dy}{dt}\text{ or }\frac{dx}{dt} \text{ depending on what is kept constant}
$$
$$
\overset{ y=k }{ dz=x\,dy\, },\,\overset{ x=k }{ dz=y\,dx }\implies dz=x\,dy+y\,dx
$$
$$
\implies dz= \frac{\partial z}{\partial y}dy+ \frac{\partial z}{\partial x}dx
$$

---
> [!exercise|*] Deriving wave equation
> $$\frac{ \partial^{2} y(x,t) }{ \partial x^{2} } =-k^{2}A\cos(kx-\omega t)=k^{2}y(x,t)
>$$
>$$\frac{ \partial^{2} y(x,t )}{ \partial t^{2} }=-\omega^{2}y(x,t)
>$$
>$$\implies \frac{ \partial^{2} x }{ \partial t^{2} } =\frac{\omega^{2}}{k^{2}}=v^{2}
>$$
>$$\implies \frac{ \partial^{2} y(x,t) }{ \partial x^{2} } =\frac{1}{v^{2}}\frac{ \partial^{2} y(x,t) }{ \partial t^{2} } 
>$$
>
>^exr-der-wav-eq

---

