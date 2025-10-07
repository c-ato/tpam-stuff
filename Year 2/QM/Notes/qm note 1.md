$n\lambda=2\pi r$ and $p=\frac{h}{\lambda}\implies p=\frac{nh}{2\pi r}=mv\implies v=\frac{nh}{2\pi mr}$
$$
E=- \frac{e^{2}}{8\pi\varepsilon_{0}r}=-\frac{1}{2}mv^{2}=-\frac{n^{2}h^{2}}{8\pi^{2}mr^{2}}\implies r_{n}=\frac{n^{2}h^{2}\varepsilon_{0}}{\pi m}
$$
wave equation is basic postulate - cannot be derived from other equations.

Schrodinger equations has to satisfy De Broglie's relation, energy conservation, must be linear for superposition principle, and for a free particle to be sin/cos wave functions.

$E=\hbar\omega\qquad p=\hbar k\qquad E=\frac{p^{2}}{2m}+V\implies \hbar\omega=\frac{\hbar^{2}k^{2}}{2m}+V$

Free particle: $F=- \frac{ dV }{ dt }=0\therefore V=V_{0}\quad const$

$\psi=A\left[ \cos(kx-\omega t)+\gamma \sin(kx-\omega t) \right]\implies \frac{ \partial \psi }{ \partial t }=A\omega(\sin(kx-\omega t)-\gamma \cos(kx-\omega t))$
$\implies \frac{ \partial^{2} \psi }{ \partial x^{2} }=\left[ \cos(kx-\omega t)+\gamma \sin(kx-\omega t)\right]$

$\alpha \frac{ \partial^{2} \psi }{ \partial x^{2} }+V_{0}\psi=\beta \frac{ \partial \psi }{ \partial t }$

Static potential schrodinger wave equation: $Ae^{ i(kx-\omega t) }$

Static potential, time dependent schrodinger equation: $\frac{-\hbar^{2}}{2m}\frac{ \partial^{2} \psi }{ \partial x^{2} }+V_{0}\psi=i\hbar \frac{ \partial \psi }{ \partial t }$

Wavfn is complete desc of state of quantum, contains all physical info of obj, however physical obs is must be real, so wavefn is not an observable - must apply mathematical operator on wavfn to extracft physical info.#

pdf - probability density funct is normalised on entire range of $x$ - that it to say it does definety exist in this range:

$\int_{-\infty}^{\infty} P(x,t) \, dx$

In QM $P(x,t)=\left| \psi \right|^{2}=\psi^{*}\psi$ as is real

If $\psi_{1}$ is sol of TISE, then $A\psi_{1}$ is also a solution by the condition of linearity.

$\int_{-\infty}^{\infty} A\psi^{*}A\psi \, dx=\left| A \right|^{2}\int_{-\infty}^{\infty} \psi^{*}\psi \, dx=1$

for bounded $\psi(x,t)=\left\{ \begin{matrix}A\cos\left( \frac{\pi x}{a} \right)e^{ -\frac{iEt}{\hbar} }&-\frac{a}{2}<x< \frac{a}{2} \\ 0 & \text{otherwise}\end{matrix} \right.$

$\int_{-\infty}^{\infty} P(x,t) \, dx= A^{2}\int ^{\frac{a}{2}}_{- \frac{a}{2}} \cos ^{2}\left( \frac{\pi x}{a} \right) \, dx=1\implies A=\sqrt[  ]{ \frac{2}{a} }$

$\left< x \right>=\int_{-\infty}^{\infty} xP(x,t) \, dx$: weighted means of $x$ with portable document file

$\left< x \right> =\int_{-\infty}^{\infty} \psi^{*}x\psi \, dx$

QM operator extracts physical info from wavfn

$\hat{O}$ is  mathematical operator

QM Postulate 2: For every physical observable, there is an associated mathematical operator.

$\hat{p}=-i \hat{h} \frac{ \partial  }{ \partial x }$ - momentum operator is a differential operator

$\psi$ acts as a eigenfunction of QM operators - that is the function that returns unchanged after the operator acts, and the eigenvalue is the value that scales the eigenfunction after the operator acts

$\hat{p}\psi=p\psi$ then $\left< p \right>=\int_{-\infty}^{\infty} \psi^{*}\hat{p}\psi \, dx=\int_{-\infty}^{\infty} \psi^{*}p\psi \, dx=p\int_{-\infty}^{\infty} \psi^{*}\psi \, dx=p$

$KE= \frac{1}{2m}\hat{p}\hat{p}=- \frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} }$
Total energy $=\hat{E}=i \hbar \frac{ \partial  }{ \partial t }$
