paramagnets, $\mu$ us magnetic moment and $B$ is an external field where $\underline{B}=B \underline{\hat{z}}$
$$U=-\mu B$$

$$N!\sim \left( \frac{N}{e} \right)^{N}$$
$$S\left( n=\frac{N}{2} \right)=k_{B}N\ln 2$$
Heat exchange and thermalisation: $S_{A+B}=S_{A}+S_{B}$

Temperature: $U$ and $S$ from a microscopic view, We want a maximum $S_{AB}$ under moving charge so look for $\frac{ \partial S_{AB} }{ \partial U_{A} }=0$, in otherwords varying $U_{A}(=E_{A})$ and that $U=U_{A}+U_{B}$

This means that $U_{B}$ is not independent as $U$ is fixed for each macrostate
$S(U,U_{A})=k_{0}\ln(\Omega_{A}\Omega _{B}=S_{A}(U_{A})+S_{B}(U_{B})$
Then we want to maximise $S(U,U_{A})$ wrt $U_{A}$ 
$$\frac{ \partial S_{AB} }{ \partial U_{A} }=\frac{ \partial S_{A} }{ \partial U_{A} } +\frac{ \partial U_{B} }{ \partial U_{A} } \frac{ \partial S_{B} }{ \partial U_{B} }=\frac{ \partial S_{A} }{ \partial U_{A} }-\frac{ \partial S_{B} }{ \partial U_{B} } =0   \qquad \frac{ \partial U_{B} }{ \partial U_{A} } =\frac{ \partial  }{ \partial U_{A} } (U-U_{A})=-1$$
so $\frac{ \partial S_{A} }{ \partial U_{A} }=\frac{ \partial S_{B} }{ \partial U_{B} }$ or that the properties of $A\equiv B$

$$S_{eq}(U,U_{A})=k_{B}\ln\left( \sum \Omega_{A}\Omega_{B} \right)\gg S_{i}$$
2 isothermal systems $A$ and $B$ with adiabatic wall between and generally the energy specific energy level state of $A$ is given by $E^{A}_{n}$ and for a specific energy level and a signular specific state is $E_{i}^{A}$. We assume for this system that $E=C_{B}\Delta T_{B}$ such that $\frac{\Delta T_{B}}{T_{B}}\ll 1$ so that $C_{B}$ is so large to preserve $T$.

We have statistical weight of the combined system is given by $\Omega(U_{0}-E^{A}_{i})=\Omega(E^{B})$

Assume that $B$ is not affected by presence except in terms of energy conservation.

We will have that $U_{0}\approx C_{B}T\gg E^{A}_{i}$ so this suggests an taylor expansion of $\Omega$
$$S_{B}(U_{0}-E^{A}_{i})\approx S_{B}(U_{0})- E_{i}^{A}\underbrace{ \left( \frac{ \partial S_{B} }{ \partial U_{B} }  \right) }_{ \frac{1}{T} }\implies \Omega(U_{0}-E^{A}_{i})\approx \exp \left[ \frac{S_{B}}{k_{B}} -\frac{E_{i}^{A}}{k_{B}T}\right]$$
$$\implies p_{i}=  \exp \left[ -\frac{E_{i}}{k_{B}T} \right] $$
Normalise we have partition function $Z$.
$$Z=\sum_{i}\exp \left[ -\beta E_{i}^{A}\right]=\sum_{n}g_{n}\exp \left[ -\beta E_{n} \right]  $$
$$\implies p(E_{n})=g_{n}p_{i}$$