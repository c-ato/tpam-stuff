[[Year 2 Assessed Problems 9.pdf]]

A particle of mass $m$ moves in one-dimension with the potential equal to zero. The particle is in a state described by the following wavefunction, which is a superposition of two energy eigenstates and is normalised to give unit probability over a length $a$. $$\Psi(x,t)=\sqrt[  ]{ \frac{2}{3a} }\left[ \cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }+\sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar } \right] $$
(a) Express the values $E_{1}$ and $E_{3}$ in terms of $a$, $m$ and $\hbar$. If the energy of the particle is measured, what possible values can be obtained and with what probabilities? [5]
$$-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi+V(x,y)\Psi=-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi=i\hbar \frac{ \partial  }{ \partial t } \Psi$$
$$-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi=\frac{\hbar^{2}}{2m} \sqrt[  ]{ \frac{2}{3a} }\left[ \frac{\pi^{2} }{a^{2}} \cos\left( \frac{\pi x}{a} \right) e^{ -E_{1}t/\hbar }+ \frac{9\pi^{2} }{a^{2}}\sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -E_{3}t/\hbar }\right] $$
$$i\hbar \frac{ \partial  }{ \partial t }\Psi =\sqrt[  ]{ \frac{2}{a} }\left[ E_{1}\cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }+E_{3}\sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar } \right] $$
$$\implies \frac{\hbar^{2}}{2m} \left[ \frac{\pi^{2} }{a^{2}} \cos\left( \frac{\pi x}{a} \right) e^{ -E_{1}t/\hbar }+ \frac{9\pi^{2} \sqrt[  ]{ 2 }}{a^{2}}\cos\left( \frac{3\pi x}{a} \right)e^{ -E_{3}t/\hbar }\right] $$
$$=\left[ E_{1}\cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }+E_{3}\sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar } \right] $$
Comparing coefficients of:
$$\cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }: \frac{\hbar^{2}}{2m} \frac{\pi^{2}}{a^{2}}=E_{1}\qquad \sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar }: \frac{\hbar^{2}}{2m} \frac{9\pi^{2}}{a^{2}}=E_{3}$$
(b) If instead the momentum of the particle is measured, what can be the possible results and what are their probabilities? [3]
$$\Psi=\sqrt[  ]{ \frac{2}{3a} }\cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }+\frac{2}{\sqrt[  ]{ 3a }}\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar }=\sqrt[  ]{ \frac{2}{3a} }\psi_{1}+\frac{2}{\sqrt[  ]{ 3a }}\psi_{2}=\sum_{i}c_{i}\psi_{i}$$
$$\sum_{i}\left| c_{i} \right|^{2}=1=\frac{2}{3a}+\frac{4}{3a}=\frac{2}{a}$$
Probability of $\psi_{1}$ is given by:
$$\frac{\left| c_{1} \right|^{2}}{\sum_{i}\left| c_{i} \right|^{2}}=\frac{\frac{2}{3a}}{\frac{2}{a}}=\frac{1}{3}$$
and probability of $\psi_{2}$ is given by:
$$\frac{\left| c_{2} \right|^{2}}{\sum_{i}\left| c_{i} \right|^{2}}=\frac{\frac{4}{3a}}{\frac{2}{a}}=\frac{2}{3}$$(c) If the energy is measured first and yields the higher of the possible values, what results could a subsequent measurement of the momentum yield and with what probabilities? [2]

If energy is measured first and gives the higher energy we will have "collapsed" the wavefunction onto the wave with this energy and so we will measure the momentum of the same wave in the second measurement: 

From above:
$$E_{3}=9E_{1}\therefore E_{3}>E_{1}$$
So we can see that it will pertain to $\psi_{2}$ as this corresponds to $E_{3}$, but now we will break $\cos$ down into more waves by the exponential equivalent of $\cos$ so to make it an eigenfunction:
$$\frac{2}{\sqrt[  ]{ 3a }}\psi_{2}=\frac{2}{\sqrt[  ]{ 3a }} \left( \frac{e^{ i \frac{3\pi x}{a} }+e^{ -i \frac{3\pi x}{a} }}{2}e^{ -iE_{3} t/\hbar} \right) =\frac{1}{\sqrt[  ]{ 3a }} \left( e^{ i \frac{3\pi x}{a} }e^{ -iE_{3} t/\hbar}+e^{ -i \frac{3\pi x}{a}e^{ -iE_{3} t/\hbar} } \right)=\frac{1}{\sqrt[  ]{ 3a }} \phi_{1}+\frac{1}{\sqrt[  ]{ 3a }}\phi_{2} $$
We can see as their coefficients are equal, they will have the same probability, $0.5$ each. Taking the momentum operators of each $a_{i}\phi _i$:
$$\hat{p}a_{1}\phi_{1}= \frac{\pi \hbar}{a}\sqrt[  ]{ \frac{3}{a} }\phi_{1}\qquad \hat{p}a_{2}\phi_{2}= -\frac{\pi \hbar}{a}\sqrt[  ]{ \frac{3}{a} }\phi_{2}$$
