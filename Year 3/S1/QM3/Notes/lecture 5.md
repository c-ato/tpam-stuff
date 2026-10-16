For continuous description we can replace classical variables, position operator:
$$\hat{x}\ket{x} =x\ket{x} $$
Othogonality
$$\hat{I}=\int_{-\infty}^{\infty} \ket{x} \bra{x}  \, dx\qquad \text{and}\qquad \braket{ x | x' } =\delta(x-x') $$
Projecting $\psi$ onto real axis gives wf
$$\ket{\psi} =\braket{ x | \psi } $$
Skew symmetry we get $\braket{ \psi | x }=\psi^{*}(x)$
$$\braket{ x'|\hat{x} | x }=\braket{ x' | x }=\delta(x'-x)$$
So for some $V$ we can have
$$\braket{ x'|V(x) | x } =V(x)\delta( x'-x)$$
Also applicable
$$\braket{ x|V(x) | y } =\braket{ x | V(x) |x } \delta( x-y)$$
Consider a general 
$$\braket{ \psi | \hat{V} |\phi}=\braket{ \psi | \hat{I}\hat{V}\hat{I} |\phi }=\braket{ \psi | \int ^{}_{}  \, dx \braket{ x | x } \hat{V}\int ^{}_{}  \, dy \braket{ y | y } |\phi }   $$
$$=dxdy\braket{ \psi | x } \braket{ x|\hat{V} | y } \braket{ y | \phi }=\int ^{}_{}  \, dx \psi^{*}(x)\hat{V}(x)\phi(x)$$
Equivalent matrix element from discrete for continuous.

wf is projection of state $\ket{\Psi}$ onto $x$
$$\Psi(x)=\braket{ x | \Psi } $$
Probability of an eigenstate is given by $P_{n}=\left| \braket{ A_{n} | \psi } \right|^{2}$. For continuous we get $p(x)=0$ for any singular point so we have to find $p(a\leq x\leq b)=P$ for an interval so $p_{dx}=\left| \braket{ x | \psi } \right|^{2}dx$.

THe previous $\left| \braket{ x| \psi } \right|^{2}=\psi(x)^{2}$ then gives probability density.

Momentum operator is then given by 
$$\hat{p}\psi(x)=\braket{ x| \hat{p} | \psi } =\int_{-\infty}^{\infty}  \, dy \braket{ x | \hat{p} | y}\psi(y) $$