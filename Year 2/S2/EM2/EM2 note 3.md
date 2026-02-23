$\rho_{p}=\bar{\nabla}\bar{P}$ and $\sigma_{p}=\bar{P}\cdot \bar{n}$

Charge density
$$\rho=\rho_{F}+\rho_{p}\implies \bar{\nabla}\bar{E}=\frac{\rho}{\varepsilon_{0}}=\frac{1}{\varepsilon_{0}}(\rho_{F}-\bar{\nabla}\bar{P})$$
$$\bar{\nabla}(\varepsilon_{0}\bar{E}+\bar{P})=\rho_{F}$$
Electric Displacement, $F$ is for free
$$\bar{D}=\varepsilon_{0}\bar{E}+\bar{P}=\varepsilon_{0}(\bar{E}+\chi_{E}\bar{E})=\varepsilon_{0}(1+\chi_{E})\bar{E}=\varepsilon_{0}\varepsilon \bar{E}\qquad \bar{\nabla}\bar{D}=\rho_{F}$$
$$\int ^{}_{S} \bar{D} \, d\bar{S}=\int ^{}_{V} \rho_{F} \, dV=Q_{F}  $$
Relative permitivity (dielectric constant)
$$\varepsilon=1+\chi_{E}\geq 0$$
Displacement $\bar{D}$ is computational (just a linear combination of $E$ and $P$)

Boundary conditions	$$\int ^{}_{S} \bar{D} \, dS=0 \implies \bar{D}_{1}\bar{S}_{1}+\bar{D}_{2}\bar{S}_{1}=0\therefore \bar{D}_{1}\cdot \bar{n}=\bar{D}_{2}\cdot \bar{n}=\varepsilon_{1}E_{1n}=\varepsilon_{2}E_{2n}$$
$$\oint_{L}\bar{E}d\bar{l}=\bar{E}_{1}\bar{l}_{1}+\bar{E}_{2}\bar{l}_{2}=0\qquad \bar{l}_{1}=-\bar{l}_{2}\implies E_{1t}=E_{2t}=D_{1n}=D_{2n}$$
$$\frac{\tan \theta_{1}}{\tan \theta_{2}}=\frac{\varepsilon_{1}}{\varepsilon_{2}}$$
$$w_{E}=\frac{1}{2}ED$$
Atom:
Angular momentum $L=m_{e}rv$
Magnetic Dipole Moment $m=IS=- \frac{e}{T}\pi r^{2}=-\frac{evr}{2}$

Gyromagnetic ratio
$\Gamma= \frac{m}{L}=- \frac{e}{m_{e}}$
Quantisation
$\to L=n\hbar$ $n\in \mathbb{N}$
$m= \frac{e\hbar}{2me}n$ - boar magneton

Spin is also another source of magnetism

$$\bar{M}=\frac{1}{\Delta V} \sum_{\Delta V} \bar{\mu}_{i}$$
Magnetic susceptibility $\chi_{B}$
$$\bar{M}=\chi_{B} \frac{\bar{B}}{\mu_{0}}$$
Types of magnetisms:
Diamagnetism $\bar{M} \uparrow\downarrow\bar{B},\, \chi_{B}<0$
Paramagnetic $\bar{M} \uparrow\uparrow\bar{B},\, \chi_{B}>0$
Ferrormagnetic, large non-linear $\bar{M}$
Superconductors $\chi_{B}=-1$

Diamagnetism:
Faraday's law $$\oint_{L}\bar{E}d\bar{l}=\frac{d}{dt}\int ^{}_{S} =\bar{B} \, d\bar{S} =2\pi rE=\pi r^{2} \frac{dB}{dt}$$
$$E=\frac{r}{2} \frac{dB}{dt}$$
$$\tau=eEr=m_{e}r^{2}\implies \frac{d\omega}{dt}=\frac{e}{2m_{e}} \frac{dB}{dt}$$
$$\Delta\omega=\frac{2}{2m_{e}}\int ^{t}_{0}  \frac{dB}{dt}\, dt= \frac{eB}{2m_{e}}=-\Gamma B $$
Induced Magnetic Moment ($I\mathcal{M}$) and universal diamagnetism
$$\bar{m}_{I\mathcal{M}}=\Gamma \bar{L}_{I\mathcal{M}}=- \frac{e}{2m_{e}}m_{e}\Delta \bar{\omega}r^{2}\implies \bar{m}_{I\mathcal{M}}=- \frac{e^{2}r^{2}}{4m_{e}}\bar{B}$$
Monatomic gas
$$\bar{m}_{I\mathcal{M}}=- \frac{Ze^{2}r^{2}_{0}}{6m_{e}}\bar{B}$$
$r_{0}$ is the electron orbit radius
$$\chi_{B}=\frac{\mu_{0}M}{B}=- \frac{\mu_{0}nZe^{2}r_{0}^{2}}{6m_{e}}$$
Paramagnetic $(\chi_{B}>0)$
Permanent dipole moment
$$m_{atom}\neq 0\qquad U=-\bar{m}\cdot \bar{B}$$
Weak alignment of dipoles
$$\bar{P}= \frac{np^{2}}{3kT}\bar{E}\leftrightarrow \bar{M}= \frac{nm ^{2}}{3kT}\bar{B}$$
$$\bar{m}=\frac{1}{m_{0}}\chi_{B}\bar{B}\implies \chi_{B}=\mu_{0}n\left[ \frac{m ^{2}}{3kT} - \frac{Ze^{2}r_{0}^{2}}{6m_{e}} \right] $$
Levitation (Non-uniform field)
$$F_{mag}=m \frac{dB}{dz}(nV)=MV \frac{ dB }{ dz } = \frac{B\chi_{B}}{\mu_{0}}V \frac{ dB }{ dz } =\rho Vg$$
$$B \frac{ dB }{ dz } = \frac{\mu_{0}\rho g}{\left| \chi_{B} \right|}$$
Magnetisation currents (cylinder with slice)
$$m=M\pi r^{2}dx=i_{m}dx\pi r^{2}$$
$i_{m}=\bar{M}\times \bar{n}\implies \bar{i}_{m}\perp \bar{M} \therefore \bar{M}\parallel\bar{n}=0$
Surface current density $i_{m}$

Volume current $\bar{M} \parallel \bar{e}_{z}$
$V_{A}=V_{B}=dxdydz$ where $A$ is at $(x,y,z)$ and $B$ is at $(x+dx,y,z)$
Magnetic moment
$$m_{A}=M_{Z}(x,y,z)\cdot dxdydz\qquad m_{B}=m_{A}+ \left( \frac{ \partial M_{z} }{ \partial x } dx \right)dxdydz$$
$$I_{B}= \frac{m_{B}}{dxdy}= \frac{m_{A}+\left(  \frac{ \partial M_{z} }{ \partial  dx }  dx\right)dzxdydz }{dxdy}=I_{A}+ \left( \frac{ \partial M_{z} }{ \partial x }  \right) dxdz$$
$$I_{y}=I_{A}-I_{B}=- \left( \frac{ \partial M_{z} }{ \partial x }  \right)dxdz$$
$J_{y}= \frac{I_{y}}{dxdy}=$
skipskipskip
$$\bar{H}=\frac{1}{\mu_{0}}\bar{B}-\bar{M}\implies \nabla \times \bar{H}=\bar{J}_{F} +\frac{ \partial D }{ \partial t } $$