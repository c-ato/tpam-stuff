starting point - Shrodinger's equation $i\hbar \frac{ \partial \underline{\psi}(r,t) }{ \partial t }=\hat{H} \underline{\psi}(r,t)$

SE introduced linearity of solutions, and so can be represented as certain vectors

QM postulate 1 - any QM state is described by a vector in a Hilbert space, specific for any $\hat{H}$

Such a state is denoted by the ket-vector $\ket{\underline{\psi}(t)}$ (related to the wave funct $\underline{\psi}(\underline{r},t)$ which is a projection of $\ket{\underline{\psi}(t)}$ into the real space)

Linear dependence $\{ \ket{\psi_{j}} \} \iff \exists \{ \alpha_{j} \} \,s.t.\, \sum_{j}\alpha_{j}\ket{\underline{\psi}_{j}}=0$

Linear independence $\{ \ket{\psi_{j}} \} \iff \exists \{ \alpha_{j} \} \,s.t.\, \sum_{j}\alpha_{j}\ket{\underline{\psi}_{j}}=0\implies \alpha_{j}=0\forall j$

Bra-vec, $\bra{\underline{\psi}(t)}=\ket{\underline{\psi}(t)}^{*}$, describing the same qm state, so ket correpsonds to $\underline{\psi}(\underline{r},t)$ so bra also corresponds to it

Inner product of $\ket{\psi}$ and $\ket{\phi}$ is then given by $\braket{ \psi | \phi }$. They have lienarity (yk this) and skew-symmetry so $\braket{ \psi | \phi }=\braket{ \phi | \psi }^{*}$ and $\braket{ \psi | \psi }\geq 0$ (follows from skew symmetry). Lead to interesting property of anti-linearity $\braket{ \alpha\psi+\beta\psi | \phi }=\alpha^{*}\braket{ \psi | \phi }+\beta^{*}\braket{ \psi | \phi }$

> [!definition|*]- Hilbert Space
> This is a vector space, associated with $\hat{H}$, where the inner product is defined.
> In the $d$-dimensional $HS$, $\{ \ket{\eta_{n}(t)} \}\equiv \{ \ket{\eta_{1}},\ket{\eta_{2}},\dots,\ket{\eta_{d}} \}=\ket{n}$
> From LI follows that $\braket{ n | m }=\delta _{nm}$
 ^def-qm3-hilbert-spa

Orthonormal - we can span any stat in this HS 

$\ket{\psi}=\sum_{n}\alpha_{n}\ket{n}$
$\bra{\psi}=\sum_{n}\alpha^{*}_{n}\bra{n}$
$\braket{ n | \psi }=\alpha_{n}\braket{ n | m }=a_{n}$

matrix rep in a given basis $\{ \ket{n} \}$, any state $\ket{\psi}$ ca be represented as a matrix column

$$\ket{\psi} \to \{ \braket{ n | \psi }  \}=\{ \alpha_{n} \}=\begin{bmatrix}
\alpha_{1} \\
\alpha_{2} \\
\vdots \\
\alpha_{d}
\end{bmatrix}$$
so $\bra{\psi}=\{ a_{n}^{*} \}$
$$\braket{ \psi | \phi } =\sum \alpha_{n}^{*}\beta_{m}\braket{ n | m } =\sum \alpha_{n}\beta_{n}=\begin{bmatrix}
\alpha_{1}^{*},\alpha_{2}^{*},\dots,\alpha_{d}^{*}
\end{bmatrix}\begin{bmatrix}
\beta_{1} \\
\beta_{2} \\
\vdots \\
\beta_{d}
\end{bmatrix}$$
Normalisation we can define
$$\ket{\tilde{\psi}} =\frac{\ket{\psi} }{\sqrt[  ]{ \braket{ \psi | \psi }  }}\implies \braket{ \tilde{\psi} | \tilde{\psi}} =1$$
