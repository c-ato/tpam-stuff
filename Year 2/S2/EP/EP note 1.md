Dimensional eradication:

Removal of asymptotic behaviour 

Power series, reform equations and manipulate dummy variables to obtain same powers and compare coefficients and then obtain recursion relation, then can use back in power series

Pochhammer symbol $(C)_{n}=C(C+1)\dots(C+n-1)$

Confluent hypergeometric function???

Choosing initial recursion coefficient can control whether just even or odd

The power series is only useful when can terminate so is a finite polynomial based on a choice of $\varepsilon$ depending on the odd and even function

Hermite polynomials 

$$\phi_{n}(y)=\sum^{n}_{k=0}a_{k}y^{k}\qquad \frac{a_{k}}{a_{k+2}}=\frac{(k+1)(k+2)}{2(k-n)}$$
Require $\varepsilon=2n+1\to \phi(y)$ of polynomial of order $n$, and energy levels are quanntised: $E_{n}=\left( n+\frac{1}{2} \right)\hbar\omega$ where $n \in \mathbb{N}/\{ 0 \}$

Rodrigues Formula
$$H_{n}(y)=(-1)^{n}e^{ y^{2} } \frac{d^{n}}{dy^{n}}\left[ e^{ -y^{2} } \right] $$
Orthogonality of Rodrigues Formula $(m>n)$
$$\int_{-\infty}^{\infty} H_{m}(y)H_{n}(y)e^{ -y^{2} } \, dy=2^{n}n!\sqrt[  ]{ \pi } \delta_{mn} $$
$$(-1)^{n}\int_{-\infty}^{\infty} H_{m}(y) \frac{d^{n}}{dy^{n}}(e^{ -y^{2} }) \, dy =(-1)^{n}\left\{ \left[ H_{m}(y) \frac{d^{n-1}}{dy^{n-1}}(e^{ ^{-y^{2}} }) \right] ^{\infty}_{-\infty}-\int_{-\infty}^{\infty} H_{m}(y) \frac{d^{n-1}}{dy^{n-1}}(e^{ -y^{2} }) \right\}$$
$$=(-1)^{n-1}\int_{-\infty}^{\infty} H_{m}(y) \frac{d^{n-1}}{dy^{n-1}}(e^{ -y^{2} })$$
So inductive:
$$\int_{-\infty}^{\infty}  \frac{d^{n}H_{m}}{dy^{n}}e^{ -y^{2} } \, dy=0 $$
If $m=n$
$\frac{d^{n}H_{n}}{dy^{n}}=\frac{d^{n}}{dy^{n}} 2^{n}y^{n}=2^{n}n!$
$$\implies 2^{n}n!\int_{-\infty}^{\infty} e^{ -y^{2} } \, dy =2^{n}n!\sqrt[  ]{ \pi }$$
SO solution of quantum SHO ad $E_{n}=\left( n+\frac{1}{2} \right)\hbar\omega$ and 
$$\psi_{n}(x)=\frac{1}{\sqrt[  ]{ 2^{n}n!\sqrt[  ]{ \pi \ell } }}H_{n}\left( \frac{x}{\ell} \right)e^{ -\frac{x^{2}}{2\ell^{2}} }$$
Leibnitz theorem: pascal triangle but order of derivative rather than power
where $y=uv$ then 
$$y^{(n)}= \sum^{n}_{k=0}\begin{pmatrix}n \\ k\end{pmatrix}u^{(n-k)}v^{(k)}$$
