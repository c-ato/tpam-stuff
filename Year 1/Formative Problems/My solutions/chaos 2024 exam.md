[[CHAOS (A-B) 2024.pdf]]

1. A dissipative oscillator is described by the equation $$\frac{ d^{ 2 }x }{ dt^{ 2 } }  +x=\eta \frac{ dx }{ dt } \cos x$$where $\eta$ is a variable parameter.
- (a) Employ the position, $x$, and the momentum, $p ≡ \frac{dx}{dt}$ , to find the fundamental equation.
$$
\frac{ dp }{ dt }  =\eta p\cos x-x
$$
- (b) Solve for the trajectory in the limit $\eta=0$, and include the time dependency.
$$
\frac{ d^{ 2 }x }{ dt^{ 2 } } +x=0\iff x=A\cos t +B\sin t 
$$
$$
\frac{ dx }{ dt } =p=B\cos t-A\sin t\implies p^{2}+x^{2}=A^{2}+B^{2}
$$
- (c) What do you think happens when $\eta$ is non-zero by tiny?

The system will oscillate but will dissipate if $\eta>0$, slowly and non-uniformly due to the $\cos x$.

- (d) Employ the position, $x$, and the analogue momentum, $q ≡ \frac{1}{\eta} \frac{ dx }{ dt } − \sin x$, to find a second fundamental equation
$$
q=\frac{1}{\eta}\frac{ dx }{ dt } -\sin x\implies \frac{ dx }{ dt } =\eta q+\eta\sin x\implies \frac{ d^{ 2 }x }{ dt^{ 2 } } =\eta \frac{ dq }{ dt } +\eta\frac{ dx }{ dt } \cos x 
$$
$$
=\frac{ d^{ 2 }x }{ dt^{ 2 } }  =\eta \frac{ dx }{ dt } \cos x-x\therefore \eta \frac{ dq }{ dt } =-x
$$
- (e) Solve for the behaviour of $q$ where $\eta=\infty$
$$
q=\frac{1}{\eta}\frac{ dx }{ dt } -\sin x\to -\sin x
$$
In this case $q$ oscillates regularly.
$$
\eta \frac{ dq }{ dt } =-x\implies \frac{ dq }{ dt }=-\frac{x}{\eta}\to 0 
$$
Otherwise $q$ remains constant.

- (f) Solve for the behaviour of $x$ when $η=∞$, being very careful to consider $q < 1, q > 1, q = 0$ and $q = 1$ independently. You may like to rescale time with $T = ηt$ and solve for $x(T )$. (Hint: You may find the transformation $s = \tan\frac{x}{2}$ useful.)
$$
q=\frac{1}{\eta}\frac{ dx }{ dt } -\sin x=\frac{ dx }{ dT } -\sin x\overset{ q=0 }{ = }0\iff \frac{ dx }{ dT } =\sin x\implies \int ^{}_{} \csc x \, dx =T
$$
$$
=-\ln|\cot x+\csc x|+C=-\ln \left| \frac{\cos x+1}{\sin x} \right|+C=-\ln \left| \frac{2\cos ^{2}\left( \frac{x}{2} \right)}{2\sin\left( \frac{x}{2} \right)\cos\left( \frac{x}{2} \right)} \right|+C
$$
$$
=-\ln \left|\cot\left( \frac{x}{2} \right) \right|+C=\ln \left|\tan\left( \frac{x}{2} \right) \right|+C=T\implies x=2\tan ^{-1}(Ae^{T})
$$

$$
q=\frac{1}{\eta}\frac{ dx }{ dt } -\sin x=\frac{ dx }{ dT } -\sin x\overset{ q=1 }{ = }1\iff \frac{1}{\sin x+1} \frac{ dx }{ dT } =1\implies \int ^{}_{} \frac{1}{\sin x+1} \, dx =T
$$
$$
\int ^{}_{} \frac{\sin x-1}{\sin ^{2}x-1} \, dx =\int ^{}_{} \frac{1-\sin x}{\cos ^{2}} \, dx \int ^{}_{} \sec^{2}x-\tan x\sec x \, dx =\tan x-\sec x+C=\frac{\sin x-1}{\cos x}
$$
$$
=\frac{2s}{1-s^{2}}- \frac{1-s^{2}}{1+s^{2}}=\frac{2s(1+s^{2})-(1-s^{2})^{2}}{(1-s^{2})(1+s^{2})}=\frac{2s+2s^{3}-1+2s^{2}-s^{4}}{}T+C
$$
gave up
- (g) What do you think happens when $\eta$ is finite by huge.
Very quick to dissipate

2. Consider the map $$x_{n+1}=r\left( x_{n}+\frac{1}{x_{n}} \right)$$
- (a) Find all the possible 1-cycles and establish for which range of control parameter they are stable.
$$
x=r\left( x+\frac{1}{x} \right)\implies x^{2}= \frac{1}{1-r}\iff x=\pm \sqrt[  ]{ \frac{1}{1-r} }\qquad x\neq 0\qquad r>1
$$
$$
1>\frac{ df }{ dx } =r\left( 1-\frac{1}{x^{2}} \right)>-1\implies \frac{r}{r-1}> x^{2}>0> \frac{1}{1-r}
$$
$$
\implies \frac{r}{r-1}> \frac{1}{(1-r)^{2}}\implies r(r-1)=r^{2}-r>1\qquad r> \frac{1}{2} + \frac{\sqrt[  ]{ 5 }}{2}\qquad r< \frac{1}{2} - \frac{\sqrt[  ]{ 5 }}{2}
$$
$$
\because r>1 \qquad r> \frac{1+\sqrt[  ]{ 5 }}{2}
$$
- (b) Find all the possible 2-cycles and establish for which range of control parameter they are stable.
$$
y=r\left( x+\frac{1}{x} \right)\qquad x=r\left( y+\frac{1}{y} \right)\implies \frac{xy}{1+y^{2}}=r= \frac{xy}{1+x^{2}}\implies x^{2}=y^{2}\implies x=-y 
$$
$$
\because x=y\text{ is 1 cycle}\qquad x,y\neq 0
$$
$$
-x=r\left( x+\frac{1}{x} \right)\implies x=\pm \sqrt[  ]{ \frac{1}{1+r} }\implies y= \mp \sqrt[  ]{ \frac{1}{1+r} }\qquad r>-1
$$
$$
-1<\frac{ df }{ dx } \frac{ df }{ dy } <1\qquad -1<0<\left( r\left( 1-\frac{1}{x^{2}} \right) \right) ^{2}<1\implies -1<r\left( 1-\frac{1}{x^{2}} \right)<1
$$
$$
\implies r>  \frac{1+\sqrt[  ]{ 5 }}{2}\qquad r<\frac{1-\sqrt[  ]{ 5 }}{2} \qquad \because -1<r\qquad -1<r<\frac{1-\sqrt[  ]{ 5 }}{2}\qquad r>\frac{1+\sqrt[  ]{ 5 }}{2}
$$
- (c) Find the attractor when it is either a 1-cycle or a 2-cycle.
$$
\text{1 cycle:} \sqrt[  ]{ \frac{1}{1-r} } \text{ or }-\sqrt[  ]{ \frac{1}{1-r} }
$$
$$

\text{2 cycle:} \sqrt[  ]{ \frac{1}{1+r} } \text{ and }-\sqrt[  ]{ \frac{1}{1+r} }
$$
3. A map is defined by $y_{n+1}=M[y_{n}]$ with $$\begin{matrix}
 & M[y]=2y & y\in\left[ 0, \frac{1}{2} \right] \\
 & M[y]=3-4y & y\in\left[ \frac{1}{2} , \frac{3}{4} \right]  \\
 & M[y]=8y-6 & y\in\left[ \frac{3}{4}, \frac{7}{8} \right]  \\
 & M[y]=8-8y & y\in\left[\frac{7}{8} , 8 \right] 
\end{matrix}$$
- (a) Depict this map on the interval $y \in [0,1]$
![[chaos 2024 exam 2025-05-21 11.31.48.excalidraw]]
- (b) Employ base 2 to find a useful representation for this map.
$$
\begin{matrix}
\text{As base 2 decimal:} &   0.a_{1}a_{2}a_{3}a_{4}a_{5}\dots \\
\text{In first interval }\left[ 0, \frac{1}{2} \right]: & a_{1}=1 &  0.1a_{2}a_{3}a_{4}\dots \\
\text{In 2nd interval }\left[ \frac{1}{2} , \frac{3}{4} \right]: & a_{1}=1,a_{2}=1 &  0.11a_{3}a_{4}\dots \\
\text{In 3rd interval }\left[ \frac{3}{4}, \frac{7}{8} \right] : & a_{1}=1,a_{2}=1,a_{3}=1 &  0.111a_{4}\dots \\
\text{In 4th interval }\left[\frac{7}{8} , 8 \right] : & a_{1}=1,a_{2}=1,a_{3}=1,a_{4}=1 &  0.1111\dots
\end{matrix}
$$
- (c) Demonstrate that binary numbers of the form $0.a_{1}a_{2}a_{3}b_{1}b_{2}b_{3}c_{1}c_{2}c_{3}\dots$ where the triples are restricted to $x_{1}x_{2}x_{3} ∈ \{000, 111, 010, 101\}$ are preserved by this map. 
$$
\begin{matrix}
M[0.000b_{1}\dots]\to M[0.00b_{1}b_{2}\dots]\to M[0.0b_{1}b_{2}b_{3}\dots]\to M[0.b_{1}b_{2}b_{3}\dots]  \\
M[0.111c_{1}\dots]\to M[0.00(1-c_{1})(1-c_{2})\dots]\to M[0.(1-c_{1})(1-c_{2})(1-c_{3})\dots] \\
M[0.010\dots]\to M[0.10a_{1}\dots]=M[0.1(1-a_{1})(1-a_{2})...]=M[0.a_{1}a_{2}a_{3}\dots] \\
M[0.101d_{1}\dots]\to M[10(1-d_{1})\dots]\to M[0.1d_{1}d_{2}\dots]\to M[0.(1-d_{1})(1-d_{2})(1-d_{3})\dots]
\end{matrix}
$$
- (d) Find a sequence of cycles of this form, starting from a 1-cycle and reaching a 6-cycle
$$
\begin{matrix}
\text{1 cycles} & 0.\dot{0},0.\dot{1}\dot{0} \\
\text{2 cycles} & 0.\dot{1}0\dot{1} \\
\text{3 cycles} & 
\end{matrix}
$$
cba too long

