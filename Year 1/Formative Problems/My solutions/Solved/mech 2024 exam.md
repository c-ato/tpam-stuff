[[A38707_LCLIMechanics_QP_Main2024.pdf]]

1. 
- (a) Consider the equation $$\int ^{}_{} u \, dt=mg+\ddot{x}$$where $u$ is velocity, $t$ is time, $m$ is mass, $g$ is acceleration due to gravity, $x$ is distance and double dot denotes the second derivative with respect to time. Is this equation dimensionally homogeneous? Justify your answer.
$$
[LT^{-1}][T]=[M][LT^{-2}]+[LT^{-2}]
$$
No all of the units above are not dimensionally equivalent so it is not homogeneous

- (b) If a particle of mass $m$ is subject to a force of the form $F = F_{0} \cos (ωt)$, where $F_{0}$ and $ω$ are constants and $t$ is time, find the acceleration, velocity and position of the particle as a function of time, given the particle starts at $x = 0$ with constant velocity $u$.
$$
F=m\ddot{x}=F_{0}\cos(\omega t)
$$
$$
\ddot{x}=\frac{F_{0}}{m}\cos (\omega t)
$$
$$
\dot{x}=\int ^{}_{} \ddot{x} \, dt =\frac{F_{0}}{m\omega}\sin(\omega t)+A\overset{ t=0 }{ \underset{ \dot{x}=u }{ \implies } }A=u
$$
$$
x=\int ^{}_{} \dot{x}  \, dt=-\frac{F_{0}}{m\omega^{2}}\cos(\omega t) +ut+B\overset{ t=0 }{ \underset{ x=0 }{ \implies } } B=\frac{F_{0}}{m\omega^{2}}
$$
$$
x=\frac{F_{0}}{m\omega^{2}}(1-\cos(\omega t)) +ut
$$
- (c) Starting from Newton’s Second Law, show that $$\frac{d}{dt}(\mathbf{r}\times \mathbf{\dot{r}})=0$$for a particle moving under the action of a central force, where $\mathbf{r}$ is position, $m$ is mass and $t$ is time. Hence, prove that the motion is constrained to lie in a plane.

$$
F=m\mathbf{\ddot{r}}\qquad\mathbf{r}=r e_{r}\qquad \mathbf{\dot{r}}=\dot{r}e_{r}+re_{\theta}\dot{\theta}\qquad \mathbf{r}\times \mathbf{\dot{r}}=re_{r} \times \dot{r}e_{r}+re_{r}\times  re_{\theta}\dot{\theta}=r^{2}\dot{\theta}
$$
$$
\mathbf{\ddot{r}}=(\ddot{r}-r\dot{\theta}^{2})e_{r}+(r\ddot{\theta} +2\dot{r}\dot{\theta})e_{\theta}
$$
$$
\mathbf{F}=Fe_{r}=m\ddot{\mathbf{r}}=m((\ddot{r}-r\dot{\theta}^{2})e_{r}+(r\ddot{\theta} +2\dot{r}\dot{\theta})e_{\theta})
$$
$$
r\ddot{\theta} +2\dot{r}\dot{\theta}=0\implies r^{2}\ddot{\theta}+r \dot{r}\dot{\theta}= \frac{d}{dt}(r^{2}\dot{\theta})=0
$$
$$
\therefore \frac{d}{dt}(\mathbf{r}\times \mathbf{\dot{r}})=\frac{d}{dt}(r^{2}\dot{\theta})=0
$$
Let $\mathbf{h}=\mathbf{r}\times \mathbf{\dot{r}}$.
$$
\because \mathbf{h}=\mathbf{r}\times \mathbf{\dot{r}} \qquad\mathbf{r\perp \mathbf{h}} \therefore \mathbf{r}\cdot \mathbf{h}=0
$$
The position vector is always perpendicular to the constant vector so must be restricted to the perpendicular plane.

- (d) Formulate a complete model system for a situation where a particle of mass m is acted on by an outward pointing central force of the form$$F(r)=-\frac{\alpha}{r^{2}}+\frac{\beta}{r^{3}}$$where $α$ and $β$ are constants. The particle is initially located a distance $a$ from the centre of the force, moving with radial velocity $v$ and transverse velocity $w$. You may assume that $\mathbf{\dot{r}}=\dot{r}e_{r}+r \dot{\theta} e_{\theta}$ for a position vector $r$ in polar coordinates, $\dot{r}=-h \frac{du}{d\theta}$ and $$\frac{d^{2}u}{d\theta^{2}}+u=-\frac{F\left( \frac{1}{u} \right)}{mh^{2}u^{2}}$$where $u=\frac{1}{r}$ and you should carefully define $h$. Not that you are not asked to solve the resulting model.
$$
\frac{d^{2}u}{d\theta^{2}}+u=-\frac{-\alpha u^{2}+\beta u^{3}}{mh^{2}u^{2}}= \frac{\alpha-\beta u}{mh^{2}}\implies \frac{d^{2}u}{d\theta^{2}}+\left( 1+\frac{\beta}{mh^{2}} \right)u=\frac{\alpha}{mh^{2}}
$$
$$
h=r^{2}\dot{\theta}=rr\dot{r}\overset{ t=0 }{ = }aw\qquad\theta\overset{ t=0 }{ = }0\qquad u=\frac{1}{r}\overset{ t=0 }{ \underset{ r=a }{ \implies } }u=\frac{1}{a}\qquad \dot{r}\overset{ t=0 }{ = }v=-h \frac{du}{d\theta}
$$
$$
\implies\frac{du}{d\theta}=-\frac{v}{aw}\qquad \frac{d^{2}u}{d\theta^{2}}=\frac{\alpha}{mh^{2}}-\left( 1+\frac{\beta}{mh^{2}} \right)u\overset{ t=0 }{ = }\frac{d^{2}u}{d\theta^{2}}=\frac{\alpha}{ma^{2}w^{2}}-\left( \frac{1}{a}+\frac{\beta}{ma^{3}w^{2}} \right)
$$
2. 
- (a) First consider a particle of mass m moving in a straight line with position x. Starting from Newton’s second law, prove the principle of Conservation of Energy for a force that depends only on x.
$$
F=m\ddot{x}\implies m\ddot{x}\dot{x}=F\dot{x}=F \frac{dx}{dt}=\frac{d}{dt}\left( \frac{1}{2}m\dot{x}^{2} \right)\implies \int ^{x}_{0} F \, dx =\frac{1}{2}m\dot{x}^{2}+C
$$
$$
F=-\frac{dU}{dx}\implies \int ^{x}_{0} -\frac{dU}{dx}  \, dx= -U(x)+K=\frac{1}{2}m\dot{x}^{2}+C\implies\frac{1}{2}m\dot{x}^{2}+U(x)=E
$$
$E$ is given as a constant and this shows that the sum of potential and kinetic energy is conserved for a given $x$.

- (b) Now consider a particle of mass $m$ at position $P(θ ,t)$ moving on a smooth wire shaped in a circle of radius $a$ lying in a vertical plane, where $θ$ is the polar angle that the particle makes with the centre of the circle $O$ measured from the upwards vertical and $t$ is time. The particle is attached to one end of a spring (spring constant $k$, natural length $\frac{a}{2}$) with the other end of the spring attached to the top of the wire $T (θ = 0)$. See Figure 1. 
![[{E0C819E7-67B4-422F-B737-12AAADCBDD8C}.png]]
- Figure 1: Sketch of the wire, mass and spring system for part (b), showing the top of the circle $T (θ = 0)$, the particle at point $P(θ ,t)$ and the origin $O$ at the centre of the circle.
	- (i) Show that the kinetic energy of the particle is given by $$\frac{1}{2}ma^{2}\dot{\theta}^{2}$$where the dot denotes the first derivative with respect to time.
$$
\frac{1}{2}mv^{2}=E\qquad v=a\dot{\theta}\implies \frac{1}{2}ma^{2}\dot{\theta}^{2}=E
$$
- 
	- (ii) Show that the extension in the spring is given by $$2a\sin\left( \frac{\theta}{2} \right)-\frac{a}{2}$$
![[mech 2024 exam 2025-05-13 09.08.29.excalidraw]]
$$
a\sin\left( \frac{\theta}{2} \right)=\frac{l_{extended}}{2}\therefore l_{extended}=2a\sin\left( \frac{\theta}{2} \right)\qquad e=l_{extended}-l_{natural}=2a\sin\left( \frac{\theta}{2} \right)-\frac{a}{2}
$$
- 
	- (iii) Find the height of the particle above the centre of the circle.
![[mech 2024 exam 2025-05-13 09.11.28.excalidraw]]
$$
h=a\cos \left( \frac{\theta}{2} \right)
$$
- 
	- (iv) Hence, show that the total energy of the system is given by $$\frac{1}{2}ma^{2}\dot{\theta}^{2}+mga\cos \theta+\frac{ka^{2}}{2}\left( 2\sin\left( \frac{\theta}{2} \right)-\frac{1}{2} \right)^{2}=E$$
$$
E_{Total}=KE+GPE+EP\qquad KE=\frac{1}{2}mv^{2}=\frac{1}{2}ma^{2}\dot{\theta}^{2}\qquad GPE = mgh=mga\cos \theta
$$
$$
EP=\frac{1}{2}ke^{2}=\frac{1}{2}k\left( 2a\sin\left( \frac{\theta}{2} \right)-\frac{a}{2} \right)^{2}=\frac{ka^{2}}{2}\left( 2\sin\left( \frac{\theta}{2} \right)-\frac{1}{2} \right)^{2}
$$
$$
\therefore E_{Total}=\frac{1}{2}ma^{2}\dot{\theta}^{2}+mga\cos \theta+\frac{ka^{2}}{2}\left( 2\sin\left( \frac{\theta}{2} \right)-\frac{1}{2} \right)^{2}
$$
- 
	- (v) If the particle starts from rest at $θ = \frac{π}{3}$, find the value of $θ$ when the particle will stop again. You may leave your answer in terms of a trigonometric function for $θ$. 

$$
\theta =\frac{\pi}{3}\qquad E=\frac{mga}{2}+\frac{ka^{2}}{2} \frac{1}{4}
$$
$$
E=\frac{1}{2}ma^{2}\dot{\theta}^{2}+mga\cos \theta+\frac{ka^{2}}{2}\left( 2\sin\left( \frac{\theta}{2} \right)-\frac{1}{2} \right)^{2}\qquad\dot{\theta}=0\qquad 
$$
$$
\frac{mga}{2}+\frac{ka^{2}}{8}=mga\cos \theta+\frac{ka^{2}}{2}\left( 2\sin\left( \frac{\theta}{2} \right)-\frac{1}{2} \right)^{2}=
$$
$$
\frac{mga}{2}+\frac{ka^{2}}{2} \frac{1}{4}=mga\cos \theta+\frac{ka^{2}}{2}\left( 4\sin ^{2}\left( \frac{\theta}{2} \right)-2\sin\left( \frac{\theta}{2} \right)+\frac{1}{4} \right)
$$
Comparing $mga$ coefficient and $\frac{ka^{2}}{2}$. $n,m \in \mathbb{Z}$
$$
\cos \theta=\frac{1}{2}\implies \theta=\cos ^{-1}\left( \frac{1}{2} \right)=2n\pi\pm\frac{\pi}{3}
$$
$$
4\sin ^{2}\left( \frac{\theta}{2} \right)-2\sin\left( \frac{\theta}{2} \right)+\frac{1}{4} =\frac{1}{4}\implies 2\sin \left( \frac{\theta}{2} \right)\left( 2\sin\left( \frac{\theta}{2} \right)-1 \right)=0\quad \sin\left( \frac{\theta}{2} \right)=0\quad\theta=2m\pi
$$
$$
2\sin\left( \frac{\theta}{2} \right)-1=0\qquad \theta=2\sin ^{-1}\left( \frac{1}{2} \right)=4m\pi\pm\frac{\pi}{3}
$$
$\therefore$ $m=2n$ such that $\theta=4m\pi\pm \frac{\pi}{3}$ and this satisfies the conditions where the particle stops.