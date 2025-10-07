[[Assessed Problem Sheet 1.pdf]]

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
\frac{A^{2}}{2}\left[ x+\frac{d}{4\pi}\sin\left( \frac{4\pi x}{d} \right) \right]^{d}_{0}=\frac{A^{2}d}{2}=1 \implies A=\sqrt{ \frac{2}{d} }
$$
$$
\hat{T}\Psi=\frac{\hat{p}^{2}}{2m}\Psi=-\frac{\hbar}{2m}\frac{ \partial^{2}  }{ \partial x^{2} }\Psi=\frac{4A\pi^{2}}{d^{2}}\Psi=\frac{4\pi^{2}}{d^{2}}\sqrt[  ]{ \frac{2}{d} }\Psi
$$
$$
\int_{-\infty}^{\infty} \Psi^{*}\hat{T}\Psi \, dx =\frac{4\pi^{2}}{d^{2}}\sqrt[  ]{ \frac{2}{d} } \int_{-\infty}^{\infty} \Psi^{*}\Psi \, dx =\frac{4\pi^{2}}{d^{2}}\sqrt[  ]{ \frac{2}{d} }
$$
$$
\left< x \right>=x=\int_{-\infty}^{\infty} \Psi^{*}x\Psi \, dx
$$