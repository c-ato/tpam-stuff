Cyclic variables and generalised momenta
Generalised momentum canonical conjugate to $p_{i}\equiv\frac{ \partial \mathcal{L}  }{ \partial \dot{q}_{i} }$

Find conserved quantities where $\dot{p}_{i}=\frac{ \partial \mathcal{L} }{ \partial q_{i} }$

Hamiltonian and Energy Conservation

Hamiltonian is translationally invariant with time.

Hamiltonian is energy if:

$$\mathcal{H}=T+V\iff T= \sum_{ij} h_{ij} \dot{q}_{i}\dot{q}_{j}+\sum_{i}b_{i}q_{I}+c\qquad h_{ij}=\frac{1}{2}m \frac{ \partial r }{ \partial q_{i} } \frac{ \partial r }{ \partial q_{j} } $$
$$b_{i}=m \frac{ \partial r }{ \partial q_{i} } \frac{ \partial r }{ \partial t } \qquad c=m \left( \frac{ \partial r }{ \partial t }  \right)^{2}$$
If $r$ does not depend on $t$ $\implies b_{i}=c=0$

Effective potential - when parts of the kinetic energy act as potential due to constraints and cyclic variables.

Quadrature - solution left in integral form

Centre of mass coordinate
$$\underline{R}_{cm}=\frac{m_{1}\underline{r}_{1}+m_{2}\underline{r}_{2}}{m_{1}+m_{2}}\qquad \underline{r}=\underline{r}_{1}-\underline{r}_{2}$$
$$T=\frac{1}{2}m_{1}\dot{r}_{1}^{2}+\frac{1}{2}m_{2} \dot{r}^{2}_{2}= T=\frac{1}{2}\underbrace{ (m_{1}+m_{2}) }_{ M }\dot{R}^{2}+\frac{1}{2} \underbrace{ \frac{m_{1}m_{2}}{m_{1}+m_{2}} }_{ \mu }\dot{r}^{2}$$
$M$ is total mass, and $\mu$ is the reduced mass.
$$V(\left| \underline{r}_{1}-\underline{r}_{2} \right|)=V(\left| \underline{r} \right|)$$
$$\mathcal{L} =T-V=\frac{1}{2}M\dot{R}^{2}+\frac{1}{2}\mu \dot{r}^{2}-V(r)$$
$R$ is cyclic variable
$$\frac{ \partial \mathcal{L}  }{ \partial \dot{R} } =\underline{P}_{R}=\mu \underline{\dot{R}}$$
$$\mathcal{L} =\frac{\left| \underline{P}_{R} \right|^{2}}{2m}+\frac{1}{2}\mu \dot{r}^{2}-V(r)\qquad \underline{r}=\{ r,\underbrace{ \theta,\phi }_{ cyclic } \} $$
Angular momentum for central force
$$\underline{\dot{L}}=\underline{r}\times \underline{F}=\underline{\tau}\qquad \underline{r}\times \underline{F}\propto \underline{r}\times \underline{r}=\underline{0}$$
$$\mathcal{L} _{rel}=\frac{1}{2}\mu(\dot{r}^{2}+r^{2}\dot{\phi}^{2})-V(r)$$
$$P_{\phi}=\frac{ \partial \mathcal{L}  }{ \partial \dot{\phi} } =\mu r^{2}\dot{\phi}=l=I\dot{\phi}$$