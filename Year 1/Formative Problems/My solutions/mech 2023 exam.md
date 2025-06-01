
[[1Mech.pdf]]

1. 
- (a) The displacement $x(t)$ of a mass $m$ attached to a spring obeys the equation of motion$$\ddot{x}+\gamma \dot{x}+\omega^{2}x=\frac{F(t)}{m}$$where $γ ≥ 0$ and $ω > 0$ are constants and $F(t)$ is a driving force. Let the mass have initial displacement $x(0) = x_{0} > 0$ and initial velocity $v(0) = 0$. 
	- (i) Let $γ = 0$ and $F(t) = 0$. Find $x(t)$. 
$$
\ddot{x}+\omega^{2}x=0\implies \ddot{x}+\omega^{2}x=0 \iff x(0)=A\sin(\omega t)+B\cos(\omega t)=B=x_{0}
$$
$$
\dot{x}(0)=A\omega\cos(\omega t)-B\omega \sin(\omega t)=0 \therefore A=0
$$
- 
	- (ii) Let $γ = 0$ and $F(t) = F_{0} \cos(ωt)$, where $F_{0} > 0$ is a constant. Verify that the function $$x(t) = C \cos(ωt) + \frac{F_{0}}{2m\omega}  t \sin(ωt)$$, where $C$ is any constant, satisfies the equation of motion and the initial condition $v(0) = 0$. Determine $C$. Describe how $x(t)$ behaves in the limit t → ∞. 
$$
\dot{x}=-C\omega \sin(\omega t)+\frac{F_{0}}{2m}t\cos(\omega t)+\frac{F_{0}}{2m\omega}  \sin(ωt)
$$
$$
\ddot{x}=-C\omega^{2}\cos(\omega t)-\frac{F_{0}\omega}{2m}t\sin(\omega t)+\frac{F_{0}}{m}\cos(ωt)
$$
$$
\ddot{x}+\omega^{2}x=\cancel{ -C\omega^{2}\cos(\omega t) }\cancel{ -\frac{F_{0}\omega}{2m}t\sin(\omega t) }+\frac{F_{0}}{m}\cos(ωt)+\cancel{ \omega^{2}C \cos(ωt) } \cancel{ + \frac{F_{0}\omega}{2m}  t \sin(ωt) }
$$
$$
=\ddot{x}+\omega^{2}x=\frac{F_{0}}{m}\cos(\omega t)=\frac{F(t)}{m}\qquad x(0)=C=x_{0}
$$
As $t\to \infty$, the mass oscillates with (linearly) increasing amplitude.
- 
	- (iii) Let $γ > 0$ and $F(t) = F_{0} \cos(ωt)$, where $F_{0} > 0$ is a constant. Without finding $x(t)$, describe how $x(t)$ behaves in the limit t → ∞ and justify your answer.

Oscillates with boundedness, or oscillates increasingly.

- (b) A particle of mass $m$ moves under gravity along a coil of frictionless wire in the shape of an elliptical helix. The Cartesian coordinates of the particle are $$x(t) = a \cos θ (t)\qquad y(t) = b \sin θ (t)\qquad z(t) = cθ (t)$$where $θ (t)$ is some function of $t$, and $a$, $b$ and $c$ are positive constants with $a > b$. 
	- (i) Find the particle’s velocity vector, and hence show that $$\frac{1}{2}m\dot{\theta}^{2}(a^{2}\sin ^{2}\theta+b^{2}\cos ^{2}\theta+c^{2}) + mgcθ = E$$where $E$ is a constant. 
$$
\dot{x}=-a\dot{\theta}\sin \theta\qquad\dot{y}=b\dot{\theta}\cos \theta\qquad\dot{z}=c\dot{\theta}
$$
$$
E=KE+GPE=\frac{1}{2}m\dot{x}^{2}+\frac{1}{2}m\dot{y}^{2}+\frac{1}{2}m\dot{z}^{2}+mgz
$$
$$
=\frac{1}{2}m(\dot{\theta}^{2}a^{2}\sin ^{2}\theta+\dot{\theta}^{2}b^{2}\cos ^{2}\theta+c^{2}\dot{\theta}^{2})+mgc\theta=\frac{1}{2}m\dot{\theta}^{2}(a^{2}\sin ^{2}\theta+b\cos ^{2}\theta+c^{2})+mgc\theta
$$
- 
	- (ii) Let the particle be initially stationary at position $θ (0) = 0$. Find an expression for $\dot{\theta}^{2}$. Assuming that the particle never stops after it is released, show that $θ (t) < 0$ for all $t > 0$. 
$$
\dot{\theta}=0\qquad\theta=0\qquad E=0\therefore \frac{1}{2}m\dot{\theta}^{2}(a^{2}\sin ^{2}\theta+b\cos ^{2}\theta+c^{2})+mgc\theta=0
$$
$$
\implies \dot{\theta}^{2}=- \frac{gc\theta}{a^{2}\sin ^{2}\theta+b \cos ^{2}\theta+c^{2}}>0\implies \theta<0
$$

- 
	- (iii) Show that $\dot{\theta}^{2}$ has a local maximum or local minimum whenever $$(a^{2} − b^{2}) (\sin^{2} θ − θ \sin(2θ )) + b^{2} + c^{2} = 0$$Show that above holds for infinitely many values of $θ < 0$, and interpret this result.
$$

$$