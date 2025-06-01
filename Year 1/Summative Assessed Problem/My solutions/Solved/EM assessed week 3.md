[[Year 1 Assessed Problems 3.pdf]]

\section{The figure shows, in cross-section, portions of two infinitely large, parallel, non-conducting sheets, each with a uniform charge distribution. The charge density for the sheet on the left is $+3\sigma$ and that for the sheet on the right is $-\sigma$. Find the magnitude and direction of the total electric field $\mathbf{\underline{E}}$ in terms of $\sigma$:}

\subsection{To the left of both sheets.}

$$
E_{LP}=\frac{3\sigma}{2\varepsilon_{0}}\qquad E_{RP}=- \frac{\sigma}{2\varepsilon_{0}}
$$
$$
E_{LP}+E_{RP}= \frac{\sigma}{\varepsilon_{0}}\text{ to the left}
$$
\subsection{Between the sheets.}
$$
E_{LP}-E_{RP}= \frac{2\sigma}{\varepsilon_{0}}\text{ to the left}
$$
\subsection{To the right of both sheets.}
$$
E_{LP}+E_{RP}= \frac{\sigma}{\varepsilon_{0}}\text{ to the right}
$$
\section{A sphere $S_{1}$ of radius $R_{1}$ contains charge with a uniform density $\rho$. A spherical cavity $S_{2}$ of radius $R_{2}$ is cut out of the sphere. The centres of the spheres are separated by a vector distance $a$, with $R_{2} + a < R_{1}$. Derive an expression for the electric field $E$ as a function of $a$ and $\rho$ in a generic location inside the spherical cavity. (Hint: Use the superposition principle to replace this sphere by two objects which are equivalent and keep everything in vector form.)}

Let $\underline{r}$ be some arbitrary point in the spherical cavity s.t. it is a position vector from the centre of $S_{2}\,(\underline{a})$. 

We are given that a sphere can act as a point charge from its centre. $S_{2}$ has density of $-\rho$ superimposing on the sphere $S_{1}$ with density $\rho$, we may use:
$$
Q=V\rho=\frac{4}{3}\pi R^{3}\rho
$$
Note that :
$$
\hat{\underline{x}}=\frac{\underline{x}}{|x|} \iff |x|\hat{\underline{x}}=\underline{x}
$$
$$
\mathbf{\underline{E}}_{S_{1}}= \frac{Q_{S_{1}}|\underline{r}+\underline{a}|}{4\pi\varepsilon_{0}R_{1}^{3}}\hat{\underline{(r+a)}}=\frac{\rho}{3\varepsilon_{0}}(\underline{r}+\underline{a})\qquad \mathbf{\underline{E}}_{S_{2}}=\frac{Q_{S_{2}}|\underline{r}|}{4\pi\varepsilon_{0}R_{2}^{3}}\hat{\underline{r}}= - \frac{\rho}{3\varepsilon_{0}}\underline{r}
$$
$$
\mathbf{\underline{E}}_{T}=\mathbf{\underline{E}}_{S_{1}}+\mathbf{\underline{E}}_{S_{2}}=\frac{\rho}{3\varepsilon_{0}} \underline{a}
$$

