$\hat{B} =\sum_{nm}\ket{n}B_{nm}\bra{m}$

If $\hat{B}$ is eigen function then easier as $\hat{B}=\sum_{n}b_{n}\ket{b_{n}}\bra{b_{n}}$

Simlest V for $\hat{H}$ is infinte well with sol, where $a$ is the width of the well.
$$\varepsilon_{n}=\frac{\hbar^{2}}{8ma^{2}}n^{2}$$
Hence we can write 
$$\hat{H}=\varepsilon_{n}\ket{n} \bra{n} $$
Two level system - known as qubit, is 
$$\hat{H}-\varepsilon_{0}\ket{0} \bra{0} +\varepsilon_{1}\ket{1} \bra{1} $$
Lets use an opeartor $\hat{\sigma}$ has 2 non-degen EV $\pm 1$ or $\pm \frac{1}{2}\hbar$

$$\hat{\sigma}\ket{\sigma} =\sigma \ket{\sigma} \qquad \sigma=\pm {1} \iff \hat{\sigma}\ket{\pm} =\pm \ket{\pm} $$
$+\equiv \uparrow$ and $- \equiv \downarrow$
$$\hat{S}=\frac{\hbar}{2}\hat{\sigma}\qquad\hat{\sigma}=\sum_{\sigma=\pm 1}\ket{\sigma} \sigma \bra{\sigma} =\ket{ +}\bra{  +} -\ket{ -}\bra{  -} $$
$\{ \braket{ m | \hat{A}|n }  \}$ represent the matrix elements of any $\hat{A}$
$$\underline{\underline{\sigma}}=\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}=\sigma_{z}$$
This is the Pauli matrix.

Lets have arbituary spin state $\ket{\psi}$ then decompose into $A\ket{+}+B\ket{-}$ so that $\braket{ \psi | \psi }=1\implies \left| A \right|^{2}+\left| B \right|^{2}=1$

Choose $A=e^{ i\alpha }\cos \frac{\theta}{2},B-e^{ i\beta }\sin \frac{\theta}{2}$ - spinor property of needing 2 rotations to return back to same value

$\ket{\psi}=\dots \ket{\uparrow}+\dots \ket{\downarrow}$, for $P_{\uparrow}=\left| \braket{ \psi | \uparrow } \right|^{2}=\dots=\cos ^{2} \frac{\theta}{2}$