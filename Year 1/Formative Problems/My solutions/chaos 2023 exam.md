[[CHAOS (A-B) 2023.pdf]]

1. A weakly dissipative oscillator is described by the equation $$\frac{ d^{ 2 }x }{ dt^{ 2 } } +x=\delta \frac{ dx }{ dt } f\left[ x,\frac{ dx }{ dt }  \right] $$where $\delta\ll 1$
$$
\frac{ dp }{ dt } =\delta pf[x,p]-x\qquad \frac{ dp }{ dt } =-x\implies x_{c}=A\sin t+B\cos t
$$
$$
\implies p_{c}=A\cos t-B\sin t\qquad x=A\sin t+B\cos t+x_{p}\qquad p=A\cos t-B\sin t+p_{p}
$$
(b) Show that the energy $$E=\frac{1}{2}\left[ \left( \frac{ dx }{ dt }  \right)^{2}+x^{2} \right]$$is conserved in the limit $\delta\mapsto 0$ and determine how this energy changes, as a function of time, in the presence of the dissipation
$$
\frac{ dp }{ dt } =\delta pf[x,p]-x\overset{ \delta\mapsto0 }{ = } \frac{ dp }{ dt } =-x\implies x=A\sin t+B\cos t \qquad p=A\cos t-B\sin t
$$
$$
E=\frac{1}{2}\left[ \left( \frac{ dx }{ dt }  \right)^{2}+x^{2} \right]=E=\frac{1}{2}\left[ p^{2}+x^{2} \right]=\frac{1}{2}[A^{2}+B^{2}]
$$
With the presence of the dissipation, the energy is not conversed and energy is lost with time.

- (c) Solve for the trajectory in the limit

Ellipses in phase space

- (d) Explain why the attractor must satisfy ∆E=0, where this change in energy is over a single period of the oscillation.

Conservation of energy - changing state - kinetic and potential

- (e) For the particular case $$f[x,p]=2-x^{2}$$find the attractor in the limit $\delta\mapsto 0$

2. Consider the map $$x_{n+1}=r\left( x_{n}-\frac{1}{x_{n}} \right)$$where $r$ is a control parameter.

- (a) Find all the possible 1-cycles and establish for which range of control parameter they are stable.
$$
x=r\left( x-\frac{1}{x} \right)\implies x=\pm \sqrt[  ]{ \frac{1}{1-r} }\qquad r<1\qquad x\neq 0
$$
$$
1>\frac{df}{dx}=r\left( 1+\frac{1}{x^{2}} \right)>-1\implies \frac{r}{1-r}<x^{2}\qquad \frac{r}{r-1}>x^{2}>0
$$
$$
r>1\qquad r<0\qquad r<1
$$