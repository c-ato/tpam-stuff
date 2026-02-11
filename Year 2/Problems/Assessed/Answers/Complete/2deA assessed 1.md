[[2DE_Assessment_1_PartA_2025_26.pdf]]

1. 
(a)
$$(y-2)\frac{ dy }{ dx }=16x$$
$$\int ^{}_{} y-2 \, dy=\int ^{}_{} 16x \, dx  $$
$$\frac{y^{2}}{2}-2y=8x^{2}+C'$$
$$y^{2}-4y+4=16x^{2}+\overbrace{ 2C'+4 }^{ C }$$
$$(y-2)^{2}=16x^{2}+C$$
$$y=\pm \sqrt[  ]{ 16x^{2}+C }+2$$
(b)
$$f(x,y)=\frac{dy}{dx}=\frac{16x}{y-2}\qquad\frac{ \partial f }{ \partial y } =- \frac{16x}{(y-2)^{2}}$$
If $f$ and $\frac{ \partial f }{ \partial y }$ are continuous on a point, then a unique solution exists on an interval around the point. So where $y_{0}=1$ a unique solution exists as $f$, and $\frac{ \partial f }{ \partial y }$ are continuous for this $y_{0}$ and all $x_{0}$. So, we may have an interval where a unique solution exists on an interval containing $y_{0}=1$ and $f$, $\frac{ \partial f }{ \partial y }$ are continuous.

Whereas for $y_{0}=2$, $f$ and $\frac{ \partial f }{ \partial y }$ it is undefined and discontinuous so no unique solution exists on the interval containing $y_{0}=2$

(c)
For $y(0)=1$
$$y_{+}(0)=1=+\sqrt[  ]{ C_{+} }+2\qquad +\sqrt[  ]{ C_{+} }=-1$$
No real solution for $y_{+}$ solution, now for $y_{-}$ solution.
$$y_{-}(0)=1=-\sqrt[  ]{ C_{-} }+2\qquad -\sqrt[  ]{ C_{-} }=-1\therefore C=1$$
From this we can see that the solution is unique as we can only choose $y_{-}$ so
$$y=-\sqrt[  ]{ 16x^{2}+1 }+2$$
For $y(0)=2$
$$y(0)=2=\pm\sqrt[  ]{ C }+2\qquad \pm\sqrt[  ]{ C }=0\therefore C=0$$
This means we have two solutions, and is not unique.
$$y=\pm \sqrt[  ]{ 16x^{2}}+2=\pm4x+2$$
2. 
Let us change the form of the equation so we may apply the general existence and uniqueness theorem for $n$th order linear ODEs.
$$y'''(x)=\frac{7x}{x(x^{2}-4)}y''(x)-\frac{9}{x(x^{2}-4)}y'(x)+\frac{x^{2}}{x(x^{2}-4)}y(x)=0$$
Where 
$$b_{0}(x)=- \frac{x^{2}}{x(x^{2}-4)}=\frac{x}{x^{2}-4}\qquad b_{1}(x)=\frac{9}{x(x^{2}-4)}\qquad b_{2}(x)=-\frac{7x}{x(x^{2}-4)}=\frac{7}{x^{2}-4}$$
From this we can see that between these three coefficients, $b_{n}(x)$, of $y^{(n)}$ there is discontinuity at $x=0$ and $x=\pm2$.

This means a unique solution exists on any of these intervals: 
$$x<-2 \qquad -2<x<0\qquad0<x<2\qquad 2<x $$
(a)

For $x_{0}=-3$ we have a unique solution on the interval $x<-2$

(b)

For $x_{0}=-1$ we have a unique solution on the interval $-2<x<0$

(c)

For $x_{0}=1$ we have a unique solution on the interval $0<x<2$
