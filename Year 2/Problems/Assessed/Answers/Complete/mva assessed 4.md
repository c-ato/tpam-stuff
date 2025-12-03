[[2MVA_Level_I_Assessed_Sheet_4.pdf]]

Question 1: Let $V$ be the volume given by $0 ≤ x ≤ 1$, $0 ≤ y ≤ 1$ and $0 ≤ z ≤ 1$. Consider the vector field $\mathbf{F}$ in $\mathbb{R}^{3}$ given by $F = (4xz, −y^{2}, yz)$. Calculate $\iiint_{V}\nabla\cdot \mathbf{F}dV$ .
$$\iiint\nabla\cdot \mathbf{F}dV=\iiint_{V}4z-2y+y\,dV=\int ^{1}_{0}  \, dx \int ^{1}_{0}  \, dy \int ^{1}_{0}  \, dz (4z-y)$$
$$=\int ^{1}_{0}  \, dx \int ^{1}_{0}  \, dy \int ^{1}_{0}  \, dz\,4z-\int ^{1}_{0}  \, dx \int ^{1}_{0}  \, dy \int ^{1}_{0}  \, dz\,(-y)= 2-\frac{1}{2}=\frac{3}{2}$$
Question 2: Let $S$ be the surface along $z=x^{2}+y^{2}$ which lies below the plane $2x+2y+z=2$. Let $C$ be the bounding curve of $S$ which is traversed in the counter clockwise direction when looking from above. Consider the vector field $\mathbf{F}$ in $\mathbb{R}^{3}$ given by $F = (x + y, −y, 1)$. Calculate $\oint_{C}\mathbf{F}\cdot d\mathbf{r}$.
$$x^{2}+y^{2}=z=2-2x-2y \iff x^{2}+2x+1+y^{2}+2y+1=2+1+1\impliedby (x+1)^{2}+(y+1)^{2}=2^{2}$$
Choose another cartesian coordinate: $X=x+1$ and $Y=y+1$ $\implies C:X^{2}+Y^{2}=2^{2}$ and we redefined $\mathbf{F}=(X+Y-2,1-Y,1)$ and we have $dX=dx$ and $dY=dy$ so $\nabla=\frac{ \partial  }{ \partial X }\mathbf{i}+\frac{ \partial  }{ \partial Y }\mathbf{j}+\frac{ \partial  }{ \partial z }\mathbf{k}$. By inspection the $\hat{n}=\mathbf{k}$ as this is a plane in only $\mathbf{i}$ and $\mathbf{j}$.
$$\oint_{C}\mathbf{F}\cdot d\mathbf{r}=\iint_{R}\underline{\nabla}\times \mathbf{F}\cdot \hat{n}\,dA=\iint_{R}1\mathbf{k}\cdot \hat{n}\,dA\implies \int ^{2\pi}_{0}  \, d\theta \int ^{2}_{0}  \, dr\,r  =4\pi$$
Question 3: Let $S$ be the surface of a Torus which is parameterized by the position vector $\mathbf{r}(u, v)$ given by $$\mathbf{r}(u, v) = (\cos(u)(R + r \cos(v)), \sin(u)(R + r \cos(v)), r \sin(v))$$for $0 ≤ u ≤ 2π, 0 ≤ v ≤ 2π$
	(a) Calculate the vectors $\frac{ \partial \mathbf{r} }{ \partial u }=\left( \frac{ \partial x }{ \partial u },\frac{ \partial y }{ \partial u },\frac{ \partial z }{ \partial u } \right)$ and $\frac{ \partial \mathbf{r} }{ \partial v }=\left( \frac{ \partial x }{ \partial v },\frac{ \partial y }{ \partial v },\frac{ \partial z }{ \partial v } \right)$.
$$\frac{ \partial \mathbf{r} }{ \partial u } =\left( \frac{ \partial  }{ \partial u } (\cos(u)(R + r \cos(v))), \frac{ \partial  }{ \partial u }(\sin(u)(R + r \cos(v))), \frac{ \partial  }{ \partial u }(r \sin(v))
\right)$$
$$\frac{ \partial \mathbf{r} }{ \partial u } =(-\sin(u)(R+r\cos(v)),\cos(u)(R+r\cos(v)),0)$$
$$\frac{ \partial \mathbf{r} }{ \partial v } =\left( \frac{ \partial  }{ \partial v } (\cos(u)(R + r \cos(v))), \frac{ \partial  }{ \partial v }(\sin(u)(R + r \cos(v))), \frac{ \partial  }{ \partial v }(r \sin(v))
\right)$$
$$\frac{ \partial \mathbf{r} }{ \partial v }= (-r\sin(v)\cos(u)),-r\sin(v)\sin(u)),r\cos(v))$$
	(b) Now calculate the differential surface area element $dS =  \left| \frac{∂\mathbf{r}}{∂u} × \frac{ \partial \mathbf{r} }{ \partial v } \right| dudv$.
$$\frac{∂\mathbf{r}}{\partial u} × \frac{ \partial \mathbf{r} }{ \partial v } =\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
-\sin(u)(R+r\cos(v) & \cos(u)(R+r\cos(v)) & 0 \\
-r\sin(v)\cos(u)) & -r\sin(v)\sin(u) & r\cos(v)
\end{vmatrix}$$
$$=r\cos(v)\cos(u)(R+r\cos(v))\mathbf{i}+r\cos(v)\sin(u)(R+r\cos(v))\mathbf{j}+$$
$$(r\sin ^{2}(u)\sin(v)(R+r\cos(v))+r\sin(v)\cos ^{2}(u)(R+r\cos(v)))\mathbf{k}$$
$$=r(R+r\cos(v))(\cos(v)\cos(u)\mathbf{i}+\cos(v)\sin(u)\mathbf{j}+(\sin ^{2}(u)\sin(v)+\sin(v)\cos ^{2}(u))\mathbf{k})$$
$$\left| \frac{∂\mathbf{r}}{\partial u} × \frac{ \partial \mathbf{r} }{ \partial v } \right|^{2}=r^{2}(R+r\cos(v))^{2}(\cos ^{2}(v)\cos ^{2}(u)+\cos ^{2}(v)\sin ^{2}(u)$$
$$+(\sin ^{2}(u)\sin(v)+\sin(v)\cos ^{2}(u))^{2})$$
$$=r^{2}(R+r\cos(v))^{2}(\cos ^{2}(v)+\sin ^{4}(u)\sin ^{2}(v)+\sin ^{2}(u)\cos ^{2}(u)\sin ^{2}(v)$$
$$+\sin ^{2}(u)\cos ^{2}(u)\sin ^{2}(v)+\sin ^{2}(v)\cos ^{4}(u))$$
$$=r^{2}(R+r\cos(v))^{2}(\cos ^{2}(v)+\sin ^{2}(u)\sin ^{2}(v)(\sin ^{2}(u)+\cos ^{2}(u))+(\sin ^{2}(u)+\cos ^{2}(u))\sin ^{2}(v)\cos ^{2}(u))$$
$$r^{2}(R+r\cos(v))^{2}(\cos ^{2}(v)+\sin ^{2}(u)\sin ^{2}(v)+\sin ^{2}(v)\cos ^{2}(u))$$
$$r^{2}(R+r\cos(v))^{2}(\cos ^{2}(v)+\sin ^{2}(v))$$
$$=r^{2}(R+r\cos(v))^{2}$$
$$\therefore \left| \frac{∂\mathbf{r}}{\partial u} × \frac{ \partial \mathbf{r} }{ \partial v } \right|=r(R+r\cos(v)) \implies dS=r(R+\cos(v))dudv$$
	(c) Hence, by performing surface integration show that the surface area of the torus is given by $$\iint_{S}dS=4\pi^{2}rR$$
$$\iint_{S}dS=\int ^{2\pi}_{0}  \, du \int ^{2\pi}_{0}  \, dv\,(rR+r^{2}\cos(v))=\int ^{2\pi}_{0}  \, du \int ^{2\pi}_{0}  \, dv\, rR+\int ^{2\pi}_{0}  \, du \int ^{2\pi}_{0}  \, dv\, r^{2}\cos (v)$$
We can use the fact that $\cos(v)$ is even and the region is axisymmetric and so its integral is $0$, thus we are left with
$$=\int ^{2\pi}_{0}  \, du \int ^{2\pi}_{0}  \, dv\, rR+0=\int ^{2p}_{0}  \, du\,2\pi rR=4\pi^{2}rR$$