[[CHAOS (A-B) 2019.pdf]]

1. (a) Define what is meant by the terms stable fixed point, unstable fixed point, stable 2-cycle and unstable 2-cycle of an iterated map, $$x_{n+1}=f(x_{n})$$State the conditions of stability and instability of a fixed point. Deduce from these the corresponding conditions for stability and instability of a 2-cycle.

A stable fixed point is a one cycle that the map may tend to if it exists, whereas unstable fixed points are one cycles that are unstable so they cannot be reached by iterating the map unless you start with it as an initial condition. A stable 2 cycle is when the map tends to oscillates between 2 different values after enough iterations, whereas a unstable 2 cycle can never be tended to, unless you start at it. Where $x,y$ are each of the 2 points in a 2 cycle, the conditions for stability for a 2-cycle :
$$
1> \frac{df}{dx} \frac{df}{dy}>-1
$$
Derived from 1 cycle stability:
$$
1> \frac{df}{dx}>-1\qquad x=f^{2}(x)=f(f(x))\qquad y=f(x)\implies \frac{dg}{dx}=f'(f(x))f'(x)
$$
$$
=f'(y)f'(x)\implies 1> f'(y)f'(x)=\frac{df}{dy}\frac{df}{dx}>-1
$$
	Consider the iterated map defined on the interval $0\leq x<\infty$ by$$x_{n+1}=f(x_{n})= \frac{rx_{n}}{1+x_{n}^{3}}$$where $0\leq r<\infty$
- (b) Find the fixed points of this map, and analyse their existence and stability as the parameter $r$ is varied. 
$$
x= \frac{rx}{1+x^{3}}\qquad x=0\qquad x^{3}+1=r\implies x=\sqrt[ 3 ]{ r-1 }
$$
$$
f'(x)=\frac{r(1+x^{3})-3rx^{3}}{(1+x^{3})^{2}}=\frac{r(1-2x^{3})}{(1+x^{3})}= \frac{r(3-2r)}{r}=3-2r\qquad r\neq 0
$$
$$
1>f'(x)=3-2r>-1\implies  1<r<0\qquad r<2
$$
- (c) Show that the equation $f (f (x)) = x$ can be rewritten in the form$$z^{2}+(r-r^{2})z+r^{2}=0$$
$$
x= \frac{r\frac{rx}{z}}{1+\left( \frac{rx}{z} \right) ^{3}}=\frac{\frac{r^{2}x}{z}}{\frac{r^{3}x^{3}+z^{3}}{z^{3}}}=\frac{r^{2}xz^{2}}{r^{3}x^{3}+z^{2}}\implies r^{2}xz^{2}-x^{4}r^{3}-z^{2}x=0
$$
$$
x(r^{2}-1)z^{2}-x^{4}r^{3}=0
$$