2) The force on a particle (mass $m$, charge $e$ with position vector $\mathbf{r}$) moving under the influence of a constant magnetic field $\mathbf{B}$ is $\mathbf{F} = e \dot{\mathbf{r}} × \mathbf{B}$. This is the only force acting on the particle, which starts at $0$ with velocity $V$ initially.

(a) Show that 
$$
m \ddot{\mathbf{\underline{r}}}=e \dot{\mathbf{\underline{r}}}\times \mathbf{B},
$$
and give the appropriate initial conditions.
$$
F(r)=m\mathbf{\ddot{\underline{r}}}=Q \mathbf{\underline{v}}\times\mathbf{\underline{B}}=Q \mathbf{\dot{\underline{r}}}\times\mathbf{\underline{B}}\therefore m \mathbf{\ddot{\underline{r}}}=e\mathbf{\dot{\underline{r}}}\times\mathbf{\underline{B}}
$$
(b) By integrating once, show that
$$
m\mathbf{\dot{\underline{r}}}=e\mathbf{\underline{r}}\times B +mV
$$
$$
\int ^{}_{}m \mathbf{\ddot{\underline{r}}}  \, d\mathbf{\underline{r}} =\int ^{}_{} e\mathbf{\dot{\underline{r}}}\times\mathbf{\underline{B}} \, d\mathbf{\underline{r}} =m\mathbf{\dot{\underline{r}}}=e \int ^{}_{} \mathbf{\dot{\underline{r}}} \, d\mathbf{\underline{r}}\times B= e\mathbf{\underline{r}}\times\mathbf{\underline{B}} +c
$$

$$
t=0\qquad \mathbf{\dot{\underline{r}}}=\mathbf{\underline{V}}\qquad \mathbf{\underline{r}}=0\implies m\mathbf{\underline{V}}=e 0\times\mathbf{\underline{B}} +c\therefore c=m\mathbf{\underline{V}}
$$
$$
\implies m\mathbf{\dot{\underline{r}}}=e\mathbf{\underline{r}}\times B +m\mathbf{\underline{V}}
$$
(c) If $B = (m/e, 0, 0)$ in Cartesians, use the definition of the vector product to write down an expression for $r × B$ where $r = (x, y, z).$

$$
\mathbf{\underline{r}}\times \mathbf{\underline{B}}=\frac{zm}{e}k-\frac{ym}{e}j
$$
(d) We will now find the position of the particle in terms of $x(t), y, z,$ for an initial velocity $V = (V_{1}, 0, V_{3})$.
- (i) By considering the $i$ component of the governing equation, solve to find an expression for x(t)
$$
m\mathbf{\dot{\underline{r}}}=e\mathbf{\underline{r}}\times B +m\mathbf{\underline{V}}\implies \mathbf{\dot{\underline{r}}}=\frac{e}{m}\left( \frac{zm}{e}k-\frac{ym}{e} j\right)+\mathbf{\underline{V}}
$$
$$
\mathbf{\dot{\underline{r}}}=zj-yk+V_{1}i+V_{3}k=(V_{1})i+(z)j+(V_{3}-y)k=\dot{x}i+\dot{y}j+\dot{z}k
$$
$$
m \ddot{\mathbf{r}}=e \dot{\mathbf{r}}\times \mathbf{B},=m(V_{3}-y)j+m(-z)j\implies \mathbf{\ddot{\underline{r}}}=(V_{3}-y)j+(-z)k=\ddot{x}i+\ddot{y}j+\ddot{z}k
$$
$$
\because \ddot{x}=0\implies x(t)=\int ^{}_{} \dot{x} \, dt=\int ^{}_{} V_{1} \, dt=V_{1}\int ^{}_{}  \, dt =V_{1}t
$$
- (ii) By combining your $y$ and $z$ equations (i.e. the $j$ and $k$ components) to form a single second order ODE for $y(t)$, find $y(t)$ and hence $z(t)$.

Comparing vector coefficients from before:
$$
\dot{y}=z(t)\qquad \ddot{y}=V_{3}-y\qquad \dot{z}=V_{3}-y\qquad\ddot{z}=-z\implies z(t)=A\cos t+B\sin t=\dot{y}
$$
$$
t=0\qquad \dot{y}=0 \therefore A=0\iff\dot{y}=B\sin t=z(t)
$$
$$
\int ^{}_{} \dot{y} \, dt =y(t)=-B\cos t+c\overset{ t=0 }{ \underset{ y=0 }{ \implies } }c=B\therefore y=B(1-\cos t)
$$
$$
\ddot{y}=V_{3}-y \iff B\cos t=V_{3}-B(1-\cos t)\implies B=V_{3}
$$
$$
\therefore y(t)=V_{3}(1-\cos t)\qquad z(t)=V_{3}\sin t
$$
(e) What shape is the particle path?

Circular spiral towards the $x$ axis, off centred.

4) Find the value of the constant $h = r^{2}\dot{\theta}$, and suitable initial conditions for $u(θ) = \frac{1}{r}$, $\frac{du}{d\theta}$ for the following particles under the action of a central force.

(a) The particle is initially at $r = a$, moving with radial velocity $v$ and transverse (also known as angular) velocity $aω$.

$$
\mathbf{\underline{r}}=re_{r}\qquad \mathbf{\dot{\underline{r}}}=\dot{r}e_{r}+ r e_{\theta}\dot{\theta}\qquad \mathbf{\ddot{\underline{r}}}=(\ddot{r}-r\dot{\theta}^{2})e_{r}+(2\dot{r}\dot{\theta}+r\ddot{\theta})e_{\theta}\qquad h=r^{2}\dot{\theta}
$$
Observe transverse velocity component and then at initial conditions:
$$
r \dot{\theta}=a\omega\qquad h=r^{2}\dot{\theta}\overset{ t=0 }{ \underset{ r=a }{ \implies } } h=a^{2}\omega
$$
$$
u=\frac{1}{a}\qquad \dot{r}=-h \frac{du}{d\theta}\implies\frac{du}{d\theta}=-\frac{\dot{r}}{h}\overset{ t=0 }{ \underset{ \dot{r}=v }{ \implies } } \frac{du}{d\theta}=-\frac{v}{h}=-\frac{v}{a^{2}\omega}
$$
(b) The particle is initially at $r = b$, moving away from the origin with speed $V$ in a direction which makes an angle $\frac{π}{3}$ with the outward pointing radial vector.

Observe radial velocity component and then at initial conditions:
$$
t=0\qquad u=\frac{1}{b}\qquad \mathbf{\dot{\underline{r}}}=V\qquad \theta=\frac{\pi}{3}\implies \dot{r}=\mathbf{\dot{\underline{r}}}\cos \theta  =\frac{V}{2}
$$
$$
r\dot{\theta}=\mathbf{\dot{\underline{r}}}\sin \theta\implies \dot{\theta}=\frac{V\sqrt[  ]{ 3 }}{2b} \implies h=\frac{V\sqrt[  ]{ 3 }b}{2}\qquad \frac{du}{d\theta}=-\frac{\dot{r}}{h}=-\frac{\frac{V}{2}}{\frac{V\sqrt[  ]{ 3 }b}{2}}= -\frac{1}{\sqrt[  ]{ 3 }b}
$$
(c) The particle is initially at $r = c$, moving with speed $w$ in a direction making an angle $π/4$ with the inward pointing radial vector.
$$
t=0\qquad u=\frac{1}{c}\qquad \mathbf{\dot{\underline{r}}}=w\qquad \theta=\frac{\pi}{4}\implies \dot{r}=\mathbf{\dot{\underline{r}}}\cos \theta  =\frac{w\sqrt[  ]{ 2 }}{2}
$$
$$
r\dot{\theta}=\mathbf{\dot{\underline{r}}}\sin \theta\implies \dot{\theta}=\frac{w\sqrt[  ]{ 2 }}{2c} \implies h=\frac{w\sqrt[  ]{ 2 }c}{2}\qquad \frac{du}{d\theta}=-\frac{\dot{r}}{h}=-\frac{\frac{w\sqrt[  ]{ 2 }}{2}}{\frac{w\sqrt[  ]{ 2 }c}{2}}= -\frac{1}{c}
$$
