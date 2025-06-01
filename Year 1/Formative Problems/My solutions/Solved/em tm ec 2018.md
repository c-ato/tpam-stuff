[[EM,TM,EC 2018.pdf]]

1. A uniform metal rod of Young’s modulus $Y = 2 × 10^{11} Pa$ and coefficient of linear thermal expansion $α = 10^{-5} K^{-1}$ is placed horizontally between two rigid vertical walls. At $10°C$, it just slips between the walls with no space to spare. Derive an expression for the thermal stress exerted by the rod on the walls as a function of $Y$, $α$ and the increase in temperature $∆T$ . Calculate the thermal stress if the temperature is increased to $30°C$
$$
Y=\frac{stress}{strain} \iff stress = Y\cdot strain=Y\cdot \frac{\Delta l}{l}=  Y \frac{\alpha l}{l}\Delta T=Y\alpha \Delta T
$$
$$
stress=2\times 10^{11}\cdot 10^{-5}\cdot 30=6\times 10^{7}N
$$
2. Use the equipartition theorem to estimate the molar heat capacity of solid sodium chloride at high temperature.
$$
DoF=12\therefore E= 6k_{B}T=6R
$$
3. The interaction between a pair of xenon atoms is well described by the Lennard Jones $6-12$ potential with an equilibrium spacing of $3.98  Å$ and a binding energy $\varepsilon = 0.020 eV$. Estimate, in SI units, the specific latent heat of vaporisation and the specific latent heat of fusion for xenon. [The molar mass of xenon is 131 g mol−1 and the density of solid xenon is approximately 3 g cm−3] 
$$
V(r)=4\varepsilon \left( \left( \frac{\sigma}{r} \right)^{12}- \left( \frac{\sigma}{r} \right)^{6} \right)
$$
$$
-V(r_{0})=\varepsilon=U_{0}
$$
$$
\frac{U_{0}\cdot N_{A}}{131}=14.73\dots J\,kg^{-1}
$$
The change in potential from solid to liquid for latent heat of fusion
$$
\frac{6\varepsilon-10\varepsilon}{2}\cdot \frac{N_{A}}{131}=-29.46\dots J\,kg^{-1}
$$
4. One mole of an ideal gas is compressed isothermally at a temperature $T_{0}$ until the original volume is halved. Sketch this process on a diagram of pressure versus volume. Derive an expression for the work done in terms of $T_{0}$ and state whether work is done on or by the system in this process.
![[em tm ec 2018 2025-04-17 15.51.57.excalidraw]]$$
dU=dQ-pdV=0\implies \int ^{}_{}  \, dQ = \int ^{}_{} \frac{Nk_{B}T_{0}}{V} \, dV=Nk_{B}T_{0}\ln(V) 
$$

Work is done by the system.

5. In a high-vacuum tunnel an electron is lifted just above the ground and shot at constant velocity $v = 1\,ms ^{-1}$ in a direction exactly parallel to the walls of the tunnel. By clever engineering a uniform magnetic field can be applied inside the tunnel in a direction perpendicular to the velocity of the electron. What is the strength and direction of the magnetic field that ensures that the electron never hits a tunnel wall?
$$
F=BQv\geq mg \iff B\geq \frac{mg}{Qv}\iff B\geq 5.577\dots \times 10^{-11}T
$$
Field will need to go horizontally and perpendicularly to the direction of velocity, being left of the direction of velocity.

6. The electric field due to an infinite sheet of fixed charge is $E= \frac{\sigma}{2\varepsilon_{0}}$ , where $σ$ is the surface charge density. Two sheets with the same charge density $\frac{σ}{2}$ are placed parallel to each other with a distance $d$ between them.
- (a) What is the electric field between the sheets?
$$
E=0
$$
- (b) If we put a positive charge q between the sheets, will it move if only the electrostatic force is considered? What happens if the charge is negative?

No, for both cases

7. In an alternate universe where space is two-dimensional, what form would Coulomb’s force law take? Justify your answer.
$$
2\pi r=C\qquad Ck=F\qquad A=Arc\qquad F_{A}=Ak\qquad \frac{Arc}{C}=\frac{F_{A}}{F}=\frac{A}{2\pi r}
$$
The total force can be found by the total of it across the entire circumference in $2D$ at any arbitrary radius $r$. We may then determine the force of an arc of fixed length, and we can see the ratio of the force this arc contains at a given $r$ by the above, and we see that $F_{A}\propto \frac{1}{r}$ as $F$, $\pi$ and $A$ are a constants. We also know that $F\propto \left|Q_{1}Q_{2} \right|$, thus:
$$
F=k\frac{Q_{1}Q_{2}}{r}
$$
8. In the circuit shown below, a voltmeter, of internal resistance, $r$, is used to measure the potential difference across $AB$. Redraw the circuit showing the voltmeter connected and derive an expression for $V_{AB}$ in terms of $ε$, $R$ and $r$.

![[Pasted image 20250418114917.png]]
![[em tm ec 2018 2025-04-18 11.50.00.excalidraw]]
$$
V_{AB}=\varepsilon \frac{\left( \frac{1}{r}+\frac{1}{R} \right)^{-1}}{\left( \frac{1}{r}+\frac{1}{R} \right)^{-1}+R}=\varepsilon\frac{\frac{rR}{r+R}}{\frac{rR}{r+R}+R}=\varepsilon\frac{rR}{2rR+R^{2}}= \frac{\varepsilon r}{2r+R}
$$
9. 
##### EITHER Part A
- (a) The normalised Maxwell-Boltzmann distribution of the speeds v of molecules of mass m in a gas at temperature T is given by $$P(v)=\left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}4\pi v^{2}\exp\left( \frac{-mv^{2}}{2k_{B}T} \right)$$
- 
	- (i) Explain the origins of the terms $4πv^{2}$ and $\exp \left( \frac{-mv^{2}}{2k_{B}T} \right)$ in this expression.

$4\pi v^{2}$ comes from the area of the surface of a sphere, on which is the density of states, the $\exp\left( \frac{-mv^{2}}{k_{B}T} \right)$ is the exponential of the Boltzmann factor which gives use the distribution of measuring a certain energy state.
- 
	- (ii) Show that the most probable speed is $\sqrt[  ]{ \frac{2k_{B}T}{m} }$
$$
\frac{d}{dt}(P(v))=0=\exp\left( \frac{-mv^{2}}{2k_{B}T} \right)\left( -\frac{mv}{k_{B}T}\cdot \left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}4\pi v^{2}+\left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}8\pi v \right)
$$
$$
=4\pi v\exp\left( \frac{-mv^{2}}{2k_{B}T} \right)\left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}\left( -\frac{mv}{k_{B}T}\cdot v+2 \right)=0
$$
$$
\iff  \frac{mv}{k_{B}T}\cdot v =2 \iff v^{2}=\frac{2k_{B}T}{m}\impliedby v=\sqrt[  ]{ \frac{2k_{B}T}{m} }
$$
- 
	- (iii) On the same axes, sketch the Maxwell-Boltzmann distributions for molecules at temperature $T$ and at temperature $4T$, paying careful attention to the areas under each curve and annotating your sketch with the most probable speeds.

![[em tm ec 2018 2025-04-20 13.38.19.excalidraw]]

- (b) The normalised distribution of free paths $x$ between collisions of molecules in a gas is given by $\frac{1}{l}\exp\left( \frac{-x}{l} \right)$
	- (i) Show that $l$ is the mean free path
$$
P_{l}(x)=\frac{1}{l}\exp\left( \frac{-x}{l} \right)\qquad \int_{0}^{\infty} xP_{l}(x) \, dx \overset{ a=\frac{1}{l} }{ = }\int_{0}^{\infty} axe^{ -ax } \, dx =a\int_{0}^{\infty} xe^{ -xa } \, dx 
$$
$$
=a\left[ - \frac{xe^{ -xa }}{a}-\frac{e^{ -xa }}{a^{2}} \right] ^{\infty}_{0}=\left[ -xe^{ -xa }-\frac{e^{ -xa }}{a} \right] ^{\infty}_{0}=-0-0-\left( -0-\frac{1}{a} \right)=\frac{1}{a}=l
$$
- 
	- (ii) Find the median and root-mean-square free paths in terms of $l$.
$$
\int ^{m}_{0} \frac{1}{l}e^{ - \frac{x}{l} } \, dx =\left[ -e^{ - \frac{x}{l} } \right] ^{m}_{0}=-e^{ - \frac{m}{l} }+1=0.5 \iff m=l \ln2
$$
$$
\sqrt[  ]{ \langle x^{2} \rangle  }=\sqrt[  ]{ \int ^{\infty}_{0} \frac{1}{l}e^{ - \frac{x}{l} }x^{2} \, dx  }=\sqrt[  ]{ \left[ - x^{2}e^{ - \frac{x}{l} } -2xle^{ - \frac{x}{l} }-2l^{2}e^{ -\frac{x}{l} }\right]^{\infty}_{0}  }=\sqrt[  ]{ 2l^{2} }=l\sqrt[  ]{ 2 }
$$
- 
	- (iii) Sketch the distribution of free paths and annotate your sketch with the median, mean, most probable and root-mean-square free paths. 

![[em tm ec 2018 2025-04-21 12.45.11.excalidraw]]
- 
	- (iv) $0.2$ moles of helium are sealed in a box. The pressure of the helium is one tenth of an atmosphere. The helium atoms are at thermal equilibrium with the sides of the box, which is at room temperature. Estimate the mean free path of the helium atoms. A single electron is added, at thermal equilibrium, to the centre of the box. Estimate its mean free path. 
$$
\langle x \rangle =\int ^{L}_{0} xP_{l}(x) \, dx =\int ^{L}_{0} \frac{x}{l}e^{ -\frac{x}{l} } \, dx $$
$$
=\left[ -xe^{ -\frac{x}{l} }-le^{ -\frac{x}{l} } \right] ^{L}_{0}=l-Le^{ -\frac{L}{l} }-le^{ - \frac{L}{l} }
$$
##### OR Part B
- (a) A monatomic ideal gas at initial pressure $P_{0}$ is expanded adiabatically to $8$ times its original volume $V_{0}$. Sketch this change on a diagram of pressure versus volume. Show that the final pressure is $\frac{P_{0}}{32}$.
$$
P_{1}V_{1}^{\gamma}=k=P_{0}V_{0}^{\gamma}\qquad C_{P}=\frac{5R}{2}\qquad C_{V}=\frac{3R}{2}\qquad \gamma=\frac{C_{P}}{C_{V}}=\frac{5}{3}
$$
$$
\implies P_{1}=P_{0} \frac{V_{0}^{\gamma}}{V_{1}^{\gamma}}=P_{0}\left( \frac{V_{0}}{V_{1}} \right)^{\gamma}=P_{0}\left( \frac{V_{0}}{8V_{0}} \right)^{\gamma}=P_{0} \left( \frac{1}{8} \right)^{\frac{5}{3}}=\frac{P_{0}}{32}
$$
![[em tm ec 2018 2025-04-22 09.29.19.excalidraw]]

- (b) Show that for an ideal gas $P^{1-\gamma} T^{\gamma}$ is constant in an adiabatic change, where $γ = \frac{C_{P}}{C_{V}}$ is the ratio of the heat capacities measured under constant pressure or constant volume conditions.
$$
PV^{\gamma}=constant\qquad PV=nRT \iff V=\frac{nRT}{P}\implies P\left( \frac{nRT}{P} \right)^{\gamma}
$$
$$
=P^{1-\gamma}T^{\gamma}(nR)^{\gamma}=constant\implies P^{1-\gamma}T^{\gamma}=\frac{constant}{(nR)^{\gamma}}=constant
$$
- (c) Show that in hydrostatic equilibrium, the pressure $P$ of a fluid follows $$\frac{ dP(h) }{ dh }=-\rho g $$where $h$ is the height, $ρ$ is the density of the fluid and $g$ is the acceleration due to gravity.

$P_{0}$ is the atmospheric pressure at the surface. $d$ is some depth from the top of the liquid, $l$ is the length from the bottom to the top of the liquid, hence giving $l-h=d$
$$
P=P_{0}+\rho gd=P_{0}+\rho g(l-h)\implies \frac{d}{dh}(P)=\frac{d}{dh}(P_{0}+\rho g(l-h))
$$
$$
=\frac{ dP }{ dh } =-\rho g
$$

- (d) Using $P^{1-\gamma}T^{\gamma}$ is constant, or otherwise, show that for an adiabatic change of an ideal gas $$\frac{(\gamma-1)dP}{P}=\frac{\gamma dT}{T}$$

$$
\frac{ d }{ dT } \left( P^{1-\gamma}T^{\gamma} \right) =(1-\gamma)P^{-\gamma}\frac{ dP }{ dT } T^{\gamma}+\gamma P^{1-\gamma}T^{\gamma-1}=0
$$
$$
\implies (\gamma-1)P^{-\gamma}\frac{ dP }{ dT } T^{\gamma}=\gamma P^{1-\gamma}T^{\gamma-1}
$$
$$
\implies (\gamma-1)P^{-1}\frac{ dP }{ dT } =\gamma T^{-1} \implies\frac{(\gamma-1)dP}{P}=\frac{\gamma dT}{T}
$$

- (e) In an adiabatic model of the atmosphere, a packet of air in the atmosphere does not exchange heat with surrounding packets of air.
	- (i) Show that the rate of change of temperature with height is constant in an adiabatic model for the atmosphere.

$$
dP=-\rho gdh\implies \frac{(\gamma-1)dP}{P}=\frac{\gamma dT}{T}=-\frac{\rho g(\gamma-1)dh}{P}
$$
$$
\implies \frac{dT}{dh}= -\frac{\rho g(\gamma-1)}{\gamma} \frac{T}{P}
$$
$$
\rho=\frac{m}{V}=\frac{nM}{V}\implies \frac{ dT }{ dh } =-\frac{\rho g(\gamma-1)}{\gamma} \frac{V}{nR}=-\frac{\rho g(\gamma-1)}{\gamma} \frac{nM}{nR\rho}
$$
$$
\frac{ dT }{ dh } =-\frac{(\gamma-1)}{\gamma} \frac{Mg}{R}=constant
$$

- 
	- (ii) Using an adiabatic model for the atmosphere, estimate the temperature and the pressure at the summit of Mount Everest ($8848 m$ above sea level). [ You may assume that the average molar mass of air is 29 g mol−1]
$$
\rho=\frac{PM}{RT}\implies P=\frac{\rho RT}{M}\qquad m=\frac{M}{N_{A}}\qquad C_{V}=\frac{3}{2}R
$$
$$
C_{p}=\frac{5}{2}R\implies\gamma=\frac{5}{3}\qquad \frac{\gamma-1}{\gamma}=\frac{2}{5}\qquad M=23\times 10^{-3}
$$
$$
\frac{ dT }{ dh } =-\frac{(\gamma-1)}{\gamma} \frac{Mg}{R}\implies T(h)=298-\frac{2Mgh}{5R}
$$
$$
T=\frac{PV}{nR}=\frac{PM}{\rho R}\implies \frac{ dT }{ dh } =\frac{ dP }{ dh } \frac{M}{\rho R}-\frac{d\rho}{dh} \frac{PM}{\rho^{2}R}
$$
$$
\frac{ dT }{ dh } =- \frac{gM}{R}-\frac{d\rho}{dh} \frac{T}{\rho }=-\frac{2Mg}{5R}
$$
$$
 \frac{1}{\rho} d\rho=-\frac{3Mg}{5RT}dh=\frac{3Mg}{5R} \frac{1}{298-\frac{2Mgh}{5R}}dh=\frac{3Mg}{1490R-2Mgh}dh
$$
$$
\ln\rho=-\frac{3}{2}\ln(1490R-2Mgh)+C
$$
$$
\rho=A(5RT)^{\frac{3}{2}}=\frac{PM}{RT}\implies P(h)=\frac{A(5)^{\frac{3}{2}}(RT(h))^{\frac{5}{2}}}{M}
$$
$$
P(0)=101kPa=\frac{A(5)^{\frac{3}{2}}(298R)^{\frac{5}{2}}}{M}\implies A= \frac{M\cdot101\times 10^{3}}{(5)^{\frac{3}{2}}(298R)^{\frac{5}{2}}}
$$
$$
P(h)=P_{0} \cdot\left( \frac{T}{298} \right)^{\frac{5}{2}}=P(h)=101\times 10^{3} \cdot\left( \frac{298-\frac{2Mgh}{5R}}{298} \right)^{\frac{5}{2}}
$$
$$
P(h)=101\times 10^{3} \cdot\left( 1-\frac{2Mgh}{1590R} \right)^{\frac{5}{2}}
$$
$$
T(8848)=201.9\dots K=-71.0\dots °C\qquad P(8848)= 41.1\dots kPa
$$
-  
	- (iii)  Estimate the work done on a packet of air containing $6.022 × 10^{23}$ molecules that is swept by the wind from sea level over the Indian Ocean to the summit of Everest. What becomes of this work done?
$$
mgh=nMgh=23\times 10^{-3}\cdot 9.81\cdot 8848=1996.3\dots J
$$
This work comes from the work on the gas packet, to GPE, so the gas packet ends up expanding its volume and the height/GPE increases.

10. 
##### EITHER Part A
A rhomboidal wire frame with side length $a$ has total resistance $R$. It is being pulled with a speed $v$, perpendicular to $PQ$, out of a region where there is a uniform magnetic field $B$ pointing out of the page. The extent of the $B$ field corresponds to the shaded region in the figure below.
![[Pasted image 20250424164642.png]]
Consider the moment when the left corner of the wire frame is a distance $x\leq \frac{a\sqrt[  ]{ 3 }}{2}$ inside the shaded area.

- (a) What is the induced e.m.f. and current in the wire? Express your results in terms of $B$, $x$, $v$ and $R$.
$$
\varepsilon=-N \frac{d\Phi_{m}}{dt}=-\frac{d}{dt}(BA)=-B\frac{ dA }{ dt } =-B \frac{d}{dt}\left( x\cdot x\tan 30 \right)=-\frac{2Bvx}{\sqrt[  ]{ 3 }}
$$
$$
I=\frac{V}{R}=\frac{\varepsilon}{R}=-\frac{2Bvx}{R\sqrt[  ]{ 3 }}
$$
- (b) State whether the induced current flows clockwise or counter-clockwise. 

The induced current runs clockwise

- (c) Draw a diagram of the forces on each of the sides of the rhomboidal wire generated by the interaction between the magnetic field and the induced current.
![[em tm ec 2018 2025-05-08 16.08.14.excalidraw]]
- (d) Obtain an expression for the total net force.
Symmetric about $y$ and $\left|F_{1} \right|=\left|F_{2} \right|$ so:
$$
F_{R}=F_{1}\sin30+F_{2}\sin30=2F_{1}\sin30=2BIL\sin 30=BIL
$$
$$
=B\left(-\frac{2Bvx}{R\sqrt[  ]{ 3 }}\right) \left( \frac{x}{\cos 30} \right)=-\frac{4B^{2}x^{2}v}{3R}
$$
- (e) verify that the work you do from $x = \frac{a\sqrt[  ]{ 3 }}{2}$ down to $x = 0$ equals the energy dissipated in the resistor. 
$$
W=\int _{\frac{a\sqrt[  ]{ 3 }}{2}}^{0} F \, dx =\int ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0} \frac{4B^{2}x^{2}v}{3R} \, dx =\frac{4B^{2}v}{3R}\left[ \frac{x^{3}}{3} \right] ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0}=\frac{B^{2}va^{3}}{2R\sqrt[  ]{ 3 }}
$$
$$
\frac{x}{v}=t= \frac{a\sqrt[  ]{ 3 }}{2v}\implies dt=\frac{1}{v}dx
$$
$$
W=\int ^{t}_{0} P \, dt =\int ^{t}_{0} I^{2}R \, dt = \int ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0} \frac{I^{2}R}{v} \, dx =\int ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0} \frac{4B^{2}v^{}x^{2}}{3R}\, dx 
$$
$$
\frac{4B^{2}v}{3R}\int ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0} x^{2}\, dx =\frac{4B^{2}v}{3R}\left[ \frac{x^{3}}{3} \right] ^{\frac{a\sqrt[  ]{ 3 }}{2}}_{0}=\frac{B^{2}va^{3}}{2R\sqrt[  ]{ 3 }}
$$
$$
\therefore \int ^{}_{} F \, dx=\int ^{}_{} P \, dt  
$$
##### OR Part B
A long straight stationary wire in the $(y, z)$ plane is parallel to the $y$ axis and passes through the point $z = h$, see figure below. 

A current $I$ flows in the wire, returning by a remote conductor whose field we may neglect. 

Lying in the $(x, y)$ plane is a thin rectangular loop with two of its sides, of length $a$, parallel to the $y$ axis. The length $b$ of the other two sides is negligible.

![[{B082E151-932D-4503-94A9-0F8617B975E8}.png]]

- (a) Use Ampere’s law to obtain an expression for the magnetic field $B$ generated by the current at the centre of the loop on the $x$ axis, at a distance $r$ from the wire as shown in the figure above. Verify your answer using the Biot-Savart law. Provide a sketch to illustrate the direction of the magnetic field

$I_{encl}$ is just the total current $I$, $\mathbf{B}$ is constant at fixed $r$ so becomes scalar when integrated by $d\mathbf{l}$
$$
\oint\mathbf{B}\,d\mathbf{l}=\mu_{0}I_{encl}=\mu_{0}I\qquad \oint\mathbf{B}\,d\mathbf{l}=B\oint dl2B\pi r=\mu_{0}I\implies B=\frac{\mu_{0}I}{2\pi r}
$$
$$
\delta \mathbf{B}= \frac{\mu_{0}I\delta \mathbf{l}\land\mathbf{\hat{r}}}{4\pi r^{2}}=\frac{\mu_{0}I\delta l}{4\pi r^{2}}\implies B=\frac{\mu_{0}I}{4\pi r^{2}} \oint\,dl=\frac{2\pi r\mu_{0}I}{4\pi r^{2}}=\frac{\mu_{0}I}{2\pi r}
$$
![[em tm ec 2018 2025-05-08 17.47.56.excalidraw]]

- (b) Write down the algebraic expressions for the components of the magnetic field along the $\hat{x}$, $\hat{y}$, and $\hat{z}$ directions, in terms of $I$, $x$, $h$, $r$ and any relevant constant.
$$
\mathbf{B}=B_{x}\hat{\mathbf{x}}+B_{y}\hat{\mathbf{y}}+B_{z}\hat{\mathbf{z}}\qquad B_{y}=0 \because \hat{\mathbf{y}}\parallel\mathbf{B}\qquad\mathbf{B}=B_{x}\hat{\mathbf{x}}+B_{z}\hat{\mathbf{z}}
$$
The field is radial so we may use trigonometry, where $\theta$ is the angle made by an arbitrary $\mathbf{r}$, in the $x-z$ plane, and the $z$-axis backwards, where $\theta$ is clockwise from looking above. This gives
$$
B_{x}=B\cos \theta=\frac{h}{r}\frac{\mu_{0}I}{2\pi r}=\frac{\mu_{0}Ih}{2\pi r^{2}}\qquad\qquad B_{z}=B\sin \theta=\frac{x}{r}\frac{\mu_{0}I}{2\pi r}=\frac{\mu_{0}Ix}{2\pi r^{2}}
$$
- (c) Sketch a plot of the $z$ component, $B_{z}(x)$, of the magnetic field as a function of $x$. 

![[em tm ec 2018 2025-05-09 09.33.10.excalidraw]]

11. 
##### EITHER Part A
- (a) State the AC analogue expression to Ohm’s law and define any symbols used. 
$$
V=IZ
$$
Where $Z$ is the complex impedance.

- (b) For the circuit shown below find the complex impedance between $A$ and $B$ and, hence, the impedance of the circuit.
$$
Z_{T}=\left( \frac{1}{Z_{R}}+\frac{1}{Z_{R}+Z_{C}} \right)^{-1}=\frac{R^{2}-\frac{Rj}{\omega C}}{2R-\frac{j}{\omega C}}=\frac{2R^{3}-\frac{R^{2}j}{\omega C}+\frac{R}{\omega^{2}C^{2}}}{4R^{2}+\frac{1}{\omega^{2}C^{2}}}
$$
$$
=\frac{2R^{3}\omega^{2}C^{2}+R-R^{2}\omega Cj}{4R^{2}\omega^{2}C^{2}+1}
$$
$$
\tan ^{-1}\left( -\frac{R^{2}\omega C}{4R^{2}\omega^{2}C^{2}} \right)=\tan ^{-1}\left( -\frac{1}{4\omega C} \right)
$$
- (c) In the circuit below, $R = 2 kΩ$, $L = 20 mH$ and $C = 136 μF$. The sinusoidal voltage source is $V (t) = V_{0} \sin(ωt)$ with $V_{0} = 20 V$ and $ω = 2000 rad/s$.
	- (i) For both switches closed, find an expression for the current, I(t), as a function of time and calculate the average power delivered to the circuit.
$$
I=\frac{V}{Z}= \frac{20\sin(\omega t)}{R}
$$
$$
\langle P \rangle =\frac{\omega}{2\pi}\int ^{\frac{2\pi}{\omega}}_{0} VI \, dt =\frac{400\omega}{2\pi R}\int ^{\frac{2\pi}{\omega}}_{0} \sin ^{2}(\omega t) \, dt =\frac{100\omega}{\pi R}\int ^{\frac{2\pi}{\omega}}_{0}1- \cos(\omega t)\,dt
$$
$$
=\frac{100\omega}{\pi R}\left[ t-\frac{\sin(\omega t)}{\omega} \right] ^{\frac{2\pi}{\omega}}_{0}=\frac{100\omega}{\pi R}\left( \frac{2\pi}{\omega} \right)=\frac{200}{R}=0
.1W
$$
	- (ii) After only $S_{1}$ is opened, find an expression for the current as a function of time. 
$$
Z=R+j\omega L\implies \phi=\tan ^{-1}\left( \frac{\omega L}{R} \right)=0.0199\dots
$$
$$
I=I_{0}\sin(\omega t+\phi)
$$
$$
I_{0}=\frac{V_{0}}{\left|Z \right|}=\frac{20}{\left|R+j\omega L \right|}=\frac{20}{\sqrt[  ]{ R^{2}+\omega^{2}L^{2} }}=0.0099\dots A
$$
	- (iii) For both $S_{1}$ and $S_{2}$ open, calculate the resonant angular frequency, $ω_{0}$, with the current and voltage in phase. Calculate the impedance of the circuit. Calculate the maximum energy stored in the capacitor during oscillations.
$$
\omega_{0}L- \frac{1}{\omega_{0}C}=0\implies\omega_{0}=\frac{1}{\sqrt[  ]{ LC }}=606.33\dots rad/s
$$
$$
Q=\frac{\omega_{0}L}{R}\implies V_{C}=V_{0}Q\implies E_{C}=\frac{1}{2}C(V_{0}Q)^{2}=1\mu J
$$
##### OR Part B
- (a) 
	- (i) State Thevenin’s theorem and explain how you find the Thevenin equivalent voltage.

The ability for linear circuits of resistors, currents and voltage supplies to be simplified and reduced to a single sources (of each type) and resistor around a singular component in series (parallel of current supply).
- 
	- (ii) Explain how you calculate Thevenin’s resistance.

Remove the component of interest first and the supplies, then find the total resistance of this circuit.

External circuits cannot differentiate between practical voltage and current supplies.

- (b) State the superposition theorem and when it is used.

When you have multiple sources, you may find the effect that they have individually and total this for the overall effect.

- (c) For the circuit below:

![[Pasted image 20250425215555.png]]
- 
	- (i) Draw Thevenin's equivalent circuit as seen at terminals A and B and find the Thevenin equivalent voltage and resistance

![[em tm ec 2018 2025-04-25 22.11.09.excalidraw]]
- 
	- (ii) Find and draw Norton’s equivalent circuit as seen at terminals $A$ and $B$;

![[em tm ec 2018 2025-04-25 21.56.20.excalidraw]]
- 
	- (iii) Calculate the current through, and voltage across, an additional $4.7 kΩ$ resistor connected between terminals $A$ and $B$. 
$$
V=IR=2\times 10^{-3}\cdot \frac{5\times 10^{3}\cdot 4.7\times 10^{3}}{(5+4.7)\times 10^{3}}=4.845\dots V
$$
$$
I=\frac{V}{R}=\frac{10}{(4.7+5)\times 10^{3}}=1.03\dots mA
$$
