Orthogonality: $\braket{ n | m }=\delta _nm$

Completeness: $\sum_{n}\ket{n}\bra{n}=\hat{I}$

Operator: $\ket{\psi}\underset{ \hat{A} }{ \to } \ket{\phi} \equiv \hat{A}\ket{\psi}=\ket{\phi}$

Operator is a rule that changes a function/state, linear operators follow linearity properties %%shocker%%. Associative $\hat{A}\hat{B}\ket{\psi}=\hat{A}\ket{\hat{B}\psi}=\hat{A}\ket{\phi}=\ket{\hat{A}\hat{B}\psi}$. Is non-sinuglar if it has an inverse - $\hat{A}\hat{A}^{-1}=\hat{A}^{-1}\hat{A}=\hat{I}$.

Operators do not need to be endomorphic on the HS, thus an automorphism does not need to exist (inverse).
Unitary operatoUnitary operator ￼
￼ has propertyr $\hat{U}$ has property


￼￼P̂
Simplest is $\sum_{n}\ket{n}\bra{n}=\sum_{n}\hat{P}_{n}=\hat{I}$ where $\hat{P}_{n}=\ket{n}\bra{n}$ is the projection operator. $\hat{P}_{n}\ket{\psi}=\ket{n}\braket{ n | \psi }\equiv\psi_{n}\ket{n}$. It projects an arbitary state $\ket{\psi}$ onto $\ket{n}$. Ket and bra is an operator itself.

$(\ket{\psi}\bra{\phi})\ket{n}=\braket{ Q | n }\ket{\psi}$

$\ket{Q}\bra{Q}$ is als a projector of $\ket{\psi}$ onto $Q$: $\ket{Q}\braket{ Q | \psi }=\psi_{Q}\ket{\phi}$

$\ket{\psi}\braket{ \phi}\neq \ket{\phi}\bra{\psi}$.

Operator can be specified on a basis: $\hat{A}\ket{n}=\ket{\hat{A}n}=\sum_{m}\alpha_{mn}\ket{m}$.
Take $\braket{ \ell |\hat{A} | n }=\sum_{m}\alpha_{nm}\braket{ \ell | m }=\alpha_{nm}\delta_{\ell m}=\alpha_{\ell n}$

$a_{mn}=\braket{ m|\hat{A} | n }=\braket{ m | \hat{A}n }$

Note: $\braket{ m | \hat{A}n }\neq \braket{ m\hat{A} | n }$

Dirac basis independent representation.
$$\hat{A}t=\hat{I}\hat{A}\hat{I}=\sum_{n}\ket{n} \bra{n} \hat{A}\sum_{m}\ket{m} \bra{m}=\sum_{nm}\ket{n} \braket{ n | \hat{A}m } \braket{ m}=\sum_{nm}\ket{n} \alpha_{nm}\bra{m}  $$
Basis independent as all we need is any complete or orthonormal basis.

Lets assume we know eigen value equation for $\hat{A}$: $\hat{A}\ket{a_{n}}=a_{n}\ket{a_{n}}$ where $\{ \ket{a_{n}} \}$ is a set of eigenstates of $\hat{A}$.

$\hat{A}=\sum_{nm}\ket{a_{n}}\alpha_{nm}\bra{a_{m}}$ where $a_{nm}=\braket{ a_{n} |\hat{A} | a_{m} }=a_{m}\delta_{nm}$

Hence $\hat{A}=\sum_{nm}\ket{a_{n}a_{m}\delta _{nm}}\braket{ a_{n}}=\sum_{n}\ket{a_{n}}a_{n}\bra{a_{n}}$
$\{ \underline{\underline{A}} \}=diag(a_{n})$ mat rep of A in its own basis

In arbitrary basis 
$$\{ \underline{\underline{A}} \}=\{ \alpha_{nm} \}=\begin{bmatrix}
\alpha_{11} & \dots &  \\
\vdots
\end{bmatrix}$$
Hermiticity if $\hat{B} =\ket{\eta}\bra{\phi}$ and $\hat{A}=\ket{\phi}\bra{\eta}$, totally dif.

$\hat{B}$ hermitian conjugate donated as $\hat{B}^{\dagger}$ and defined by $\bra{\psi}\hat{B}^{\dagger}=\ket{\psi \hat{B}}$

Allows for $\braket{ \psi |\hat{B} | \phi }$ to be unambigious on acting on either side

QMP2

Qm observale is represented by a hermitian operator and its eugenvalues are only measrable for this observation

Unitary operator $\hat{U}$ has property


QMP3 - A measuremnt if $\hat{A}$ in state $\ket{\psi}$ returns one ofgt he eigen values of $\hat{A}$, $A_{n}$ with protbailityu $P_{n}=\left| \braket{ \psi|A_{n}\psi |  } \right|^{2}$

After measurement, $\ket{\psi}$ collapses to $\ket{A_{n}}$