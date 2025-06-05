[[A34930_LCRealAnalysis_QP_Main2024.pdf]]

1. 
- (a) Let $f: \mathbb{R} \to \mathbb{R}$ be a function and let $\alpha,\ell \in \mathbb{R}$
	- (i) Give the definition of the limit$$\lim_{ x \to \alpha } f(x)=\ell$$
Let $\varepsilon>0(\in \mathbb{R})$ so that $\delta>0(\in \mathbb{R})$ s.t. $\left| x-\alpha \right|<\varepsilon$ and $\left| f(x)-f(\alpha) \right|<\delta$
- 
	- (ii) By directly using the definition of limit from (i), show that $$\lim_{ x \to 1 } 4x+96=100$$
$$
\left| x-1 \right|<\varepsilon\qquad \left| (4x+96)-100 \right|=\left| 4x-4 \right|=4\left| x-1 \right|<\delta 
$$
We can choose a delta $\delta=4\varepsilon$. Hence the limit exists and is true.

- (b) Let $f : \mathbb{R} → \mathbb{R}$ be a differentiable function and let $α ∈ \mathbb{R}$
	- (i) Define $f'(\alpha)$, the derivative of $f$ at $\alpha$.
$$
f'(\alpha)=\lim_{ h \to 0} = \frac{f(\alpha+h)-f(\alpha)}{h}
$$
- 
	- (ii) By directly using the definition of derivative from (i), find the derivative of the function $f(x)=x^{3}$ at the point $x=2$.
$$
f'(x)=\lim_{ h \to 0 } \frac{(x+h)^{3}-x^{3}}{h}=\lim_{ h \to 0 } \frac{3x^{2}h+3xh^{2}+h^{3}}{h}=\lim_{ h \to 0 } 3x^{2}+3xh+h\to 3x^{2}
$$
$$
f'(2)=3\cdot 2^{2}=12
$$
- (c) Find the following limits and justify your answers. You can use any of the results discussed in lectures, provided you clearly state what you are using.
	- (i) $$\lim_{ x \to 0 } \frac{\sin 2x}{3x}$$
$$
\lim_{ x \to 0 } \frac{\sin 2x}{3x}\to \frac{0}{0}\therefore \lim_{ x \to 0 } \frac{\sin 2x}{3x}=\lim_{ x \to 0 } \frac{2\cos 2x}{3}\to \frac{2}{3}
$$
- 
	- (ii) $$\lim_{ x \to 1 } \frac{x}{3x^{2}-2x+4}\to \frac{1}{5} $$
- (d) Find the derivatives of the following functions.
	- (i) $f (x) = 3x^{3} + 2x^{2} − 6x + 1$
$$
f'(x)=9x^{2}+4x-6
$$
- 
	- (ii) $f (x) = \ln(2x + 3)$ for $x > 0$.
$$
f'(x)= \frac{2}{2x+3}
$$
2. Suppose that $-\infty<a<b<\infty$
- (a) Is the function $f:[a,b]\to \mathbb{R}$ $$f(x):=\left\{ \begin{matrix}5,  & \text{if }x \in \mathbb{Q} \\9,  & \text{if }x \notin \mathbb{Q}\end{matrix} \right. $$integrable? Prove your answer.

Between any 2 numbers there exists infinitely many rational and irrational numbers so hence $\bar{\int   \, }f\,dx\neq  \underline{\int} ^{}_{}f  \, dx$ regardless of any $P$ so this is not integrable.

- (b) State Riemann’s Integrability Criterion for a bounded function $g:[a,b]\to [0,\infty)$.
$$
\int ^{}_{} g \exists \iff U(f,P)-L(f,P)<\varepsilon
$$
- (c) Use the Fundamental Theorem of Calculus, or otherwise, to prove that any continuous function $h:[a,b]\to \mathbb{R}$ has an antiderivative. 

Let $H=\int ^{}_{} h$. Suppose that $H$ exists, since $h$ is continuous on $[a,b]$ so $H'(=h)$ exists and hence $H$ exists

- (d) Find $\int ^{}_{} \sin^{6}x\cos ^{3}x \, dx$ in terms of elementary functions.
$$
u= \sin x\implies du= dx\cos x\qquad \int ^{}_{} \sin^{6}x\cos ^{3}x \, dx=\int ^{}_{} u^{6}(1-u^{2}) \, du = \frac{u^{7}}{7} - \frac{u^{9}}{9}
$$
$$
= \frac{\sin^{7}x}{7}- \frac{\sin^{9}x}{9}
$$
- (e) Compute $\int ^{2}_{1} \frac{1}{x^{2}\sqrt[  ]{ x^{2}+9 }} \, dx$.
$$
x=3\tan u\implies dx=3du\sec^{2}x\qquad\int ^{2}_{1} \frac{1}{x^{2}\sqrt[  ]{ x^{2}+9 }} \, dx= \int ^{a}_{b} \frac{3\sec^{2}u}{3\tan ^{2}u\sec u} \, du=\int ^{a}_{b} \cot u \csc u \, du
$$
$$
=\left[ -\csc u \right] ^{a}_{b}=\left[ -\csc \left( \tan ^{-1} \frac{x}{3} \right)  \right] ^{2}_{1}=1.359\dots
$$
- (f) Find a solution $y:[1,\infty)\to \mathbb{R}$ of the differential equation $y''+2y'+5y=4x$
$$
y_{c}=Ae^{ \lambda x }\implies \lambda^{2}+2\lambda+5=0 \implies \lambda=-1 \pm \frac{\sqrt[  ]{ 4-20 }}{2}=-1\pm 2i
$$
$$
\therefore y_{c}= e^{ (-1\pm 2i)x }=Ae^{ -x }\cos 2x +Be^{ -x }\sin x\qquad y_{p}= \frac{4}{5}x-\frac{8}{25}
$$
$$
y=Ae^{ -x }\cos 2x +Be^{ -x }\sin x+ \frac{4}{5}x-\frac{8}{25}
$$
3. 
- (a) Use L’Hopital’s rule to find the following limits when it applies:
	- (i) $\lim_{ x \to 0 } \frac{1-\cos x}{x^{2}}$
$$
\lim_{ x \to 0 } \frac{1-\cos x}{x^{2}}\to \frac{0}{0}\therefore\lim_{ x \to 0 } \frac{1-\cos x}{x^{2}}=\lim_{ x \to 0 }  \frac{\sin x}{2x}=\lim_{ x \to 0 }  \frac{\cos x}{2}\to \frac{1}{2}
$$
- 
	- (ii) $\lim_{ x \to 0^{+} }x^{0.001}\ln x$
$$
\lim_{ x \to 0^{+} }x^{0.001}\ln x\to 0\cdot -\infty \therefore \lim_{ x \to 0^{+} }x^{0.001}\ln x=\lim_{ x \to 0^{+} } \frac{\ln x}{x^{-0.001}}=\lim_{ x \to 0^{+} } \frac{\frac{1}{x}}{-0.001\cdot x^{-1.001}}=\lim_{ x \to 0^{+} }- \frac{x^{0.001}}{0.001}=0
$$
- 
	- (iiI) $\lim_{ x \to \infty }\left( \frac{4^{1/x}+9^{1/x}}{2} \right)^{x}$
$$
\lim_{ x \to \infty }\left( \frac{4^{1/x}+9^{1/x}}{2} \right)^{x}=\lim_{ x \to \infty } e^{ x\ln\left(  \frac{4^{1/x}+9^{1/x}}{2} \right)  }= e^{ \lim_{ x \to \infty } x\ln\left(  \frac{4^{1/x}+9^{1/x}}{2} \right)  }
$$
$$
\lim_{ x \to \infty } x\ln\left(  \frac{4^{1/x}+9^{1/x}}{2} \right)=\lim_{ x \to \infty } \frac{\ln\left(  \frac{4^{1/x}+9^{1/x}}{2} \right)}{x^{-1}}\to \frac{0}{0}\therefore \lim_{ x \to \infty } \frac{\left( - \frac{1}{x^{2}} \right)(4^{1/x}\ln 4+9^{1/x}\ln 9)\left( \frac{2}{4^{1/x}+9^{1/x}} \right)}{-\frac{1}{x^{2}}}
$$
$$
=\lim_{ x \to \infty } (4^{1/x}\ln 4+9^{1/x}\ln 9)\left( \frac{2}{4^{1/x}+9^{1/x}} \right)\to 2\ln 2+2\ln 3
$$
- (b) Let $f : [1, 3] → \mathbb{R}$ be a function such that $$\left| f(x)-f(y) \right|\leq 100\left| x-y \right|^{1.001}$$
for all $x,y\in [1,3]$. Provice that $f$ is a constant function. (Hint: first show $f'(x)=0$).
$$
f'(x)=\lim_{ \alpha \to x } \frac{f(x)-f(\alpha)}{x-\alpha}\qquad y=\alpha\implies \left| f'(x) \right|= \left|\lim_{ y \to x } \frac{f(x)-f(y)}{x-y} \right|
$$
$$
\lim_{ y \to x} \left| f(x)-f(y) \right|=\left| f'(x) \right| \lim_{ y \to x } \left| x-y \right|\leq \lim_{ y \to x } 100 \left| x-y \right|^{1.001}\to0
$$
$$
\therefore 0\leq \left| f'(x) \right|\leq 0 \therefore f'(x)=0
$$
- (c) Let $f : \mathbb{R} \setminus \{0\} → \mathbb{R}$ be the function defined by $$f(x)=\frac{1-2x}{x^{2}}+1$$for all $x \in \mathbb{R}\setminus \{ 0 \}$. Find and determine the nature (i.e. local minima or local maxima) of the stationary points of $f$ . Justify any assertions that you make. 
$$
f'(x)=\frac{-2x^{2}-2x(1-2x)}{x^{4}}=\frac{2x-2}{x^{3}}=0 \iff x=1
$$
$$
f''(x)=\frac{2x^{3}-3x^{2}(2x-2)}{x^{6}}=\frac{6-4x}{x^{4}}\qquad f''(1)=2>0 \therefore \text{minima}
$$
- (d) Given $c ∈ \mathbb{R}$, prove that there is at most one solution to the equation$$x^{3}-4x+c=0$$on the interval [0, 1]. 
$$
f(x)=x^{3}-4x+c=0\qquad f'(x)=3x^{2}-4 =0 \qquad f':[0,1]\to[-4,-1]<0\forall x \in[0,1]
$$
$\therefore$ strictly monotonic on interval. So if the curve does not pass the $x$-axis in the interval then there is no solution and this is $\leq1$ solution. If there is a solution (passes $x$-axis )in this interval then as it is a monotonic and cannot have another solution (pass the $x$-axis again as this requires increasing).

4. 
- (a) Find $\int ^{}_{}  \frac{4x^{2}+x+10}{x^{3}-x^{2}+4x-4} \, dx$ in terms of elementary functions.
$$
\int ^{}_{}  \frac{4x^{2}+x+10}{x^{3}-x^{2}+4x-4} \, dx=\int ^{}_{} \frac{Ax+B}{x^{2}+4}+ \frac{C}{x-1} \, dx 
$$
$$
4x^{2}+x+10=(Ax+B)(x-1)+C(x^{2}+4)\qquad C=3\qquad B=2\qquad A=1
$$
$$
\int ^{}_{} \frac{x+2}{x^{2}+4}+ \frac{3}{x-1} \, dx =\frac{1}{2}\ln(x^{2}+4)+\tan ^{-1} \frac{x}{2}+3\ln(x-1)
$$
- (d) Suppose that $g : [0, π] → \mathbb{R}$ is given by$$g(x):=\int ^{2x\cos ^{2}(3x)}_{0} \sin(t^{2}) \, dt\qquad\text{for all }x\in[0,\pi] $$Prove that $g$ is differentiable and find its derivative $g'$ in terms of elementary functions.

Let $H(x)=\int ^{x}_{} \sin(t^{2}) \, dt,\,h(x)=H'(x)=\sin(x^{2}),\,f(x)=2x\cos ^{2}(3x)$ and $g(x)=H(f(x))$. $h(x)$ is composed of continuous functions and is thus continuous so $H'$ exists and $H$. $f$ is also composed of elementary continuous functions, this then means that $g$ exists as it is a composition of them. We may then use chain rule:
$$
g'(x)=(H(f(x)))'=H'(f(x))f'(x)=\sin((2x\cos ^{2}(3x))^{2})(2\cos ^{2}(3x)-6\cos(3x)\sin(3x))
$$
$$
=\sin(4x^{2}\cos ^{4}(3x))(2\cos ^{2}(3x)-6\cos(3x)\sin(3x)
$$
