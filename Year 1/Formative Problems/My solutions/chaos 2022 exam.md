---
tags:
  - chaos
---
[[CHAOS (A) 2022.pdf]]

1. A forced damped pendulum is described by the equation$$\frac{d^{2}\theta}{dt^{2}}+\frac{d\theta}{dt}+\sin \theta=R\cos t$$
- (a) When $R ≪ 1$ find the attractor to leading order in $R$. 
$$
\because R\ll 1\implies \sin \theta \approx \theta \therefore \frac{d^{2}\theta}{dt^{2}}+\frac{d\theta}{dt}+\theta=R\cos t\therefore \theta=R\sin t
$$
$$
\dot{\theta}=\omega=R\cos t\qquad\theta^{2}+\omega^{2}=R^{2}
$$
- (b) Show that to order $R^{3}$ the attractor can be found approximately by solving the equation$$\frac{d^{2}\theta}{dt^{2}}+\frac{d\theta}{dt}+\theta=R\cos t+A\sin t+B\sin3t$$where you should provide explicit representations for $A$ and $B$.
$$
\sin \theta\approx \theta-\frac{\theta^{3}}{6}\implies\frac{d^{2}\theta}{dt^{2}}+\frac{d\theta}{dt}+\theta=R\cos t+\frac{\theta^{3}}{6}\qquad \frac{\theta^{3}}{6}= \frac{R^{3}\sin^{3}t}{6}
$$
$$
e^{ 3i\theta }=\cos3\theta+i\sin 3\theta=\cos ^{3}\theta+3i\cos ^{2}\theta \sin \theta-3\cos \theta \sin ^{2}\theta-i\sin ^{3}\theta
$$
$$
\therefore \sin3t=3(1-\sin ^{2}t)\sin t-\sin ^{3}t\implies \sin ^{3}t=\frac{3}{4}\sin t-\frac{1}{4}\sin 3t
$$
$$
\frac{d^{2}\theta}{dt^{2}}+\frac{d\theta}{dt}+\theta=R\cos t+\frac{\theta^{3}}{6}=R\cos t+\frac{R^{3}}{8}\left( \sin t-\frac{1}{3}\sin 3t \right)
$$
- (d) Describe how the attractor has been physically altered by the increasing of $R$.

Oscillates more on smaller scale causing the path to no longer be elliptical, and by increasing $R$ this distortion increases potentially leading to chaotic behaviour due to sensitivity due to initial conditions.

2. Consider the map$$x_{n+1}=ax_{n}-x_{n}^{2}$$where $a$ is a control parameter. Find all the possible 1-cycles and establish for which range of control parameter they are stable. 
$$
x=ax-x^{2}\qquad x=0\qquad 1=a-x \iff x=a-1
$$
$$
\frac{df}{dx}=a-2x\quad 1>a-2x>-1\implies -1>-a>-3\implies a>1\quad a<-3
$$
	Find all the possible 2-cycles and establish for which range of control parameter they are stable.
$$
x=ay-y^{2}\qquad y=ax-x^{2}\implies \frac{x}{y}-y=\frac{y}{x}-x\implies x-y=\frac{y^{2}-x^{2}}{xy}
$$
$$
x^{2}=axy-xy^{2}\qquad y^{2}=axy-yx^{2}\implies x^{2}+xy^{2}=y^{2}+yx^{2}
$$
$$
x^{2}-y^{2}=yx^{2}-xy^{2}\implies x+y=xy
$$
$$
x-y=a(y-x)+(x+y)(x-y)\implies x+y=1+a=xy
$$
$$
y=1+a-x\implies x=a(1+a-x)-(1+a-x)^{2}
$$
$$
x^{2}-ax-x+a+1=0\implies x=\frac{1+a\pm \sqrt[  ]{ (a+1)^{2} -4(a+1)}}{2}
$$
$$
=\frac{1+a\pm \sqrt[  ]{ (a+1)(a-3)}}{2}\therefore y=\frac{1+a\mp \sqrt[  ]{ (a+1)(a-3)}}{2}
$$
$$
\frac{df}{dx} \frac{df}{dy}= (a-2x)(a-2y)=
$$
$$
\left( -1\pm \sqrt[  ]{ (a+1)(a-3)}\right) \left( -1\mp \sqrt[  ]{ (a+1)(a-3)} \right) =1-(a+1)(a-3)
$$
$$
1>1-(a+1)(a-3)>-1\qquad(a+1)(a-3)>0\qquad  a>3\qquad a<1
$$
$$
(a+1)(a-3)-2<0\qquad 1-\sqrt[  ]{ 6 }<a<1+\sqrt[  ]{ 6 } 
$$
$$
\therefore 3<a<1+\sqrt[  ]{ 6 }\qquad1-\sqrt[  ]{ 6 }<a<1
$$
	Find the attractor when it is either a 1-cycle or a 2-cycle. 
$$
1-cycle:0,a-1\qquad 2-cycle:\frac{1+a\pm \sqrt[  ]{ (a+1)(a-3)}}{2}
$$
3. Consider the map $$x_{n+1}=4x_{n}^{3}-ax_{n}$$where $a$ is a control parameter.
- (a) show that $$\cos 3πy = 4 \cos ^{3} πy − 3 \cos πy $$
$$
e^{ 3i\theta }=\cos 3\theta+i\sin 3\theta=\cos ^{3}\theta+3i\cos ^{2}\theta \sin \theta-3\cos \theta \sin ^{2}\theta-i\sin ^{3}\theta
$$
$$
\cos 3\theta=\cos ^{3}\theta-3\cos \theta+3\cos ^{3}\theta=4\cos ^{3}\theta-3\cos \theta
$$
$$
\theta=3\pi y\implies \cos 3πy = 4 \cos ^{3} πy − 3 \cos πy  \therefore a=3
$$
$$
x=x(4x^{2}-2)=x(2x+\sqrt[  ]{ 2 })(2x-\sqrt[  ]{ 2 }) \therefore x=0,\pm \frac{\sqrt[  ]{ 2 }}{2}
$$
- (b) Depict the linear map in the restricted domain $y\in [0,1]$
![[chaos 2022 exam 2025-05-26 15.53.13.excalidraw]]
- (c) Employ base 3 to find a useful representation for your linear map.
$$\begin{matrix}

 & 0.a_{1}a_{2}a_{3}\dots  \\
\left[ 0, \frac{1}{3} \right] & a_{1}=0 & 0.0a_{2}a_{3}\dots \\
\left[ \frac{1}{3}, \frac{2}{3} \right] & a_{1}=1 & 0.1a_{2}a_{3}\dots \\
\left[ \frac{2}{3},1 \right] & a_{1}=2 & 0.2a_{2}a_{3}\dots
\end{matrix}
$$
$$
\begin{matrix}
\left[ 0, \frac{1}{3} \right] & M[0.0a_{2}a_{3}\dots]\to 0.a_{2}a_{3}\dots \\
\left[ \frac{1}{3}, \frac{2}{3} \right] & M[0.1a_{2}a_{3}\dots]\to 0.000\dots \\
\left[ \frac{2}{3},1 \right] & M[0.2a_{2}a_{3}\dots]\to 0.(a_{2}-2)(a_{3}-2)\dots
\end{matrix}
$$
- (d) Find all the 1-cycles and 2-cycles for the linear map using base 3.
$$
2-cycle:0.\dot{0},0.\dot{1}
$$