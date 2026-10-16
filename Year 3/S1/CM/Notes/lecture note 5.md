$\mathbf{x}=x_{k}i_{k}=x'_{m}i'_{m}=\mathbf{x}'$
Applies where by covariance principle (conserved metric)

$x_{k}i_{k}i_{p}=x'_{m}i'_{m}i_{p}$
$x_{p}=x'_{m}i'_{m}i_{p}$
$x_{p}=x'_{m}l_{mp}$
$$\mathbf{x}'=\begin{pmatrix}
x_{1}' \\
x_{2}' \\
x_{3}'
\end{pmatrix}=\begin{pmatrix}
l_{11} & l_{12} & l_{13} \\
l_{21} & l_{22} & l_{23} \\
l_{31} & l_{32} & l_{33}
\end{pmatrix}\begin{pmatrix}
x_{1} \\
x_{2} \\
x_{3}
\end{pmatrix}=L\mathbf{x}$$
Equally
$\mathbf{x}=L\mathbf{x}'$ and $LL^{T}=I\therefore L$ is an orthogonal transformation, or that $l_{pk}l_{mk}=\delta_{pm}=l_{kp}l_{km}=\delta$

> [!definition|*]- First Order Cartesian Tensors
> $$x'_{p}=l_{pk}x_{k}$$
 ^def-cm-1st-ord-cart-tens

> [!definition|*]- Second Order Cartesian Tensors
> $$a'_{mn}=l_{mi}l_{nj}a_{ij}$$
 ^def-cm-1st-ord-cart-tens

Multiplying 2 matrixes is called an outerproduct (direct product $\otimes$)
$a_{ijk}b_{lm} = c_{ijklm}$
If two indices are equal in the outer product we can obtain tensors two orders lower.
$a_{isk}b_{jk}=c_{isj}$
An example is vectors to scalar (inner prod)

If $a_{ij}=a_{ji}$ then symmetric. If $a_{ij}=-a_{ji}$ then symmetric.