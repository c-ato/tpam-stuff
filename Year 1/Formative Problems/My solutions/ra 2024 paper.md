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