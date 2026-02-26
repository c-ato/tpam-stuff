Ideal conductor has internal $\bar{E}=\bar{0}$ so $\varphi=const$ so is equipotential $\implies \rho=\varepsilon_{0} \bar{\nabla}\cdot \bar{E}=0$ so a;; charges are plared on the surface so $\sigma\neq 0$ and $E_{n}=\frac{\sigma}{\varepsilon_{0}}$ and $E_{t}=0$ so $\bar{E} \perp \bar{S}$

Poisson Equation 
$$\nabla^{2}\varphi(\bar{r})=- \frac{\rho}{\varepsilon_{0}}$$
Absence of free charge $\nabla^{2}\varphi=0$

For a compleete set of boundary conditions $\nabla^{2}\varphi=0$ has a unique solution

Image charge, place an imaginary charge that is equidistant from place of intrests and use the effects 

$$\varphi(\bar{r})=\frac{Q}{4\pi\varepsilon_{0}R}=\frac{1}{4\pi\varepsilon_{0}} \int ^{}_{V} \frac{\rho(\bar{r})}{\left| \bar{r}-\bar{r}' \right|} \, dV $$
$$\bar{r}\gg \bar{r}'\qquad\frac{1}{\left| \bar{r}-\bar{r}' \right|}\sim \left[ r^{2}-2\bar{r}\bar{r}' \right]^{\frac{1}{2}}\sim \frac{1}{r}\left[ 1+ \frac{\bar{r}\bar{r}'}{r^{2}} \right]  $$
$$\varphi(\bar{r})=\frac{1}{4\pi\varepsilon_{0}}\int ^{}_{V} \rho(\bar{r}) \, dV \left[ \frac{1}{r}+\frac{\bar{r}\bar{r}'}{r^{3}} \right] =\frac{1}{4\pi\varepsilon_{0}}\left[ \frac{Q}{r}+\frac{\bar{p}\bar{r}}{r^{3}} \right]  $$
$$\bar{p}=\int ^{}_{V} \rho(\bar{r})\bar{r}' \, dV $$
$\bar{p}$ does not depend on the choice of the origin
$$Q=0=\int ^{}_{V} \rho(\bar{r}) \, dV=0\qquad \bar{p}=\int ^{}_{V} \rho(\bar{r})\bar{r}  \, dV  \neq 0$$
$$\bar{\tau}=\bar{p}\times \bar{E}_{0}\qquad U=-\bar{p}\cdot \bar{E}_{0}\qquad \bar{F}=(\bar{p}\cdot \bar{\nabla})\bar{E}$$
$$\tau_{m}=Fa\sin \theta=IaBa\sin \theta=ISB\sin \theta\implies \bar{\tau}_{m}=\bar{m}\times \bar{B}\qquad U=-\bar{m}\cdot \bar{B} $$
Induced currents
$$\bar{\nabla}\times \bar{B}=\mu_{0}\bar{J}\qquad \bar{F}=q\bar{v}\times \bar{B}=(\bar{J}\times \bar{B})dV\qquad $$
Faraday's law - not conservative, depends on path
$$\bar{\nabla}\times \bar{E}=-\frac{ \partial \bar{B} }{ \partial t } \implies \oint_{S}\bar{E}\cdot d \bar{l}=\int ^{}_{S} (\bar{\nabla}\times \bar{E}) \, d\bar{S}=-\int ^{}_{S} \frac{ \partial \bar{B} }{ \partial t }  \, d\bar{S}=-\frac{d}{dt}\int ^{}_{S} \bar{B} \, d\bar{S}   =- \frac{d\phi_{B}}{dt}$$
EMF 
$$\varepsilon=\frac{1}{q}\oint\bar{F}_{lorentz}\cdot d\bar{l}=-\frac{d\phi}{dt}$$
Dielectric (Insulators)
- Not free charges, bounded
- $E$-field permeates

Dielectric polarisations, Field weaker inside than vacuum  
- Polar dielectrics (permanent dipole moment) - isotropic distribution (direction of dipole moment are all equal). Partial alignment with external $E$-field
- Non-polar dielectrics (induced dipole moment. Weak complete alignment. 

Polarisation vector (Dipolar moment induced/volume)
$$\bar{P}=\frac{1}{\Delta V}\sum_{\Delta V}\bar{p}_{i}\qquad dp=dq\cdot l=\sigma_{p}dS\cdot l=\sigma_{p}\cdot dV$$

$$\sigma_{p}=P\qquad dp=P\cdot dV$$
$$dQ=\sigma_{p}dS=\bar{P}\cdot d\bar{S}$$
Total polarisation charge 
$$Q_{p}=\int ^{}_{V}\rho_{p}dV=-\int ^{}_{S}  \, dQ_{p}=-\int ^{}_{S} \bar{P}\cdot  \, d\bar{S}=-\int ^{}_{V}(\nabla \bar{P})  \, dV=\rho_{p}=\nabla \bar{P}   $$
Polarisation currents
$$\nabla \bar{J}_{p}=-\frac{ \partial \rho_{p} }{ \partial t } =\nabla \frac{ \partial \bar{P} }{ \partial t } \implies \bar{J}_{p}=\frac{ \partial \bar{P} }{ \partial t } $$
Linear, isotropic and homogeneous
$$\left| \bar{P} \right|\sim \left| \bar{E} \right|\qquad \bar{P}\uparrow\uparrow\bar{E}$$
$$\bar{P}=\chi_{E}\varepsilon_{0}\bar{E}$$
$\chi_{E}$ is electric susceptibility

Non-polar case
$$\bar{p}=\alpha\varepsilon_{0}\bar{E}\qquad \chi_{E}=\frac{P}{\varepsilon_{0}E}=\frac{np}{\varepsilon_{0}E}=\frac{n\alpha\varepsilon_{0}E}{\varepsilon_{0}E}=n\alpha$$
Polar case
$$\text{No field: }dN=\frac{d\Omega}{4\pi}=\frac{2\pi \sin \theta d\theta }{4\pi}=\frac{1}{2}\sin \theta d\theta$$
$$\text{E-field: }dN=\frac{1}{2}\sin \theta d\theta e^{ - \frac{U}{kT} }$$
$$U=\frac{1}{2}\sin \theta d\theta \left( 1+\frac{pE\cos \theta}{kT} \right)$$
$$\chi_{E}=\frac{P}{\varepsilon_{0}E}=\frac{np^{2}}{3\varepsilon_{0}kT}\implies\chi_{E}=n\left( \alpha+\frac{p^{2}}{3\varepsilon_{0}kT} \right)$$
This gives the gaseous dielectric electric susceptibility