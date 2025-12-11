[[Year 2 Assessed Problems 9.pdf]]

A particle of mass $m$ moves in one-dimension with the potential equal to zero. The particle is in a state described by the following wavefunction, which is a superposition of two energy eigenstates and is normalised to give unit probability over a length $a$. $$\Psi(x,t)=\sqrt[  ]{ \frac{2}{3a} }\left[ \cos\left( \frac{\pi x}{a} \right)e^{ -iE_{1}t/\hbar }+\sqrt[  ]{ 2 }\cos\left( \frac{3\pi x}{a} \right)e^{ -iE_{3}t/\hbar } \right] $$
(a) Express the values $E_{1}$ and $E_{3}$ in terms of $a$, $m$ and $\hbar$. If the energy of the particle is measured, what possible values can be obtained and with what probabilities? [5]

$\Psi$ is not an eigenfunction of the momentum operator, so we need to convert $\Psi$ into a different form. 
$$\Psi(x,t)=\sqrt[  ]{ \frac{2}{3a} }\left[\left( \frac{e^{ i\frac{\pi x}{a} }+e^{ -i\frac{\pi x}{a} }}{2} \right) e^{ -iE_{1}t/\hbar }+\sqrt[  ]{ 2 }\left( \frac{e^{ i\frac{3\pi x}{a} }+e^{ -i\frac{3\pi x}{a} }}{2} \right)e^{ -iE_{3}t/\hbar } \right] $$
$$\Psi(x,t)=\underbrace{ \frac{1}{\sqrt[  ]{ 6a }} }_{ c_{1} }\overbrace{ e^{ i\frac{\pi x}{a}} e^{ -iE_{1}t/\hbar }}^{\psi_{1}}+\underbrace{ \frac{1}{\sqrt[  ]{ 6a }} }_{ c_{2} }\overbrace{ e^{ -i\frac{\pi x}{a}}e^{ -iE_{1}t/\hbar } }^{^{\psi_{2}}}+\underbrace{ \frac{1}{2\sqrt[  ]{ 3a }} }_{ c_{3} }\overbrace{ e^{ i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar } }^{ \psi_{3} }+\underbrace{ \frac{1}{2\sqrt[  ]{ 3a }} }_{ c_{4} }\overbrace{ e^{ -i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar } }^{ \psi_{4} }$$
Note that this is in the form of a Hermitian wavefunction $\Psi= \sum_{i}c_{i}\psi_{i}$, we will use this later.
$$-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi+V(x,y)\Psi=-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi=i\hbar \frac{ \partial  }{ \partial t } \Psi$$
$$-\frac{\hbar^{2}}{2m}\frac{ \partial^{2}  }{ \partial x^{2} } \Psi=\frac{\hbar^{2}}{2m}\frac{\pi^{2}}{a^{2}\sqrt[  ]{ 6a }}\left( e^{ i\frac{\pi x}{a}}e^{ -iE_{1}t/\hbar }+e^{ -i\frac{\pi x}{a}}e^{ -iE_{1}t/\hbar } \right)+\frac{\hbar^{2}}{2m}\frac{9\pi^{2}}{2a^{2}\sqrt[  ]{ 3a }} \left( e^{ i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar }+e^{ -i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar } \right)  $$
$$=i\hbar \frac{ \partial  }{ \partial t }\Psi = \frac{E_{1}}{\sqrt[  ]{ 6a }}\left( e^{ i\frac{\pi x}{a}}e^{ -iE_{1}t/\hbar }+e^{ -i\frac{\pi x}{a}}e^{ -iE_{1}t/\hbar } \right)+\frac{E_{3}}{2\sqrt[  ]{ 3a }} \left( e^{ i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar }+e^{ -i\frac{3\pi x}{a}}e^{ -iE_{3}t/\hbar } \right) $$
Then comparing coefficients:
$$\frac{\hbar^{2}}{2m}\frac{\pi^{2}}{a^{2}\sqrt[  ]{ 6a }}= \frac{E_{1}}{\sqrt[  ]{ 6a }}\impliedby \frac{\hbar^{2}\pi^{2}}{2ma^{2}}=E_{1}\qquad\frac{\hbar^{2}}{2m}\frac{9\pi^{2}}{2a^{2}\sqrt[  ]{ 3a }}= \frac{E_{1}}{2\sqrt[  ]{ 3a }}\impliedby \frac{9\hbar^{2}\pi^{2}}{2ma^{2}}=E_{3}$$

(b) If instead the momentum of the particle is measured, what can be the possible results and what are their probabilities? [3]

$$\hat{p}\psi_{1}=\frac{\pi}{a}\psi_{1}\therefore p_{1}=\frac{\pi \hbar}{a}\qquad \hat{p}\psi_{2}=\frac{\pi}{a}\psi_{2}\therefore p_{2}=-\frac{\pi}{a}$$
$$\hat{p}\psi_{3}=\frac{3\pi}{a}\psi_{3}\therefore p_{3}=\frac{3\pi \hbar}{a}\qquad \hat{p}\psi_{4}=\frac{3\pi}{a}\psi_{4}\therefore p_{4}=-\frac{3\pi}{a}$$
and probability of $\psi_{i}$ is given by:
$$P(p_{i})=\frac{\left| c_{i} \right|^{2}}{\sum_{n}\left| c_{n} \right|^{2}}=\frac{\left| c_{i} \right|^{2}}{\frac{1}{2a}}$$
$$P(p_{1})=\frac{1}{3}\qquad P(p_{2})=\frac{1}{3}\qquad P(p_{3})=\frac{1}{6}\qquad P(p_{4})=\frac{1}{6}$$

(c) If the energy is measured first and yields the higher of the possible values, what results could a subsequent measurement of the momentum yield and with what probabilities? [2]

$$E_{3}=9E_{1} \therefore E_{3}>E_{1}$$
The wavefunctions corresponding with $E_{3}$ are $\psi_{3}$ and $\psi_{4}$. If energy is measured first and gives the higher energy we will have "collapsed" the wavefunction onto the waves with this energy and so we will measure the momentum of either $p_{3}$ or $p_{4}$ in the second measurement. Note that both these eigenfunctions have the same $c_{i}$ coefficients and so have equal probability:
$$P(p^{E_{3}}_{i}|E_{3})=\frac{\left| c_{i}^{E_{3}} \right|^{2}}{\sum_{n} \left| c_{n}^{E_{3}} \right|^{2}}
\qquad P(p_{3}|E_{3})=\frac{1}{2}\qquad P(p_{4}|E_{3})=\frac{1}{2}$$


