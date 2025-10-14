[[Assessed Problem Sheet 1.pdf]]

A particle of mass $m$ is confined to the region $0 < x < d$. Within this region it is described by the wavefunction:
$$
\Psi(x,t)=A\sin\left( \frac{2\pi x}{d} \right)e^{ -\frac{iEt}{\hbar } }
$$
while outside this region the wavefunction = 0.

Calculate the value of the normalisation constant $A$ that gives an integrated probability of $1$ for finding this particle within the region $0 < x < d$. Assume that $A$ is a real number. [4]
$$
\Psi(x,t)=\left\{ \begin{matrix}
A\sin\left( \frac{2\pi x}{d} \right)e^{ - \frac{iEt}{\hbar } } & 0<x<d \\
0 & x\leq0,x\geq d
\end{matrix} \right. \qquad P(x,t)=\Psi^{*}\Psi=A^{2}\sin ^{2}\left( \frac{2\pi x}{d} \right)
$$
$$
1=\int_{-\infty}^{\infty} P(x,t) \, dx =A^{2} \int_{-\infty}^{\infty} \sin ^{2}\left( \frac{2\pi x}{d} \right) \, dx =A^{2}\int ^{d}_{0} \sin ^{2}\left( \frac{2\pi x}{d} \right) \, dx =\frac{A^{2}}{2}\int ^{d}_{0} 1-\cos \left( \frac{4\pi x}{d} \right) \, dx
$$
$$
\frac{A^{2}}{2}\left[ x-\frac{d}{4\pi}\sin\left( \frac{4\pi x}{d} \right) \right]^{d}_{0}=\frac{A^{2}d}{2}=1 \implies A=\sqrt{ \frac{2}{d} }
$$
Calculate the expectation value of the kinetic energy for this particle. [2]
$$
\hat{T}\Psi=\frac{\hat{p}^{2}}{2m}\Psi=-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} }\Psi=\frac{2\hbar^{2}\pi^{2}}{md^{2}}\Psi\implies
\left< T \right> =\int_{-\infty}^{\infty} \Psi^{*}\hat{T}\Psi \, dx =\frac{2\hbar^{2}\pi^{2}}{md^{2}} \int_{-\infty}^{\infty} \Psi^{*}\Psi \, dx =\frac{2\hbar^{2}\pi^{2}}{md^{2}}
$$
Calculate the expectation value $\left< x \right>$ for the position of this particle. What is the value of the wavefunction at position $x= \left< x \right>$? Comment on your answers. [4]
$$
\left< x \right>=x=\int_{-\infty}^{\infty} \Psi^{*}x\Psi \, dx=\frac{2}{d}\int ^{d}_{0} x\sin ^{2}\left( \frac{2\pi x}{d} \right) \, dx =\frac{1}{d}\int ^{d}_{0} x-x\cos\left( \frac{4\pi x}{d} \right) \, dx 
$$
%%
$$
\int ^{}_{} x\cos ax \, dx =\frac{1}{a}x\sin(ax)+\frac{1}{a^{2}}\cos(ax)
$$
%%
$$
\frac{1}{d}\left[ \frac{x^{2}}{2}-\frac{d}{2\pi}x\sin\left( \frac{2\pi x}{d} \right)-\frac{d^{2}}{4\pi^{2}}\cos\left( \frac{2\pi x}{d} \right) \right] ^{d}_{0}=\frac{d}{2}=x
$$
$$
P\left( \frac{d}{2},t \right)={ \frac{2}{d} }\sin ^{2}(\pi)=0
$$

Probability $P(x,t)$ at $x=\frac{d}{2}$ is $0$ so the cannot wave appear here, however it is the weighted mean and "expected" value.