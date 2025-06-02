[[Year 1/Formative Problems/Problem sheet/Exam papers/2023/Paper/1RA.pdf|1RA]]

1. 
- (a) Let $X$ and $Y$ be sets. Define what it means for $f$ to be a function from $X$ to $Y$.

$X=\text{dom(f)}$ and $Y=\text{codom}(f)$ and $f$ has a well defined rule satisfying the following$\forall x \in X \exists y\in Y :f(x)=y$
- (b) Let $f : \mathbb{R} → \mathbb{R}$ be a function and $α, ℓ ∈ \mathbb{R}$. 
	- (i) Define what it means that $$\lim_{ x \to \alpha }f(x)\to \ell $$
Let $\varepsilon>0(\in R)$ and $\delta>0(\in \mathbb{R})$ s.t. $0<\left| f(x)-\ell \right|<\varepsilon$ whenever $0<\left| x-\alpha \right|<\delta$.

- (c) Let $f : \mathbb{R} → \mathbb{R}$ be a differentiable function and $α ∈ \mathbb{R}$.
	- (i) Define $f ′(α)$, the derivative of $f$ at $α$
$$
f'(x)=\lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h}\therefore  f'(\alpha)= \frac{f(\alpha+h)-f(\alpha)}{h}
$$
- .
	- (ii) By directly using the definition of derivative from (i), find the derivative of the function, $f(x)=x^{2}$ at the point 5.
$$
f'(x)=\lim_{ h \to 0 } \frac{(x+h)^{2}-x^{2}}{h}=\lim_{ h \to 0 }  \frac{2xh+h^{2}}{h}=\lim_{ h \to 0 } 2x+h\to 2x\therefore f'(5)=10
$$

- (d) Let $f : \mathbb{R} → \mathbb{R}$ with $f (x) = 2x^{3} − 6x^{2} − 18x + 7$ for all $x ∈ \mathbb{R}$. Justify all the assertions that you make. You can use any of the results discussed in lectures, provided you clearly state what you are using.
	- (i) Find the increasing and decreasing intervals of $f$
$$
f'(x)=(2x^{3}-6x^{2}-18x+7)'=6x^{2}-12x-18\qquad \text{increase: }f'(x)>0\implies x^{2}-2x-3>0
$$
$$
x>3,x<-1\qquad \text{decrease: }f'(x)<0\implies x^{2}-2x-3<0\qquad 3>x>-1
$$
- .
	- (ii) Find all local maximum and local minimum points of $f$
$$
f'(x)=6x^{2}-12x-18=0\qquad x=3,-1\qquad f''(x)=(f'(x))'=(6x^{2}-12x-18)'=
$$
$$
12x-12= \overset{ x=3 }{ 24 },\overset{ x=-1 }{ -24 }\qquad f(x)=\overset{ x=3 }{ -47 },\overset{ x=-1 }{ 19 }\qquad \text{Min: }(3,-47)\qquad \text{Max: }(-1,19)
$$
- .
	- (iii) Find the convex and concave intervals of $f$
$$
\begin{matrix}
\text{Convex:} & f''(x)=(f'(x))'= & (6x^{2}-12x-18)'=12x-12>0\qquad x>1 \\
\text{Concave:} & f''(x)= & (6x^{2}-12x-18)'=12x-12<0\qquad x<1
\end{matrix}
$$
2. 
- (a) Define what it means for a bounded function $f:[0.1]\to \mathbb{R}$ to be integrable.

A function $f$ is integrable on an interval if for $\varepsilon>0(\in \mathbb{R})\exists P \,s.t.U(f,P)-L(f,P)<\varepsilon$

- (b) State the First Fundamental Theorem of Calculus.

Let $f:[a,b]\mapsto \mathbb{R}$ be a bounded integrable function and suppose that $F:[a,b]\mapsto \mathbb{R}$ s.t. $F:= \int ^{x}_{a} f \forall x \in[a,b]$. If $f$ is continuous at $c (\in[a,b])$, then $F$ is differentiable at $c$ with derivative $F'(c)=f(c)$

![[ra note 5#^thm-ra-fftc]] 

- (c) Suppose that $P = \{2, 4, 10\}$ and that $f : [2, 10] → \mathbb{R}$ is given by:$$f(x):= \left\{ \begin{matrix}x,  & \text{if }x \notin \{ 4,10 \} \\1,  & \text{if }x =4 \\9,  & \text{if }x =10\end{matrix} \right. $$Compute both the lower sum $L( f , P)$ and the upper sum $U( f , P)$. 
$$
L(f,P)=2+6=8\qquad U(f,P)=8+60=68
$$
-  (d) Find an antiderivative of the function $g : (−2π, 3π) → \mathbb{R}$ given by $g(x) := \sin^{3}(x) \cos ^{4}(x)$ for all $x ∈ (−2π, 3π)$. 
$$
\int ^{}_{} g(x) \, dx  = \int ^{}_{} \sin^{3}x \cos ^{4}x \, dx =\int ^{}_{} \sin x(1-\cos ^{2}x)\cos ^{4}x\, dx 
$$
$$
u=\cos x\implies du=-\sin x\,dx\implies \int ^{}_{} (1-u^{2})u ^{4}\, du=\int ^{}_{} u^{4}-u^{6} \, du 
$$
$$
=\frac{u^{5}}{5}-\frac{u^{7}}{7}=\cos^{5}x \left( \frac{1}{5}+ \frac{\cos ^{2}x}{7} \right)
$$
- (e) Compute the improper integral $\int ^{2}_{1} \frac{x}{x^{2}-4x+3} \, dx$ or show that it diverges
$$
\int ^{2}_{1} \frac{x}{x^{2}-4x+3} \, dx=\int ^{2}_{1} \frac{x}{(x-1)(x-3)} \, dx\qquad x=A(x-1)+B(x-3)\implies B= -\frac{1}{2}\qquad A=\frac{3}{2}
$$
$$
\int ^{2}_{1} \frac{3}{2} \frac{1}{x-3}- \frac{1}{2} \frac{1}{x-1} \, dx=\left[ \frac{3}{2}\ln \left| x-3 \right|-\frac{1}{2}\ln \left| x-1 \right| \right] ^{2}_{1}=\left[ \frac{1}{2}\ln \left|  \frac{(x-3)^{3}}{x-1} \right| \right]^{2}_{1}
$$
$$
=\frac{1}{2}\left( \ln \left| \frac{-1}{1} \right|-\ln \left|  \frac{-8}{0} \right| \right) =\ln \infty=\infty \text{ $\therefore$ this diverges}
$$
- (f) Find a solution $y : [0, ∞) → \mathbb{R}$ of the initial value problem $$y'=2x\sin(5x), \qquad y(0)=9$$
$$
y=\int ^{}_{} y' \, dx=\int ^{}_{} 2x\sin(5x) \, dx \qquad u=2x\qquad v'=\sin(5x)\qquad u'=2\qquad v=- \frac{1}{5}\cos (5x)
$$
$$
=- \frac{2}{5}x\cos(5x)+ \int ^{}_{} \frac{2}{5} \cos(5x) \, dx =\frac{2}{5}\left( \frac{1}{5}\sin(5x)- x\sin(5x) \right)+C
$$
$$
y(0)=9=C\therefore y=\frac{2}{5}\left( \frac{1}{5}\sin(5x)- x\sin(5x) \right)+9
$$
- (g) Find the general solution of the differential equation $4y''-20y'+25y$ on $\mathbb{R}$.
$$
y=Ae^{ \lambda x }\implies 4\lambda^{2}-20\lambda+25=0=(2\lambda-5)^{2} \therefore\lambda=2.5\implies y= Ae^{ 2.5x }+Bxe^{ 2.5x }\because\text{repeat root}
$$
3. 
- (a) We want to construct a cylindrical can with a bottom but no top that will have a volume of $27π cm^{3}$. Determine the dimensions (the radius and height) of the can that will minimize the amount of material needed to construct the can. Justify the assertion that you make. You can use any of the results discussed in lectures, provided you clearly state what you are using. 
$$
\pi r^{2}h=V=27\pi\qquad 2\pi rh+\pi r^{2}=A\implies  2\pi r\frac{V}{\pi r^{2}}\qquad\frac{2V}{r}+\pi r^{2} =A \qquad \frac{dA}{dr}=2\pi r-\frac{2V}{r^{2}}
$$
$$
=\frac{1}{r^{2}}(2\pi r^{3}-2V)=0\implies r= \sqrt[ 3 ]{ \frac{V}{\pi} }\,(\text{only sol})\qquad \frac{ d^{ 2 }A }{ dr^{ 2 } } =2\pi+\frac{2V}{r^{3}}=4\pi>0 \therefore \min 
$$
$$
\therefore r=3\implies h=3
$$
- (b) Determine whether the following limits exist, and if so find their values. Justify your answers. You can use any of the results discussed in lectures, provided you clearly state what you are using. 
	- (i) $\lim_{ x \to 0 } \frac{e^{ x }\cos x+5\sqrt[  ]{ 1-x }}{1+\arctan x+\ln(1-x)}$
$$
\lim_{ x \to 0 } \frac{e^{ x }\cos x+5\sqrt[  ]{ 1-x }}{1+\arctan x+\ln(1-x)}\to \frac{1+5}{1}=6
$$
- .
	- (ii) $\lim_{ x \to 0 }\left( \frac{\pi}{2}-\arctan x \right)^{\frac{1}{\ln x}}$
$$
\lim_{ x \to 0 }\left( \frac{\pi}{2}-\arctan x \right)^{\frac{1}{\ln x}}=\left( \frac{\pi}{2} \right)^{\lim_{ x \to 0 } \frac{1}{\ln x}}=\left( \frac{\pi}{2} \right)^{\lim_{ x \to 0 } \frac{0}{ \frac{1}{x}}}=\left( \frac{\pi}{2} \right)^{\lim_{ x \to 0 } 0}=1
$$
- (c) Let $a, b ∈ \mathbb{R}$ and $a > 0$. Let $f : \mathbb{R} → \mathbb{R}$ be the polynomial $$f(x)=x^{3}+ax+b$$Prove that there exists exactly one number $x_{0}\in \mathbb{R}$ such that $f(x_{0})=0$
$$
f'(x)=3x^{2}+a> 0 \forall x \in \mathbb{R}\therefore \text{monotonically increasing}
$$
$$
\lim_{ x \to \infty } f(x)=\infty\qquad \lim_{ x \to -\infty } f(x)=-\infty \therefore \text{by IVT }\exists x_{0}\in(-\infty,\infty)(\mathbb{R})\text{ s.t. }f(x_{0})=0
$$
And as this is monotonically increasing $f(x)$ can only cross the $x$-axis once.

4. 
- (a) Suppose that $f:[-6,-5]\to \mathbb{R}$ is given by $$f:=\left\{ \begin{matrix}-x, & \text{if }x \in \mathbb{Z}; \\8,  & \text{if }x \notin \mathbb{Z}.\end{matrix} \right. $$Use Riemann’s Criterion or otherwise to prove that $f$ is integrable.
$$
P=\{ -6,-6+\delta,-5-\delta,-5 \}\qquad L(f,P)=6(\delta)+8(1-2\delta)+5(\delta)=8-5\delta
$$
$$
U(f,P)=8(\delta)+8(1-2\delta)+8(\delta)=8\qquad U(f,P)-L(f,P)=5\delta<\varepsilon
$$
Choose $\delta=\frac{\varepsilon}{10}$
$$
U(f,P)-L(f,P)=5\delta=\frac{\varepsilon}{2}<\varepsilon
$$
Hence $f(x)$ is integrable

- (b) Suppose that $R = \{0, 1, 3, 4\}, S = \{2, 3\}$ and $g : [0, 4] → [5, 10]$. Prove directly, without using the Partition Lemma, that $L(g, R) ≤ L(g, R ∪ S)$. 
$$
R\cup S=\{ 0,1,2,3,4 \}\qquad m_{i}=\min\{ g(x):x \in[i,i+1] \}
$$
$$
L(g,R)=m_{0}+2\min\{ g(x):x \in[1,3] \}+m_{4}
$$
$$
L(g,R \cup S)=m_{0}+\min\{ g(x):x \in[1,2] \}+\min\{ g(x):x \in[2,3] \}+m_{4}
$$
Observe the differences:
$$
2\min\{ g(x):x \in[1,3] \}\qquad \min\{ g(x):x \in[1,2] \}+\min\{ g(x):x \in[2,3] \}
$$
$$
\because [1,2],[2,3]\in [1,3] \therefore \min\{ g(x):x \in[1,3] \}\leq\min\{ g(x):x \in[1,2] \}
$$
$$
\land\min\{ g(x):x \in[1,3] \}\leq\min\{ g(x):x \in[2,3] \}
$$
$$
\therefore2\min\{ g(x):x \in[1,3] \}\leq\min\{ g(x):x \in[1,2] \}+\min\{ g(x):x \in[2,3] \}
$$
$$
\therefore L(g, R) ≤ L(g, R ∪ S)
$$
- (c) Suppose that $h:(0,1)\to \mathbb{R}$ is given by $$h(x):=\int ^{2x+1}_{0} \sqrt[  ]{ 100-t^{4} } \, dt $$for all $x ∈ (0, 1)$. Prove that $h$ is differentiable and find an expression for the derivative $h′(x)$, for all $x ∈ (0, 1)$, that does not contain the integral or antiderivative symbol $\int$.

Let 
$$
f(x)=\int ^{x}_{0} \sqrt[  ]{ 100-t^{4} } \, dt\qquad g(x)=2x+1\qquad \therefore f(g(x))=h(x) \qquad F=f'(x)=\sqrt[  ]{ 100-x^{4} }
$$
$F$ is continuous on the interval $x \in [0,1]$ ($g:[0,1]\to[1,3]$) as $F$ is composed of continuous elementary functions ($x^{4}$, subtraction and $\sqrt[  ]{  }$ for which exists when $x\leq \sqrt[  ]{ 10 }$ and $3<\sqrt[  ]{ 10 }$), $\therefore$ $f$ is differentiable and hence $h(x)$ is as well as it is a composition of continuous functions ($f$ and $h$ which is a composition of multiplication and addition). So we may use chain rule to find $h'(x)$ as such:
$$
h'(x)=(f(g(x)))'=f'(g(x))g'(x)=F(g(x))g'(x)=(2x+1)'\sqrt[  ]{ 100-(2x+1)^{4} }
$$
$$
h'(x)=2\sqrt[  ]{ 100-(2x+1)^{4} }
$$
- (d) A soft drink company has a $10, 000L$ industrial mixing tank filled with pure water. The tank is drained at a rate of $12 L\min^{-1}$ whilst a syrup solution containing $10 kg\,L^{-1}$ of sugar is pumped into the tank at a rate of $10 L \min ^{-1}$. Assuming that the mixture is instantly and uniformly mixed, formulate and solve an initial value problem to model the mass of sugar $y(t)$ in the tank after $t$ minutes of mixing for all $t ∈ [0, 5000]$. 
$$
V=10000-12t+10t=10000-2t:t_{max}=5000\qquad M=100t-12\left( \frac{M}{V} \right)t \implies M=\frac{100t}{1+\frac{12}{V}t}
$$
$$
=\frac{100t}{1+\frac{12t}{10000-2t}}=\frac{100t}{\frac{10000+10t}{10000-2t}}=\frac{100t(10000-2t)}{10000+10t}=\frac{10t(10000-2t)}{1000+t}
$$
