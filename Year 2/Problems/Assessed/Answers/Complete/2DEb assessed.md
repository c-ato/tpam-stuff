[[2DE_Assessment_2_PartB_2025_26.pdf]]

1
(a)
Fixed points are  at $y=a,b,c$
(b)
$$\dot{y}=f(x)=(y-a)(y-b)(y-c)\qquad \dot{f}(x)=(y-b)(y-c)+(y-a)(y-c)+(y-a)(y-b)$$
$$0<a<b<c\qquad\dot{f}(a)=\underbrace{ (a-b) }_{ <0 }\underbrace{ (a-c) }_{ <0 }>0\therefore y=a\text{ is unstable}$$
$$\qquad\dot{f}(b)=\underbrace{ (b-a) }_{ >0 }\underbrace{ (b-c) }_{ <0 }<0\therefore y=b\text{ is stable}$$
$$\qquad\dot{f}(c)=\underbrace{ (c-a) }_{ >0 }\underbrace{ (c-b) }_{ >0 }>0\therefore y=c\text{ is unstable}$$
(c)
$$\dot{y}=f(x)=(y-a)^{3}\qquad \dot{f}(x)=3(y-a)^{2}\geq 0$$
![[2DEb assessed 1c]]
(d)
$$\dot{y}=(y-a)^{3}\impliedby \frac{\dot{y}}{(y-a)^{3}}dt=1dt\qquad $$
$$ -\frac{1}{2(y-a)^{2}}=t+C\underset{ t=0 }{ \overset{ y=y_{0} }{ \implies }  } C= -\frac{1}{2(y_{0}-a)^{2}}$$
$$y=\pm \sqrt[  ]{ \frac{1}{2(t+C)} }+a$$
$$t=\frac{1}{2(a-y_{0})^{2}}\implies t+C=\frac{1}{2(a-y_{0})^{2}}-\frac{1}{2(y_{0}-a)^{2}}=0$$
$$\therefore y=\pm \sqrt[  ]{ \frac{1}{2(t+C)} }+a=\pm \sqrt[  ]{ \frac{1}{2(0)} }+a$$
2
(a)
$$\begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}\begin{pmatrix}
\dot{x} \\
x
\end{pmatrix}+\begin{pmatrix}
1 \\
0
\end{pmatrix}=\begin{pmatrix}
\ddot{x} \\
\dot{x}
\end{pmatrix}$$
(b)
$$\begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}\begin{pmatrix}
\dot{x} \\
x_{e}
\end{pmatrix}+\begin{pmatrix}
1 \\
0
\end{pmatrix}=\begin{pmatrix}
0 \\
0
\end{pmatrix}$$
$$\begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}\begin{pmatrix}
\dot{x} \\
x_{e}
\end{pmatrix}=\begin{pmatrix}
-1 \\
0
\end{pmatrix}$$
$$\begin{pmatrix}
\dot{x} \\
x_{e}
\end{pmatrix}=\begin{pmatrix}
0 & 1 \\
-1 & -1
\end{pmatrix}\begin{pmatrix}
-1 \\
0
\end{pmatrix}=\begin{pmatrix}
0 \\
1
\end{pmatrix}$$
$$x_{e}=1$$
(c)
$$x=x_{e}+v(t)=v(t)+1\qquad \dot{x}=\dot{v}(t)\qquad \ddot{x}+\dot{x}+x=1=\ddot{v}+\dot{v}+v+1=1$$
$$\ddot{v}+\dot{v}+v=0$$
$$\begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}\begin{pmatrix}
\dot{v} \\
v
\end{pmatrix}=\begin{pmatrix}
\ddot{v} \\
\dot{v}
\end{pmatrix}$$
(d)
$$\det \left( \begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}-\sigma \begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix} \right) =\sigma(\sigma+1)+1=\sigma^{2}+\sigma+1=0$$
$$\sigma=-\frac{1}{2}\pm \frac{\sqrt[  ]{ 3 }}{2}i$$
The imaginary component means it is a spiral, and the negative real component then means it is a stable spiral around $\mathbf{x}_{e}=\begin{pmatrix}0 \\ 1\end{pmatrix}$
$$\begin{pmatrix}
-1 & -1 \\
1 & 0
\end{pmatrix}\begin{pmatrix}
1 \\
0
\end{pmatrix}=\begin{pmatrix}
-1 \\
1
\end{pmatrix}$$
This is anticlockwise movement.
![[2DEb assessed 2d]]