[[Year 2 Assessed Problems 2.pdf]]

1. 
Choosing the distance of each corner charge to be $r$ from the central charge we can find the magnitudes of lengths of all relevant sides. Also note that $Q_{1}=Q_{2}=Q_{3}=Q$ and $Q_{4}=q$ which is the charge we wish to find the magnitude of and $\underline{r}_{ij}$ is vector from $i$ to $j$. 
![[em2 assessed problem sheet 2 2026-02-04 10.19.14.excalidraw]]
By symmetry we only need to consider finding the force acting on one of the corner charges and resolving it such that overall charge, and force acting on it is $0$.
$$\underline{r}_{12}=r\sqrt[  ]{ 3 }\begin{pmatrix} 1 \\0\end{pmatrix}\qquad \underline{r}_{13}=r\sqrt[  ]{ 3 }\begin{pmatrix} \frac{1}{2} \\ \frac{\sqrt{ 3 }}{2} \end{pmatrix}\qquad \underline{r}_{14}=r\begin{pmatrix} \frac{\sqrt[  ]{ 3 }}{2}\\ \frac{1}{2}\end{pmatrix}\qquad$$
$$\underline{F}_1 = \underline{0} = \sum_{i=2}^{4} \frac{Q_1 Q_i}{4 \pi \varepsilon_0 r_{1i}^2} \hat{r}_i = \frac{Q}{4 \pi \varepsilon_0} \frac{1}{2} \left( \frac{Q}{3r ^{2}} \begin{pmatrix} 3 \\ \sqrt[  ]{ 3 } \end{pmatrix} + \frac{q}{r^{2}} \begin{pmatrix} \sqrt{3} \\ 1 \end{pmatrix} \right)$$
$$=\frac{Q}{4 \pi \varepsilon_0} \frac{1}{2} \left( \frac{\sqrt[  ]{ 3 }}{3}\frac{Q}{r ^{2}} \begin{pmatrix} \sqrt[  ]{ 3 } \\ 1 \end{pmatrix} + \frac{q}{r^{2}} \begin{pmatrix} \sqrt{3} \\ 1 \end{pmatrix} \right)=0$$

$$\therefore q=-\frac{\sqrt[  ]{ 3 }}{3}Q\implies \left| q \right|=\frac{\sqrt[  ]{ 3 }}{3}Q$$

2. 
$$\varphi(r)=\frac{q}{4\pi\varepsilon_{0}r}\qquad \rho=\frac{Q}{\frac{4}{3}\pi R^{3}}=\frac{3Q}{4\pi R^{3}}\qquad d\varphi= \frac{dq}{4\pi\varepsilon_{0}r}= \frac{\rho dV}{4\pi\varepsilon_{0}r}= \frac{4\pi r^{2}\rho dr}{4\pi\varepsilon_{0}r}=\frac{\rho}{\varepsilon_{0}}rdr$$
$$\implies\varphi(r)=\frac{3Q}{4\pi\varepsilon_{0} R^{3}}\int ^{R}_{0} r \, dr =\frac{3Q}{8\pi\varepsilon_{0}R}$$
3. 
![[em2 assessed problem sheet 2 q3]]
By solving for an arbitrary point on the vertical, we will show that it is $\varphi=0$ for the entire vertical and by symmetry this applies for the horizontal as well. Further, we can equate $\left| \underline{r}_{1} \right|=\left| \underline{r}_{4} \right|$ and $\left| \underline{r}_{2} \right|=\left| \underline{r}_{3} \right|$ by symmetry again.
$$\varphi=\frac{Q}{4\pi\varepsilon_{0}r_{1}}+\frac{-Q}{4\pi\varepsilon_{0}r_{4}}+\frac{Q}{4\pi\varepsilon_{0}r_{2}}+\frac{-Q}{4\pi\varepsilon_{0}r_{3}}=\frac{Q}{4\pi\varepsilon_{0}}\left( \frac{1}{r_{1}}-\frac{1}{r_{4}}+\frac{1}{r_{2}}-\frac{1}{r_{3}} \right) $$
$$=\frac{Q}{4\pi\varepsilon_{0}}\left( \frac{1}{r_{1}}-\frac{1}{r_{1}}+\frac{1}{r_{2}}-\frac{1}{r_{2}} \right) =0$$
Now for the force from the image charges, which will be equivalent to the force from the induced charge.
$$\underline{F}=-\frac{Q^{2}}{4\pi\varepsilon_{0}(a\sqrt[  ]{ 2 })^{2}}\mathbf{i}-\frac{Q^{2}}{4\pi\varepsilon_{0}(a\sqrt[  ]{ 2 })^{2}}\mathbf{j}+\frac{Q^{2}}{4\pi\varepsilon_{0}(2a)^{2}}\left( \frac{\sqrt[  ]{ 2 }}{2}\mathbf{i}+\frac{\sqrt[  ]{ 2 }}{2}\mathbf{j} \right)$$
$$=\frac{Q^{2}}{4\pi\varepsilon_{0}a^{2}}\left( \left( -\frac{1}{2}+\frac{\sqrt[  ]{ 2 }}{8} \right)\mathbf{i}+\left( -\frac{1}{2}+\frac{\sqrt[  ]{ 2 }}{8} \right)\mathbf{j} \right)=\frac{Q^{2}}{4\pi\varepsilon_{0}a^{2}} \left( -\frac{1}{2}+\frac{\sqrt[  ]{ 2 }}{8} \right)\underbrace{ (\mathbf{i}+\mathbf{j}) }_{ \frac{\pi}{4} } $$
$$\left| \underline{F} \right|=\left| \frac{Q^{2}}{4\pi\varepsilon_{0}a^{2}} \left( -\frac{1}{2}+\frac{\sqrt[  ]{ 2 }}{8} \right)(\mathbf{i}+\mathbf{j})  \right|=\frac{Q^{2}(2\sqrt[  ]{ 2 }-1)}{16\pi\varepsilon_{0}a^{2}}$$
Direction of force is $\frac{\pi}{4}$ above the horizontal