[[Mechsheet4qn.pdf]]

2. Assessed Let a particle of mass $m$ be attached to two springs, both with spring constant $k$. The end of one spring (denoted $α$, with natural length $a$) is attached at a point $A$, with the end of the other spring (denoted $β$, with natural length $2a$) attached at a point $B$, a distance $4a$ directly above $A$. The mass is attached to the free end of both springs. The particle is at a location $x(t)$, where $x$ is measured upwards such that $x = 0$ at point $A$.
- (a)
![[mech assessed 4 2025-03-22 03.58.47.excalidraw]]
- (i) The extension in spring $α$ is given by $x − a$.
As spring $\alpha$ starts from $A\,(x=0)$ and ends at where the mass is connected $(x)$ this gives the total length to be $x$ and the extension is the total length $-$ the original length so $x-a$
- (ii) The extension in spring (β) is given by $(2a − x)$.
As spring $\beta$ starts from $B\,(x=4a)$ and ends at where the mass is connected $(x)$ this gives the total length to be $4a-x$ and so the extension is the total length $-$ the original length so $4a-x-2a$$=2a-x$
- (b) Hence write down the equation for conservation of energy.
$$
\frac{1}{2}ke_{1}^{2}+\frac{1}{2}ke_{2}^{2}+\frac{1}{2}m\dot{x}^{2}=\frac{1}{2}k(x-a )^{2}+\frac{1}{2}k(2a-x)^{2}+\frac{1}{2}m\dot{x}^{2}+mgx=E
$$
- (c) If the particle is initially at rest at $x = 2a$, find the value of the constant energy.
$$
t=0\qquad \dot{x}=0\qquad x=2a\implies \frac{1}{2}k(a)^{2}+\frac{1}{2}k(0)^{2}+\frac{1}{2}m(0)^{2}+mg(2a)=\frac{ka^{2}}{2}+2mga=E\forall t
$$
- (d) Find the height at which the particle will next come to rest.
$$
\frac{1}{2}k(2x^{2}-6ax+5a^{2})+ \frac{1}{2}m\dot{x}^{2}+mgx=\frac{ka^{2}}{2}+2mga
$$
$$
\dot{x}=0\implies kx^{2}-3kax+\frac{5ka^{2}}{2}+0+mgx-\frac{ka^{2}}{2}-2mga=0=kx^{2}+(mg-3ka)x+2ka^{2}-2mga
$$
$$
x^{2}+ \left( \frac{mg}{k}-3a \right)x+\left( 2a^{2}-\frac{2mga}{k} \right)
$$
We know that $\dot{x}=0$ at $x=2a$, hence $x-2a$ is a root and $X_{1}=2a$. 
$$
(x-X_{1})(x-X_{2})=x^{2}-(X_{1}+X_{2})x+X_{1}X_{2}=0
$$
Hence the second root and solution to where $\dot{x}=0$ is given by:
$$
-(X_{1}+X_{2})=\frac{mg}{k}-3a\implies X_{2}=a-\frac{mg}{k}
$$
3. A smooth (i.e. no friction) wire is in the shape of a helix so that $x = a \cos θ (t)$, $y = a \sin θ (t)$, $z = aθ (t) /2$, with the central ($z$) axis pointing vertically upwards. A small bead of mass $m$ moves along the wire, starting from height $z = 2πa$ with speed $0$.
- (a) By writing down the position vector and differentiating, show that $$\mathbf{\dot{r}}=-a\dot{\theta}\sin \theta \mathbf{i}+a\dot{\theta}\cos\theta \mathbf{j}+\frac{a}{2}\dot{\theta}\mathbf{k},$$and hence that the kinetic energy of the bead is given by $$\frac{5ma^{2}}{8}\dot{\theta}$$
$$
\mathbf{r}=x\mathbf{i}+y\mathbf{j}+z\mathbf{k}=a\cos \theta \mathbf{i}+a\sin \theta \mathbf{j}+\frac{a\theta}{2}\mathbf{k}\implies \mathbf{\dot{r}}=\dot{x}\mathbf{i}+\dot{y}\mathbf{j}+\dot{z}\mathbf{k}=-a\dot{\theta}\sin \theta \mathbf{i}+a\dot{\theta}\cos\theta \mathbf{j}+\frac{a}{2}\dot{\theta}\mathbf{k}
$$
$$
E_{KE}=\frac{1}{2}m\mathbf{\dot{r}}^{2}=\frac{1}{2}m(\mathbf{\dot{r}}\cdot \mathbf{\dot{r}})^{2}=\frac{1}{2}m\left( a^{2}\sin ^{2}\theta+a\cos ^{2}\theta+\frac{a^{2}}{4} \right)\dot{\theta}^{2}=\frac{5ma^{2}}{8}\dot{\theta}^{2}
$$
- (b) Write down the potential energy of the bead in terms of θ, choosing the potential to be zero at $z = 0$.
$$
E_{PE}=mgh=mgz=\frac{mga}{2}\theta
$$
- (c) Hence show that conservation of energy gives $$\frac{5ma^{2}}{8}\dot{\theta}^{2}+ \frac{mga}{2}\theta=2mg\pi a$$
$$
\frac{5ma^{2}}{8}\dot{\theta}^{2}+ \frac{mga}{2}\theta=E\qquad t=0\qquad z=\frac{a}{2}\theta=2\pi a\qquad \dot{r}=0\therefore \frac{5ma^{2}}{8}\dot{\theta}^{2}=0 \implies E=2mg\pi a
$$
- (d) By rearranging to find an equation for $\dot{\theta}^{2}$, find the maximum value that $θ$ can attain. What does this mean physically?
$$
\frac{5ma^{2}}{8}\dot{\theta}^{2}+ \frac{mga}{2}\theta=2mg\pi a\implies \dot{\theta}^{2}=\frac{(16\pi-4\theta)g}{5a}\geq0
$$
$$
\therefore 16\pi\geq 4\theta \iff 4\pi\geq \theta \therefore \theta_{max}=4\pi
$$
This shows maximum height (as the initial condition) and in the $\dot{\theta}^{2}$ equation it shows a linear relationship with $-\theta$ so it won't go higher than the original height.