> [!definition|*]- Curl
> $$\underline{F}=(P,Q,R)\qquad\text{curl}(\underline{F})=\underline{\nabla}\times \underline{F}=\left( R_{y}-Q_{z},P_{z}-R_{x},P_{y}-Q_{x}\right) $$
 ^def-mva-curl

> [!theorem|*]- Green's Theorem
> Let $C$ be a closed curve, oriented counterclockwise and enclosing a region $R \in \mathbb{R}^{2}$. If $\underline{F}$ is a vector field defined and differentiable everywhere in $R$, then $$\oint_{C}\underline{F}\cdot d\underline{r}=\iint_{R}\text{curl}(\underline{F})dA$$
 ^thm-mva-green

> [!definition|*]- DIvergence
> $$\underline{F}=(M(x,y),N(x,y))\qquad Div(\underline{F})=\underline{\nabla}\cdot \underline{F}= \frac{ \partial M }{ \partial x } +\frac{ \partial N }{ \partial y } $$
 ^def-mva-div

> [!definition|*]- Flux
> Let $\mathbf{F}:\mathbb{R}^{2}\to \mathbb{R}^{2}$ be a vector field and let $C$ be a planar curve with planar unit normal vector $\hat{n}$. The flux is then defined as the line integral: $$\int ^{}_{C}  \, \mathbf{F}\cdot \hat{n}\,ds $$
 ^def-mva-flux

> [!theorem|*]- Green's Theorem in normal form
> $$\int ^{}_{C}  \, \mathbf{F}\cdot \hat{n}\,ds =\iint_{R} \underline{\nabla}\cdot\mathbf{F}\,dA$$
 ^thm-mva-green-thm-norm
