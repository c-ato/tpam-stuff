[[2MVA Problem Sheet 2.pdf]]

1. The domain $T$ is the solid tetrahedron with vertices $(0, 0, 0)$, $(1, 0, 0)$, $(1, 1, 0)$ and $(1, 0, 1)$. Sketch the domain $T$ and evaluate the following triple integral: $$I=\iint_{T}xyzdxdydz$$[20]
![[MVA sheet 2 2025-10-27 13.59.03.excalidraw]]
$$0\leq x\leq 1\qquad 0\leq y\leq x\qquad 0\leq z\leq x-y$$
$$\int ^{1}_{0} \int ^{x}_{0} \int ^{x-y}_{0} xyz \, dz  \, dy  \, dx=\int ^{1}_{0} \int ^{x}_{0} \frac{x^{3}y+xy^{3}}{2}-x^{2}y^{2}\, dy  \, dx =\int ^{1}_{0} \frac{x^{5}}{4}+\frac{x^{5}}{8}-\frac{x^{5}}{3}  \, dx= \int ^{1}_{0} \frac{x^{5}}{24} \, dx $$
$$=\frac{1}{144}$$
2. Change to polar coordinates and compute the integral: $$I=\int ^{1}_{0}  \, dx \int ^{\sqrt[  ]{ 4-x^{2} }}_{x\sqrt[  ]{ 3 }} x^{2}y(x^{2}+y^{2}) \, dy $$[20]
$$x^{2}+y^{2}= r^{2}\qquad x\sqrt[  ]{ 3 }\leq y\leq \sqrt[  ]{ 4-x^{2} }\implies x^{2}+y^{2}= r^{2}\leq 4\iff  r\leq2 \because  r\geq 0$$
$$x\sqrt[  ]{ 3 }=\sqrt[  ]{ 4-x^{2} }\implies 4x^{2}=4\impliedby x=1 \therefore y= \sqrt[  ]{ 3 }\implies \theta_{1}=\arctan\left( \frac{y}{x} \right)=\frac{\pi}{3}$$
$$x=0= r\cos \theta_{2}\impliedby \theta_{2}=\frac{\pi}{2}\qquad 0\leq r\leq 2\qquad \frac{\pi}{3}\leq\theta\leq \frac{\pi}{2}$$
![[MVA sheet 2 2025-10-27 15.28.55.excalidraw]]
$$I=\int ^{}_{}  \, dx \int ^{}_{} x^{2}y(x^{2}+y^{2}) \, dy =\int ^{}_{}  \, d\theta \int ^{}_{} r^{3}\cos ^{2}\theta \sin \theta( r^{2}) \, rdr =\int ^{\frac{\pi}{2}}_{\frac{\pi}{3}} \cos ^{2}\theta \sin \theta \, d\theta \int ^{2}_{0} r^{6} \, dx  $$
$$=- \frac{1}{3}\left[ \cos ^{3}\theta \right] ^{\frac{\pi}{2}}_{\frac{\pi}{3}}\cdot\left[ \frac{r^{7}}{7} \right] ^{2}_{0}=\frac{16}{21}$$
3. Consider the following triple integral $$I=\iiint_{T}z^{3}dxdydz$$ where $T$ is the domain bounded by the planes, $x=0$, $y=0$, $z=0$ and $x+y+z=2$
(a) Express the integral as repeated integrals using Cartesian coordinates.
$$0\leq x\leq 2-z-y\qquad 0\leq 2-z-y\implies 0\leq y\leq 2-z\implies 0\leq z\leq 2$$
$$\therefore I=\int ^{2}_{0}  \, dz \int ^{2-z}_{0}  \, dy \int ^{2-z-y}_{0} z^{3} \, dx $$
(b) Express the integral as repeated integrals using cylindrical coordinates.
$$r(\cos \theta+\sin \theta)+z=2\implies 0\leq z\leq 2-r(\cos \theta+\sin \theta)\qquad 0\leq x=r\cos \theta\leq 2\implies 0\leq r\leq \frac{2}{\cos \theta}$$
$$x=1, z=0\implies y=0= \arctan \frac{y}{x}=\theta_{1}=0\qquad x=0=r\cos \theta_{2}\impliedby \theta_{2}=\frac{\pi}{2}$$
$$I=\int ^{\frac{\pi}{2}}_{0}  \, d\theta \int ^{\frac{2}{\cos \theta}}_{0}  \, dr \int ^{2-r(\cos \theta+\sin \theta)}_{0} z^{3}r \, dz  $$
(c) Express the integral as repeated integrals using spherical coordinates.
$$\rho(\cos \theta \sin \phi+\sin \theta \sin \phi+\cos\phi)=2\implies 0\leq\rho\leq \frac{2}{\cos \theta \sin \phi+\sin \theta \sin \phi+\cos \phi}$$
$$0\leq \theta\leq \frac{\pi}{2},0\leq \phi\leq \frac{\pi}{2}\qquad \int ^{\frac{\pi}{2}}_{0}  \, d\theta \int ^{\frac{\pi}{2}}_{\frac{\pi}{0}}  \, d\phi \int ^{\frac{2}{\cos \theta \sin \phi+\sin \theta \sin \phi+\cos \phi}}_{0} \rho^{5}\cos ^{3}\theta \sin \phi\, d\rho  $$
(d) Calculate the triple integral using one of the three coordinate systems.
$$I=\int ^{2}_{0}  \, dz \int ^{2-z}_{0}  \, dy \int ^{2-z-y}_{0} z^{3} \, dx =\int ^{2}_{0}  \, dz \int ^{2-z}_{0}  \, dy (2-z-y)z^{3}=\int ^{2}_{0}  \, dz \left( 2-z-\frac{(2-z)^{2}}{2} \right)$$
$$=4-2-2+2-\frac{2}{3}=\frac{4}{3}$$
4. 
(a) Express the integral as repeated integrals using Cartesian coordinates. 
$$\sqrt[  ]{ z-y^{2} }\leq x\leq \sqrt[  ]{ 2-y^{2}-z^{2} }\implies 0\leq \sqrt[  ]{ 2-y^{2}-z^{2} }\implies 0\leq y\leq\sqrt[  ]{ 2-z^{2} }$$
$$\implies 0\leq z\leq \sqrt[  ]{ 2 }\therefore I=\int ^{\sqrt[  ]{ 2 }}_{0}  \, dz \int ^{\sqrt[  ]{ 2-z^{2} }}_{0}  \, dy \int ^{\sqrt[  ]{ 2-y^{2}-z^{2} }}_{\sqrt[  ]{ z-y^{2} }}  \, dx   z$$
(b) Express the integral as repeated integrals using cylindrical coordinates. 
$$x^{2}+y^{2}+z^{2}=r^{2}+z^{2}=2\qquad z=r^{2}\implies r^{2}\leq z\leq \sqrt[  ]{ 2-r^{2} }\qquad 0\leq \theta\leq \frac{\pi}{2} \because x,y\geq 0$$
![[MVA sheet 2 2025-11-05 15.29.22.excalidraw]]
$$r^{2}+z^{2}=2\qquad z=r^{2}\implies z+z^{2}=2\impliedby z=1\impliedby r=1\implies 0\leq r\leq 1$$
$$0\leq z\leq \sqrt[  ]{ 2 }\implies I= \int ^{1}_{0}  \, dr \int ^{\sqrt[  ]{ 2-r^{2} }}_{r^{2}}  \, dz \int ^{\frac{\pi}{2}}_{0}  \, d\theta  zr   $$
(c) Express the integral as repeated integrals using spherical coordinates. 
$$z=x^{2}+y^{2}=\rho \cos \phi=\rho^{2}\sin ^{2} \phi\qquad \rho^{2}=2\implies \cot \phi \csc \phi\leq\rho\leq \sqrt[  ]{ 2 }\qquad 0\leq \theta\leq \frac{\pi}{2}$$
$$\phi=\tan ^{-1}\left( \frac{1}{1} \right)=\frac{\pi}{4}\implies 0\leq \phi\leq \frac{\pi}{4}\implies I=\int ^{\frac{\pi}{4}}_{0}  \, d\phi \int ^{\frac{\pi}{2}}_{0}  \, d\theta \int ^{\sqrt[  ]{ 2 }}_{\cot \phi \csc \phi}  \, d\rho \rho^{3}\sin \phi \cos \phi  $$

(d) Calculate the triple integral using one of the three coordinate systems. 
$$I= \int ^{\frac{\pi}{2}}_{0}  \, d\theta\int ^{1}_{0}  \, dr \int ^{\sqrt[  ]{ 2-r^{2} }}_{r^{2}}  \, dz zr=\frac{1}{2}\left[ \theta \right] ^{\frac{\pi}{2}}_{0}\int ^{1}_{0}  \, dr r\left[ z^{2} \right]^{\sqrt[  ]{ 2-r^{2} }}_{r^{2}} =\frac{\pi}{4}\int ^{1}_{0}  \, dr r(2-r^{2}-r^{4})=$$
$$\frac{\pi}{4}\left[ r^{2}-\frac{r^{4}}{4}-\frac{r^{6}}{6} \right] ^{1}_{0}=\frac{\pi}{4}\left( 1-\frac{1}{4}-\frac{1}{6} \right)= \frac{7\pi}{48} $$
(f) Using the result of (d), or otherwise, calculate the following integral $$J=\iiint_{T}(z+xy\sin (y^{2}))dxdydz$$where the domain $T$ lies between the two surface $z=x^{2}+y^{2}$ and $x^{2}+y^{2}+y^{2}=2$

Note that $I$ from above is axisymmetric with $x$ and $y$ without the domain restriction, so in this part for each we gain a factor of $2$ compared to the above for each axis it is symmetric of, resulting in quadruple the original $I$. Then note that $x\sin(y^{2})$ is symmetric with y, so double the case of $y\geq 0$ but is anti-symmetric of $x$ and so this means the entire integral is 0.
$$J=\iiint zdxdydz+\iiint x\sin(y^{2})dxdydz=4I+0= \frac{7\pi}{12}$$