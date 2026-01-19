second law of thermodynamics builds on head flows spontaneously from hot to cold - signifies reversibility and irreversibility and fundamental limitations of appliances

Entropy emergences from 2nd LoT

Shorthand - discard adiabatic as net $0$

![[SP&E note 3 2025-10-17 16.18.01.excalidraw]]

Cannot perfectly convert heat into work in a cyclic process

Heat goes from hot to cold

![[SP&E note 3 2025-10-20 09.33.48.excalidraw]]

![[SP&E note 3 2025-10-20 09.34.06.excalidraw]]
$\eta=\frac{W}{Q_{1}}=1- \frac{Q_{2}}{Q_{1}}=1- \frac{T_{2}}{T_{1}}$ there is max efficiency

![[SP&E note 3 2025-10-24 16.23.30.excalidraw]]

Entropy: another function of state - derived from first law

> [!theorem|*]- Clausius' Theorem
> $\eta^{\mathrm{Rev}}\geq \eta\implies \frac{T_{2}}{T_{1}}=\frac{Q_{2}^\mathrm{Rev}}{Q_{1}^\mathrm{Rev}}\leq \frac{Q_{2}}{Q_{1}}\implies \frac{Q_{1}}{T_{1}}\leq \frac{Q_{2}}{T_{2}}\implies \frac{Q_{1}}{T_{2}}-\frac{Q_{2}}{T_{2}}=\frac{Q_{1}}{T_{2}}+\frac{\tilde{Q}_{2}}{T_{2}}=\sum_{stage} \frac{Q}{T}\leq0$
 ^thm-

$\Gamma$ is reservoir at $T_{0}$. $\gamma'$ as an intermediate body that undergoes a carnot to the body $\gamma$ acting as another "reservoir". $C_{\Gamma}\gg C_{\gamma'}\gg C_{\gamma}$ allowing $\gamma$ to be irreversible with lack of equilirbrium but has $\gamma'$ deposit heat be well defined 

Work may be done on both $\gamma'$ and $\gamma$, $dW',dW$ respectively 

![[SP&E note 3 2025-10-27 09.19.11.excalidraw]]

$q$ or $\oint q>0\implies \oint W= \oint (W+W')>0$

$\int ^{B}_{A} \frac{dQ}{T}=S_{B}-S_{A}$ where $S$, the total differential, is the entropy

For reversible we obtain $\oint q=T_{0}\oint \frac{dQ}{T}=0\implies$ path independence, so depends on endpoints $dU=dQ+dW_{in}=TdS-pdV$

For irreversible $\oint \frac{dQ}{T}<0\implies \int ^{B}_{A} \frac{dQ}{T_{ext}}<S_{B}-S_{A}$

$$dU=TdS-pdV+\sum_{i}Y_{i}dX$$

Extensive variables (proportional to the size of the system): $V$, $S$, $N$

Internal energy is unique (as a potential) as it has all extensive variables.

$$\frac{ \partial U }{ \partial S }=T \frac{ \partial U }{ \partial V }\qquad-p=\frac{ \partial U }{ \partial V } \qquad Y_{j}= \frac{ \partial U }{ \partial X_{j} }   $$
there variables are independent of size

"2 equations of state" are $p(S,V,N)= -\frac{ \partial U }{ \partial V }$ and $T(S,V,N)=\frac{ \partial U }{ \partial \sqrt{ x } }$, not a function of state

To obtain "THE function of state" we want to eliminate $S$, that is, solving for $S(V,U,N)$ from one of these equations and substitute into the other

May not want to use $S$, $V$, $N$, other choices are enthalpy, $H$, where $H=U+pV$.

Legendre transformation changes variables $(S,V,N)\to (S,p,N)$

$$dH=dU+pdV+Vdp=TdS+Vdp\implies H(S,p)$$
$$T=\frac{ \partial H }{ \partial S } \qquad V= \frac{ \partial H }{ \partial p } $$
Helmholte free energy: $F=U-TS\implies dF=-SdT-pdV$ so $\frac{ \partial F }{ \partial T }=-S$ and $\frac{ \partial F }{ \partial V }=-p$, $F(T,V,N)$

Gibbs free energy
$$G=U+pV-TS=H-TS\implies dG=-SdT+Vdp\implies G(T,P,N)\quad \frac{ \partial G }{ \partial T } =-S\qquad \frac{ \partial G }{ \partial p } =V$$

"free energy" is 
$$dF=dU-TdS-SdT=dQ-dW_{by}-TdS\leq TdS-pdV-TdS=-dW_{by}$$
$$\implies \left| dF \right|\leq dW_{by}$$ some energy is bounded by work and can be obtained from the system

$$\underline{\underline{A}}$$
