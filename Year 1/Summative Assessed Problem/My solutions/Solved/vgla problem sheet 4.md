\section{Suppose that $z_{1}=1+i$}

\subsubsection{Calculate $z_{1}^{8}$ in both modulus-argument form and exponential form giving the principal value of the argument.}

$$
z_{1}=\sqrt[  ]{ 2 }    \angle \frac{\pi}{4} =\sqrt[  ]{ 2 }e^{i \frac{\pi}{4}}
$$
\subsubsection{Find all the fifth roots of $z_{1}$. Present your answers in exponential form giving the principal value of the argument.}
$$
z_{1}^{\frac{1}{5}}=2^{\frac{5}{2}}e^{ i\left( \frac{\frac{\pi}4{}+2n\pi }{5} \right) },n=\{ 0,1,2,3,4 \}
$$
$$
z_{1}^{\frac{1}{5}}=2^{\frac{1}{10}}e^{ i \frac{\pi}{20} }\,,\,2^{\frac{1}{10}}e^{ i \frac{9\pi}{20} }\,,\,2^{\frac{1}{10}}e^{ i \frac{17\pi}{20} }\,,\,2^{\frac{1}{10}}e^{ i \frac{25\pi}{20} }=2^{\frac{1}{10}}e^{ i \frac{5\pi}{4} }
$$
\section{Consider the polynomial $p(z) = z^{3} - z^{2} + 9z - 9$}
\subsubsection{Determine the roots of $p(z)$}
Observe that $p(1)=1-1+9-9=0\therefore z=1$
$$
\frac{z^{3}-z^{2}+9z-9}{z-1}=z^{2}+9=0 \iff z=\frac{\pm \sqrt[  ]{ 36 }}{2}i=\pm 3i
$$
\subsubsection{Write $p(z)$ as a product of real linear and real irreducible quadratic factors.}
$$
p(z)=(z-1)(z^{2}+1)
$$
\section{The circle of radius $r$ in the $xy$-plane centred at $(a, b) \in \mathbb{R}^{2}$ is described by the equation $(x - a)^{2} + (y - b)^{2} = r^{2}$. Describe the solution set to the equation $|z - 1| = 4|z - 3|$ (where $z \in \mathbb{C}$) as a geometrically defined subset of the Argand diagram.}
$$
\sqrt[  ]{ (x-1)^{2}+ y^{2}}=4\sqrt[  ]{ (x-3)^{2}+(y)^{2} }
$$
$$
(x-1)^{2}+y^{2}=16((x-3)^{2}+y^{2})\implies 15x^{2}-94x+143+15y^{2}=0\implies x^{2}-\frac{94}{15}x+\frac{143}{15}+y^{2}=0
$$
$$
\left( x-\frac{47}{15} \right)^{2}-\frac{47}{15}^{2}+\frac{143}{15}+y^{2}=0\implies\left( x-\frac{47}{15} \right)^{2}+y^{2}=\frac{64}{225}\implies \sqrt[  ]{ \left( x-\frac{47}{15} \right)^{2}-y^{2} }=\frac{8}{15}
$$
$$
\implies\left| z-\frac{47}{15} \right| =\frac{8}{15}
$$
This is a circle centred around $0+\frac{47}{15}i$ in the complex plane, with the radius $r= \frac{8}{15}$
\section{Is the following system of linear equations homogeneous? Justify your answer.
$$
\begin{align}2x_{1}-7(x_{4}+1)-3x_{2}&=2(x_{3}+3)-13 \\x_{1}+x_{2}+x_{3}+x_{4}&=0 \\(x_{1}+1)-2(x_{2}-2)+x_{3} &=5\end{align}$$}
$$
\begin{align}
2x_{1}-7x_{4}-7-3x_{2}&=2x_{3}+6-13 \\
x_{1}+x_{2}+x_{3}+x_{4}&=0 \\
x_{1}+1-2x_{2}-4+x_{3} &=5
\end{align}
$$
$$
\begin{align}
2x_{1}-7x_{4}-3x_{2}&=2x_{3} \\
x_{1}+x_{2}+x_{3}+x_{4}&=0 \\
x_{1}-2x_{2}+x_{3} &=0
\end{align}
$$
$$
\begin{align}
2x_{1}-7x_{4}-3x_{2}-2x_{3}&=0 \\
x_{1}+x_{2}+x_{3}+x_{4}&=0 \\
x_{1}-2x_{2}+x_{3} &=0
\end{align}
$$
Yes, is homologous as constant terms for each is $0$

\section{We define the following matrices: $$A=\begin{pmatrix}
1 & -1 & 2 \\
1 & 3 & -1 \\
-1 & 1 & 4
\end{pmatrix}\quad B=\begin{pmatrix}
-2 & 1 & 0 \\
0 & 1 & 2 \\
4 & -1 & 2
\end{pmatrix}\quad C=\begin{pmatrix}
6 & 1 \\
2 & 0 \\
-1 & 1
\end{pmatrix}$$. For each of the following matrix calculations, either do the calculation or explain why it is not possible to do the calculation}
\subsubsection{$A+B;$}
$$
\begin{pmatrix}
1 & -1 & 2 \\
1 & 3 & -1 \\
-1 & 1 & 4
\end{pmatrix}+\begin{pmatrix}
-2 & 1 & 0 \\
0 & 1 & 2 \\
4 & -1 & 2
\end{pmatrix}=\begin{pmatrix}
-1 & 0 & 2 \\
1 & 4 & 1 \\
3 & 0 & 6
\end{pmatrix}
$$
\subsubsection{$B\cdot A;$}
$$
\begin{pmatrix}
-2 & 1 & 0 \\
0 & 1 & 2 \\
4 & -1 & 2
\end{pmatrix}\begin{pmatrix}
1 & -1 & 2 \\
1 & 3 & -1 \\
-1 & 1 & 4
\end{pmatrix}=\begin{pmatrix}
-1 & 5 & -5 \\
-1 & 5 & 7 \\
1 & -5 & 17
\end{pmatrix}
$$
\subsubsection{$C\cdot A;$}
Cannot as $C$ does not have the same amount of columns as $A$ does rows.
\subsubsection{$(B\cdot2C)+\frac{1}{2}C$}
$$
\begin{pmatrix}
-2 & 1 & 0 \\
0 & 1 & 2 \\
4 & -1 & 2
\end{pmatrix}\cdot2\begin{pmatrix}
6 & 1 \\
2 & 0 \\
-1 & 1
\end{pmatrix}+\frac{1}{2}\begin{pmatrix}
6 & 1 \\
2 & 0 \\
-1 & 1
\end{pmatrix}=\begin{pmatrix}
-2 & 1 & 0 \\
0 & 1 & 2 \\
4 & -1 & 2
\end{pmatrix}\begin{pmatrix}
12 & 2 \\
4 & 0 \\
-2 & 2
\end{pmatrix}+\begin{pmatrix}
3 & \frac{1}{2} \\
1 & 0 \\
-\frac{1}{2} & \frac{1}{2}=
\end{pmatrix}
$$$$
=\begin{pmatrix}
-20 & -4 \\
0 & 4 \\
40 & 12
\end{pmatrix}+\begin{pmatrix}
3 & \frac{1}{2} \\
1 & 0 \\
-\frac{1}{2} & \frac{1}{2}=
\end{pmatrix}=\begin{pmatrix}
-17 & -3.5 \\
1 & 4 \\
39.5 & 12.5
\end{pmatrix}
$$
