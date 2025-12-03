[[Assessed Problem Sheet 8.pdf]]

Consider a system consisting of 5 distinguishable molecules (that could mean that each of them is pinned to a specific location). Each molecule has a spin $1/2$ and a permanent magnetic moment $\mathbf{\mu}$. The magnetic moment can therefore take only two orientations: $\uparrow$ or $\downarrow$. In the presence of a (vertical) external magnetic field $\mathbf{H}$, the magnetic energy of a molecule is $\mathbf{\mu}\cdot \mathbf{B}$, where $\mathbf{B}=\mu_{0}\mathbf{H}$ so that the energy for the orientation $\uparrow$ of the magnetic moment is $-\mu B$. We neglect other types of energies such as the kinetic and interaction energies (either interaction between the magnetic dipoles or by other means), and the molecules are isolated from their surroundings.

(i) Give an expression for and calculate the statistical weight of the macrostate that has fixed total magnetic energy $U_{tot}=-\mu B$. [2]

3 $\uparrow$ and 2 $\downarrow$ so $\Omega=^{5}C_{3}=10$

(ii) We replace the first molecule with a molecule having a magnetic moment of magnitude $\mu'=3\mu$ (but still with spin $1/2$), which maybe denoted $\Uparrow$ or $\Downarrow$. The new system consists of one molecule with magnetic moment $3μ$ and four molecules each with moment $μ$. Calculate the statistical weight of the macrostate that has fixed total magnetic energy $U_{tot}=-\mu B$. You will either give an expression for it or list all the accessible microstate(s). [2]

Only 5 microstates: $^{4}C_{0}=1$ from $\Downarrow\uparrow\uparrow\uparrow\uparrow$ and $^{4}C_{1}=4$ from $\Uparrow\uparrow\downarrow\downarrow\downarrow$

(iii) Similar to part 2, but the new molecule has a magnetic moment $\mu'=5\mu$, denoting this as $⤊$ or $⤋$. List the accessible microstate(s). [1

Only 1 microstate: $⤊\downarrow\downarrow\downarrow\downarrow$

Now, consider two systems made of distinguishable molecules. System $A$ has five molecules with one of them having magnetic moment $\mu'=5\mu$ and the remaining having $\mu$ each; system $B$ has five molecules each with magnetic moment $\mu$. Initially, the systems are prepared to have the total energy $-\mu B$ each. We then bring the two systems, which are otherwise isolated, into thermal contact so that energy can be exchanged, but not molecules.

(iv) Calculate the number of microstates for the thermalised system $A+B$. [1]

Combined system has $-2\mu B$ so we have $⤊\downarrow\downarrow\downarrow\downarrow\downarrow\downarrow\uparrow\uparrow\uparrow$ with $^{9}C_{6}$ and $⤋\uparrow\uparrow\uparrow\uparrow\uparrow\uparrow\uparrow\uparrow\downarrow$ with $^{9}C_{8}=9$ so total $\Omega=93$

(v) Find in which direction heat flows between $A$ and $B$ during thermalisation. [4] Hint: you can find the possible configurations of $A$ (or $B$) and calculate the mean energy of $A$ (or $B$) after thermalisation.

corresponding A and B configs and total combinations
$⤊\downarrow\downarrow\downarrow\downarrow$ and $\uparrow\uparrow\uparrow\downarrow\downarrow$ $^{4}C_{0}\times^{5}C_{3}=10$. $A$ state with $-\mu B$ and is initial. $B$ state with $-\mu B$ and is initial.
$⤊\uparrow\downarrow\downarrow\downarrow$ and $\uparrow\uparrow\downarrow\downarrow\downarrow$ $^{4}C_{1}\times^{5}C_{2}=40$. $A$ state with $-3\mu B$. $B$ state with $+\mu B$.
$⤊\uparrow\uparrow\downarrow\downarrow$ and $\uparrow\downarrow\downarrow\downarrow\downarrow$ $^{4}C_{2}\times^{5}C_{1}=30$. $A$ state with $-5\mu B$. $B$ state with $+3\mu B$.
$⤊\uparrow\uparrow\uparrow\downarrow$ and $\downarrow\downarrow\downarrow\downarrow\downarrow$ $^{4}C_{3}\times^{5}C_{0}=4$. $A$ state with $-7\mu B$. $B$ state with $+5\mu B$.
$⤊\uparrow\uparrow\uparrow\uparrow$ this configuration is not possible as we do not have enough down spin in system $B$. A state with $-9\mu B$ 

$⤋\downarrow\downarrow\downarrow\downarrow$ this configuration is not possible as we do not have enough up spin in system $B$. $A$ state with $+9\mu B$
$⤋\uparrow\downarrow\downarrow\downarrow$ this configuration is not possible as we do not have enough up spin in system $B$. $A$ state with $+7\mu B$
$⤋\uparrow\uparrow\downarrow\downarrow$ this configuration is not possible as we do not have enough up spin in system $B$. $A$ state with $+5\mu B$
$⤋\uparrow\uparrow\uparrow\downarrow$ and $\uparrow\uparrow\uparrow\uparrow\uparrow$ $^{4}C_{3}\times^{5}C_{0}=4$. $A$ state with $+3\mu B$. $B$ state with $-5\mu B$.
$⤋\uparrow\uparrow\uparrow\uparrow$ and $\uparrow\uparrow\uparrow\uparrow\downarrow$ $^{4}C_{4}\times^{5}C_{1}=5$. $A$ state with $+\mu B$. $B$ state with $-3\mu B$.

$\left< U_{A}^{final} \right> = \mu B\left( \frac{10(-1)+40(-3)+30(-5)+4(-7)+4(+3)+5(+1)}{10+40+30+4+4+5} \right)=- \frac{97}{31}\mu B$
$\Delta U_{A}=-\frac{97}{31}\mu B-(-\mu B)=- \frac{66}{31}\mu B$

Energy moves away from $A$ to $B$

Check:
$\left< U_{B}^{final} \right> = \mu B\left( \frac{10(-1)+40(+1)+30(+3)+4(+5)+4(-5)+5(-3)}{10+40+30+4+4+5} \right)=\frac{35}{31}\mu B$
$$\Delta U_{B}=\frac{35}{31}\mu B-(-\mu B)= \frac{66}{31}\mu B$$
$\left| \Delta U_{A} \right|=\left| \Delta U_{B} \right|$ looks good

