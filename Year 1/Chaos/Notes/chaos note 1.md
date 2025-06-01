---
tags:
  - maths
  - physics
  - chaos
  - differentials
---
> [!definition|*]- Lagrangian (dissipative) systems
> A system of differential equations that dissipates energy
 ^def-chaos-lagrangian

> [!definition|*]- Hamiltonian system
> A system of differential equations in which energy is conserved, such that $\frac{dE}{dt}=0$
 ^def-chaos-Hamiltonian

> [!theorem|*]- Complex trigonometry identity
> $$e^{ i\theta }=\cos \theta+i\sin \theta\qquad e^{ -i\theta }=\cos \theta-i\sin \theta$$
> $$\cos \theta= \frac{e^{ i\theta }+e^{ -i\theta }}{2}\qquad \sin \theta= \frac{e^{ i\theta }-e^{ -i\theta }}{2i}$$
> $$e^{ i\theta }e^{ -i\theta }= \cos ^{2}\theta+\sin ^{2}\theta=1$$
 ^thm-chaos-complex-trig-inden

Fundamental equation
$$
\frac{dx}{dt}=f[x,t]
$$
where $x$ is a vector and the dynamic variable.

3 methods to convert to 1st order:
1 basic:
$$
v= \frac{dx}{dt}\implies \frac{d^{2}x}{dy^{2}}=\frac{dv}{dt}
$$
[[chaos.pdf#page=3|chaos, p.3]]

2 physicist:
$$
\frac{dx}{dt}= \frac{p}{m}\implies \frac{dp}{dt}=-kx
$$
3 numeric:
$$
y=\left[ \frac{m}{k} \right] ^{1/2} \frac{dx}{dt}\qquad \frac{dx}{dt}= \left[ \frac{k}{m} \right]^{1/2}y
$$
$$
\frac{dy}{dt}= \left[ \frac{m}{k} \right]^{1/2}\frac{d^{2}x}{dt^{2}} = -\left[ \frac{k}{m} \right] ^{1/2} x
$$
Use $\tan$ substitution when dealing with $\sec$ integrations

$$
\mathcal{H}=T+V\qquad\mathcal{L}=T-V
$$
$$
\frac{d}{dt}\left[ \frac{d\mathcal{L}}{d \dot{r}} \right]= \frac{d\mathcal{L}}{d\theta}\qquad \frac{d}{dt}\left[ \frac{d\mathcal{L}}{d \dot{\theta}} \right] =\frac{d\mathcal{L}}{dr} 
$$
$$
\frac{ dr }{ dt } = \frac{ \partial \mathcal{H} }{ \partial p_{r} } \qquad \frac{d\theta}{dt}= \frac{ \partial \mathcal{H}\ }{ \partial p_{r} } 
$$
