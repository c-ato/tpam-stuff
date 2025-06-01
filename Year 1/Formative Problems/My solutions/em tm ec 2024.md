[[EM,TM,EC 2024.pdf]]

1. Define and explain the zeroth and first laws of thermodynamics. What is meant by the terms isothermal, isobaric, isochoric and adiabatic?

Where $A$, $B$ and $C$ are temperatures of systems in thermal equilibrium, if $A=B$ and $A=C$ then $B=C$, this is the zeroth law of thermodynamics. The first law is $\Delta U=W_{on}+Q_{in}$

2. $12$ grams of $O^{16}$ gas (molar mass of $32$ amu) is expanded from its original volume of $2$ litres at a fixed temperature of $300 K$. During this expansion, its pressure changes from $200 kPa$ to $100 kPa$. Calculate

- (a) The work done by the gas

$$
W_{by}=\int ^{200kPa}_{100kPa} P \, dV=\int ^{200kPa}_{100kPa} \frac{nRT}{V} \, dV =nRT \ln(2)
$$
$$
=\frac{12}{32}R\cdot 300\ln(2)=648.35\dots J
$$
- (b) The heat added to the gas
$$
\Delta U=0=W_{on}+Q_{in}=Q_{in}-W_{by}\implies Q_{in}=W_{by}=648.35\dots J
$$
3. Point charges of $−2Q$, $Q$, and $q$ are fixed at $(x, y)$ coordinates $(−a, 0)$, $(a, 0)$, and $(a, 2a)$ respectively. Derive the vector expression for the net electric force on the charge $q$. 
$$
\mathbf{F}=\mathbf{E}q=q\left( -\frac{2Q}{4\pi\varepsilon_{0}(8a^{2})}\begin{pmatrix}
\frac{1}{\sqrt[  ]{ 2 }} \\
\frac{1}{\sqrt[  ]{ 2 }}
\end{pmatrix}+\frac{Q}{4\pi\varepsilon_{0}(4a^{2})}\begin{pmatrix}
0 \\
1
\end{pmatrix} \right)
$$
$$
=\frac{qQ}{16\pi\varepsilon_{0}a^{2}}\left( -\begin{pmatrix}
\frac{1}{\sqrt[  ]{ 2 }} \\
\frac{1}{\sqrt[  ]{ 2 }}
\end{pmatrix}+\begin{pmatrix}
0 \\
1
\end{pmatrix} \right)=\frac{qQ}{16\pi\varepsilon_{0}a^{2}} \begin{pmatrix}
- \frac{1}{\sqrt[  ]{ 2 }} \\
1-\frac{1}{\sqrt[  ]{ 2 }}
\end{pmatrix}
$$
4. Derive an expression for the inductance of a solenoid of length $l$, radius $R$, and having $n$ turns per unit length. (Hint: use Ampere’s law and a sensible integration path to find the $B$-field and hence flux inside the solenoid for a given current. Then use the correct expression from the formula sheet.) 

For the chosen path $C$ we will take the path $l$ inside the solenoid in which $\mathbf{B}$ is constant and then move the path perpendicularly till infinity before looping back to the start so we are left with $Bl$.
$$
\oint \mathbf{B}\, d\mathbf{l}=\mu_{0}I_{encl}=\mu_{0}I\qquad  \oint_{C}\mathbf{B}\, d\mathbf{l} =B \oint_{C} dl=Bl\implies B=\frac{\mu_{0}I}{l}
$$
$$
\Phi_{m}=NBA=nlBA=nl\pi R^{2} \frac{\mu_{0}I}{l}=n\pi R^{2}\mu_{0}I \qquad N\Phi _{m}=LI\implies \Phi_{m}=\frac{LI}{N}=\frac{LI}{nl}=n\pi R^{2}\mu_{0}I
$$
$$
\implies L=n^{2}l\pi R^{2}\mu_{0}
$$
5. Consider the two circuits shown below, where the symbol $A$ represents an ammeter (an instrument to measure the current in a circuit).

![[Pasted image 20250512100609.png]]

- (a) What is the assumption that is generally made for a good ammeter?

Has $0\Omega$ - close circuited

- (b) With switches $S$ open, calculate the readings at the ammeter in the two circuits and explain the comparison between the results.
$$
40 \frac{((15+5)^{-1}+20^{-1})^{-1}}{((15+5)^{-1}+20^{-1})^{-1}+10}=20\qquad V=IR\implies I=\frac{20}{15+5}=1A
$$
$$
40 \frac{(10^{-1}+20^{-1})^{-1}}{(20^{-1}+10^{-1})^{-1}+20}=10\qquad V=IR\implies I=\frac{10}{10}=1A
$$
The 2 currents are equivalent.
- (c) With switches $S$ closed, calculate again the ammeter readings in the two circuits. Why are the currents different with respect to the previous case? Also, in which of these circuits with closed switches is the greatest power dissipated? 
$$
R_{top}=((15+5)^{-1}+20^{-1})^{-1}+10=20\Omega
$$
$$
R_{bot}=(20^{-1}+10^{-1})^{-1}+20=\frac{80}{3}=26.6\dots\Omega
$$
$\therefore$ top circuit has a lower total resistance and by $P=\frac{V^{2}}{R}$ we then know this circuit dissipated the most power as $V$ is constant.
6. 
#### EITHER Part A
- (a) Sketch the approximate form of the potential felt by an atom that is bound to another atom as a function of the interatomic distance. On this sketch, label both $\varepsilon$, the work done to separate the two atoms to infinity, and $r_{0}$, the equilibrium bond length between the two atoms. 

![[em tm ec 2024 2025-05-12 10.30.01.excalidraw]]

- (b) Now, instead sketch the force described by this potential as a function of interatomic distance, indicating where this force is attractive and repulsive, with $r_{0}$ clearly labelled. 

![[em tm ec 2024 2025-05-12 10.32.58.excalidraw]]
- (c) The general form of the Lennard-Jones potential is given by $$V(r)=\frac{A}{r^{12}}-\frac{B}{r^{6}}$$Show that the generalised constants $A$ and $B$ can be related to $\varepsilon$ and $r_{0}$, with $A=\varepsilon r_{0}^{12}$ and B = $2\varepsilon r_{0}^{6}$.
$$
F(r)=-\frac{dV(r)}{dt}=\frac{6B}{r^{7}}-\frac{12A}{r^{13}}\qquad F(r_{0})=\frac{6B}{r_{0}^{7}}-\frac{12A}{r_{0}^{13}}=0\implies B=\frac{2A}{r_{0}^{6}}
$$
$$
V(r)=\frac{A}{r^{12}}-\frac{2A}{r^{6}r_{0}^{6}}\qquad V(r_{0})=\frac{A}{r_{0}^{12}}-\frac{2A}{r_{0}^{12}}=-\frac{A}{r_{0}^{12}}=-\varepsilon\implies A=\varepsilon r_{0}^{12}
$$
$$
\therefore B=\frac{2\varepsilon r_{0}^{12}}{r_{0}^{6}}=2\varepsilon r_{0}^{6}
$$
- (d) A student puts some liquid argon, which has density $ρ$ and surface tension $γ$, into a refrigerated tank with a small tube of radius $r$ protruding vertically out of it. The liquid rises into the tube to a height $h$ and forms a meniscus, with a contact angle $θ$ between surface of the liquid and the wall of the tube. Derive an expression for the height the liquid reaches in the tube. You may assume the liquid undergoes an acceleration due to gravity of $g\,ms ^{-2}$.

![[em tm ec 2024 2025-05-12 10.50.43.excalidraw]]
$$
F_{\gamma}\cos\theta=2\pi r\gamma \cos \theta=mg=V\rho g=\pi r^{2}h\rho g\implies h=\frac{2\gamma \cos\theta}{r\rho g}
$$
#### OR Part B

- (a) State the law of the equipartition of energy.

The energy in a system that is in thermal equilibrium is given by $n\cdot \frac{1}{2}k_{B}T$ where $n$ here is the number of degrees of freedom, or the number of terms with either displacement or velocity terms squared.

- (b) Use this law to predict and justify the molar heat capacity at constant volume, $c_{V}$ , in terms of the gas constant $R$, for
	- (i) a monoatomic gas

This only has 3 translational degrees of freedom 
$$
n=3\therefore c_{V}=\frac{3R}{2}
$$
- 
	- a diatomic gas

This has 3 translational degrees of freedom, 2 rotational and 2 vibrational
$$
n=7 \therefore c_{V}=\frac{7R}{2}
$$
- 
	- a solid comprised of atoms in a lattice
Each atom has 6 bonds, so 12 vibrational degrees, however this is shared so this is then halfed to 6.
$$
n=6\therefore c_{V}=3R
$$
- (c) Oxygen gas ($O_{2}$) and chlorine gas ($Cl_{2}$) are experimentally found to have $c_{V} = 20.7 J K ^{-1}  mol^{-1}$ and $cV = 24.8 J K^{-1} mol^{-1}$ respectively. What is the reason for this difference?

$O_{2}$ does not have enough energy, and has a few degrees of freedom frozen out

- (d) For a set of particles of mass $m$ at a temperature $T$, the distribution of their speeds $v$ is given by the normalised Maxwell-Boltzmann distribution $$P(v)=4\pi\left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}v^{2}\exp\left( \frac{-mv^{2}}{2k_{B}T} \right)$$
	- (i) Show that the most probable speed is $\sqrt[  ]{ \frac{2k_{B}T}{m} }$
$$
\frac{dP(v)}{dv}=4\pi\left( \frac{m}{2\pi k_{B}T} \right)^{\frac{3}{2}}\exp\left( \frac{-mv^{2}}{2k_{B}T} \right)\left( 2v -\frac{mv^{3}}{k_{B}T}\right)
$$
$$
\frac{dP(0)}{dv}\implies2v -\frac{mv^{3}}{k_{B}T}=0\implies v=\sqrt[  ]{ \frac{2k_{B}T}{m} }
$$
- 
	- (ii) Through use of the law of the equipartition of energy, justify that the root-mean square speed is given by $\sqrt[  ]{ \frac{3k_{B}T}{m} }$
$$
n=3\therefore E=\frac{3}{2}k_{B}T=\frac{1}{2}mv^{2}\implies v=\sqrt[  ]{ \frac{3k_{B}T}{m} }
$$
7. 
- (a) An infinite long wire with a uniform charge density, $λ$, along its length is placed along the $z$-axis. By choosing a suitable Gaussian surface, use Gauss’ Law to find an expression for the electric field at a distance $r$ from this wire along the $y$-axis.

Lets find the electric field for a single circle around the wire across $dl$ of the wire
$$
\int ^{}_{S} \mathbf{E}_{circ} \, d\mathbf{S}=\frac{Q_{encl}}{\varepsilon_{0}}=\frac{\lambda dl}{\varepsilon_{0}} \qquad \int ^{}_{S} \mathbf{E}_{circ} \, d\mathbf{S}=E_{circ}\int ^{}_{S}  \, dS=2\pi rE_{circ}  \implies E_{circ}=\frac{\lambda dl}{2\pi \varepsilon_{0}r}
$$
![[em tm ec 2024 2025-05-12 11.30.24.excalidraw]]
Using symmetry we may ignore the vertical ($y$) component:
$$
dE=\frac{\lambda dl}{4\pi\varepsilon_{0}a^{2}}\cos \theta \qquad \tan \theta=\frac{l}{r}\implies dl=r\sec^{2}\theta \,d\theta\qquad \cos \theta=\frac{r}{a}\implies a=r\sec\theta
$$
$$
dE=\frac{\lambda dl}{4\pi\varepsilon_{0}a^{2}}\cos \theta=\frac{\lambda}{4\pi\varepsilon_{0}} \frac{r\sec^{2}\theta}{r^{2}\sec^{2}\theta}\cos \theta\,d\theta\implies E=\frac{\lambda}{4\pi\varepsilon_{0}r}\int ^{\frac{\pi}{2}}_{-\frac{\pi}{2}} \cos \theta \, d\theta =\frac{\lambda}{2\pi\varepsilon_{0}r}
$$
- (b) An infinite number of such infinite long wires, each identical to the one described in part (a), are placed in the $x$-$z$ plane, as shown in the figure below. All the wires are parallel to the $z$-axis and equally spaced so that there are $N$ wires per unit length along the $x$ direction. Use the superposition principle in combination with the result from (a) to derive an expression for the electric field at a point, with distance $d$ from the origin, along the $y$-axis. You may find the following sum useful: $$\sum^{\infty}_{n=-\infty} \frac{a}{a^{2}+n^{2}}=\frac{\pi \coth(\pi a)}{a}$$where a is any constant.

![[em tm ec 2024 2025-05-12 11.45.05.excalidraw]]
$$
x=\frac{n}{N}\qquad dE_{y}=dE_{x}\cos\phi=\frac{\lambda}{2\pi\varepsilon_{0}(x^{2}+d^{2})^{\frac{1}{2}}}\frac{d}{(x^{2}+d^{2})^{\frac{1}{2}}}=\frac{\lambda d}{2\pi\varepsilon_{0}(x^{2}+d^{2})} 
$$
$$
E_{y}= \frac{\lambda d}{2\pi\varepsilon_{0}}  \sum^{\infty}_{n=-\infty} \frac{d}{\left( \left( \frac{n}{N} \right)^{2}+d^{2} \right)}= \frac{\lambda d^{2}N^{2}}{2\pi\varepsilon_{0}}  \sum^{\infty}_{n=-\infty} \frac{1}{ n^{2}+N^{2}d^{2} }= \frac{\lambda d^{2}N^{2}}{2\pi\varepsilon_{0}}\frac{\pi \coth(\pi Nd)}{Nd}$$
$$
=\frac{\lambda Nd }{2\varepsilon_{0}} \coth(\pi d)\qquad d\gg \frac{1}{N}\implies dN\gg 1 \qquad \coth(\pi Nd)=\frac{e^{ \pi Nd }+e^{ -\pi Nd }}{e^{ \pi Nd }-e^{ -\pi Nd }}=\frac{e^{ 2\pi Nd }+1}{e^{ 2\pi Nd }-1}
$$
$$
\lim_{ Nd \to \infty } \coth(\pi Nd)= \lim_{ Nd \to \infty } \frac{e^{ 2\pi Nd }+1}{e^{ 2\pi Nd }-1}=\lim_{ Nd \to \infty } \frac{e^{ 2\pi Nd }}{e^{ 2\pi Nd }}=1
$$
$$
\therefore E_{y}= \frac{\lambda N}{2\varepsilon_{0}}\qquad \lambda N=\sigma \therefore E_{y}=\frac{\sigma}{2\varepsilon_{0}}
$$
#### OR Part B
- (a) A uniform current density, $J$ flows through an infinitely long wire of radius $R$. Use Ampere’s Law to derive expressions (in terms of $J$, $R$, $r$, and any constants) for the magnetic field: 
	- (i) outside the wire at a distance $r>R$

Take radially around the wire and see that $B$ is constant
$$
\oint\mathbf{B} \cdot d\mathbf{l}=B\oint dl=2B\pi r\qquad \oint\mathbf{B}\cdot d\mathbf{l}=\mu_{0}I_{encl}=\mu_{0}I=\mu_{0}J\pi R^{2}\implies B=\frac{\mu_{0}JR^{2}}{2r}
$$
- 
	- (ii) inside the wire at distance $r < R$
$$
\oint\mathbf{B} \cdot d\mathbf{l}=B\oint dl=2B\pi r\qquad \oint\mathbf{B}\cdot d\mathbf{l}=\mu_{0}I_{encl}=\mu_{0}J \frac{r^{2}}{R^{2}}\implies B=\frac{\mu_{0}Jr}{2\pi R^{2}}
$$
- (b) Describe (or make a sketch showing) the direction of the magnetic field outside the wire mentioned in part (a) above. 

![[em tm ec 2024 2025-05-12 14.09.43.excalidraw]]

- (c) The figure below shows the cross-section of an infinitely long conducting cylinder of radius 3a carrying a current density of J in the positive z direction (coming out of the page). Inside the cylinder is an infinitely long cylindrical hole of radius a, which is displaced so that its centre is at a distance a from the centre of the the conducting cylinder (obviously, no current flows inside the hole). Derive a vector expression for the magnitude and direction of the magnetic field inside the hole. (Hint: use the superposition principle and remember the magnetic field is perpendicular to both the current density and radial vector i.e. $\mathbf{B}\propto \mathbf{J \land \mathbf{r}}$.) 
![[{306CE8F0-A5E5-492A-A0AB-A7FB46BF1356}.png]]
Lets find the field due to a full version of the larger cylinder: 
$$
\oint\mathbf{B}\cdot d\mathbf{l}=\mu_{0}I_{encl}=\mu_{0}J \frac{\left|\mathbf{a+\mathbf{r}} \right|^{2}}{9a^{2}}\qquad \oint\mathbf{B\cdot d\mathbf{l}}=B\oint dl=2B\pi \left|\mathbf{a}+\mathbf{r} \right|$$
$$
\implies B_{large}=\frac{\mu_{0}J\left|\mathbf{a+\mathbf{r}}\right|}{18a^{2}\pi}(\mathbf{\hat{a}}+\mathbf{\hat{r}})
$$
Now for the smaller cylinder with a $-J$:
$$
\oint\mathbf{B}\cdot d\mathbf{l}=\mu_{0}I_{encl}=-\mu_{0}J \frac{\left|\mathbf{\mathbf{r}} \right|^{2}}{a^{2}}\qquad \oint\mathbf{B\cdot d\mathbf{l}}=B\oint dl=2B\pi \left|\mathbf{r} \right|\implies B_{small}=-\frac{\mu_{0}Jr}{2a^{2}\pi}
$$
$$
B_{total}=\frac{\mu_{0}J\left|\mathbf{a+\mathbf{r}}\right|}{18a^{2}\pi}-\frac{\mu_{0}Jr}{2a^{2}\pi}=\frac{\mu_{0}J}{2\pi a^{2}}\left( \frac{\left|\mathbf{a}+\mathbf{r}\right|-9r}{9} \right)
$$

#### 8 Part B
![[{27D81C05-F84A-493A-AF8D-3C0EF562060F}.png]]
- (a) Calculate the currents $I_{5}$, $I_{2}$ and $I_{3}$ as indicated in the figure, and specify their direction.

Using superposition with the voltage source we get below as ideal current source and $AB$ are open circuited and all the detached resistors are short circuited:

![[Untitled 2025-05-09 15.56.13.excalidraw]]

Using superposition with the current source we get below as ideal voltage source is close circuited and $AB$ are open circuited and resistor circuit equivalent is series parallel.

![[Untitled 2025-05-09 16.02.35.excalidraw]]
$$
I_{5}=1-1=0\qquad I_{2}=\frac{6}{5}\qquad I_{3}=\frac{4}{5}
$$
$I_{5}$ is 0 so direction does not matter, $I_{2}$ and $I_{3}$ are moving towards the junction

- (b) Calculate the voltage between terminals $A$ and $B$, $V_{AB}=V_{A}-V_{B}$

Let $V_{B}=0$ and then $V_{A}$ is entirely given by superposition of current source as voltage source short circuits $AB$.
$$
V_{A}=IR=2\times \frac{50}{10+5}=\frac{20}{3}=6.66\dots V \therefore V_{AB}=6.66\dots V
$$
$$
R_{Th}=\left( \left( \frac{25}{10}+\frac{6}{5} \right)^{-1}+\frac{15}{50} \right)^{-1}=\frac{370}{211}=1.753\dots R
$$
![[Untitled 2025-05-09 16.27.36.excalidraw]]

- (d) Add a $10 μF$ capacitor between $A$ and $B$, and calculate the time constant of the resulting circuit. What does the time constant represent in the dynamics of the circuit? 

The time constant tells how long it take to change the capacitor to $63\%$ of total.
$$
\tau=RC=1.753\dots \times 10^{-5}s=17.53\dots\mu s
$$
