---
tags:
  - physics
  - matter
  - temperature
---
![[Pasted image 20241010091502.png]]
$I(\lambda)$ is the intensity per wavelength at wavelength.
$$
\therefore I=\int ^{\infty}_{0} I(\lambda) \, dx 
$$
$$
\implies I=\sigma T^{4}\,,\, \lambda_{peak}=\frac{b}{T}
$$
Classically:
$$
I(\lambda)= \frac{n(\lambda)}{\lambda}k_{B}T\implies I(\lambda)\propto \frac{1}{\lambda^{2}},\lambda\to 0,I(\lambda)\to \infty
$$
$$
I(\lambda)= \frac{2\pi c}{\lambda^{4}}k_{B}T
$$
Boltzmann distribution:
$$
P(E)= \frac{e^{-\frac{E}{k_{B}T}}}{k_{B}T}
$$
$$
\bar{E}=\int ^{\infty}_{0} E p(E) \, dE=k_{B}T
$$

Planck:
$$
E=hf=h \frac{c}{\lambda}
$$
$$
\implies \bar{E}= \frac{\frac{hc}{\lambda}}{e^{\frac{hc}{\lambda k_{b}T}}-1}
$$
$$
\bar{E}(\lambda\to \infty)\ll 1
$$
$$
e^{\frac{hc}{\lambda k_{b}T}}\approx 1+ \frac{hc}{\lambda k_{B}T}+\dots\implies \bar{E}= \frac{\frac{hc}{\lambda}}{e^{\frac{hc}{\lambda k_{b}T}}-1}\approx \frac{\frac{hc}{\lambda}}{1+\frac{hc}{\lambda k_{b}T}-1}
$$
$=k_{B}T$ retaining the property for lower energies (higher $\lambda$).
