[[RA8.pdf]]

1. 
- (a) Prove that the function $f : [0, 1] → \mathbb{R}$ given for all $x ∈ [0, 1]$ by $$f(x):= \int ^{4x^{6}+3x^{2}}_{-1} e^{ 3t^{2} } \, dt $$ is differentiable and find its derivative in terms of elementary functions.

Let us prove for a simpler case:
$$
g(x)=\int ^{x}_{-1} e^{ 3t^{2} } \, dt \qquad G(x)=e^{ 3x^{2} }\qquad h(x)=4x^{6}+3x^{2}
$$
Let $G(x)=e^{ 3x^{2} }$. Observe that $G(x)$ is composed of elementary functions $e^{ x }$, $x^{2}$ and $3x$, all of which are continuous on $\mathbb{R}$ and hence interval of $[-1,x]$, where $x \in [0,1]$. So $G(x)$ is also continuous on this interval. Hence by the 1st FTC $g(x)$ is differentiable and has an antiderivative $g'(x)=G(x)$.

$f(x)$ is a composition of $g(x)$ and $h(x)$ ($f(x)=g(h(x))$, both of which are differentiable on the $\mathbb{R}$ so $f(x)$ is differentiable on $\mathbb{R}$  so an antiderivative $F(x)$ exists. So using chain rule we obtain:
$$
f'(x)=(g(h(x)))'=g'(h(x))h'(x)=e^{ 4x^{6}+3x^{2} }(24x^{5}+6x)
$$
- (b)
- (i)
$$
u=2x+1\qquad \frac{du}{2}=dx\qquad\int ^{}_{}  \frac{xe^{ 2x }}{(1+2x)^{2}} \,dx =  \int ^{}_{}  \frac{(u-1)}{2} \frac{e^{ u-1 }}{u^{2}}\, \frac{du}{2}=\frac{1}{4e}\int ^{}_{} \frac{e^{ u }}{u} -\frac{e^{u}}{u^{2}} \, du 
$$
Observe that the integrand is in the form $f'(x)g(x)+f(x)g'(x)$ where $f(x)=e^{ u }$ and $g(x)=\frac{1}{u}$, hence:
$$
\frac{1}{4e}\int ^{}_{} \frac{e^{ u }}{u} -\frac{e^{u}}{u^{2}} \, du =\frac{1}{4e} \frac{e^{ u }}{u}= \frac{1}{4e} \frac{e^{2x+1}}{(2x+1)}= \frac{1}{4} \frac{e^{ 2x }}{(2x+1)}
$$


- (ii)
$$
u=\sec (x)\qquad \frac{du}{\sec(x)}=\frac{du}{u}=\tan (x)\,dx\qquad\int ^{}_{} \tan^{9}(x) \, dx =\int ^{}_{} (\sec^{2}(x)-1)^{4} \tan (x) \, dx 
$$
$$
=\int \frac{(u^{2}-1)^{4}}{u}\,du=\int ^{}_{} u^{7}-4u^{5}+6u^{3}-4u+\frac{1}{u} \, du =\frac{1}{8}u^{8}-\frac{2}{3}u^{6}+\frac{3}{2}u^{4}-2u^{2}+\ln(u)
$$
$$
=\frac{1}{8}\sec^{8}(x)-\frac{2}{3}\sec^{6}(x)+\frac{3}{2}\sec^{4}(x)-2\sec^{2}(x)+\ln(\sec(x)))
$$

- (iii)

Observe that the 2nd term after decomposing is in the form $\frac{f'(x)}{f(x)}$ and the 3rd being the form of a standard $\tan ^{-1}(x)$ differential
$$
u=x^{2}+4\qquad \frac{du}{2x}=dx\int ^{}_{} \frac{x^{3}+4}{x^{2}+4} \, dx = \int ^{}_{} x-\frac{4x}{x^{2}+4} + \frac{4}{x^{2}+4}\, dx $$
$$
= \frac{1}{2}x^{2}-2\ln(x^{2}+4)+2\tan ^{-1}\left( \frac{x}{2} \right)
$$
- (c) Find the value of the following improper integrals or prove that they are divergent:
- (i)

Decompose the improper integral into two proper integrals took to a limit:
$$
\int_{-\infty}^{\infty} e^{ -9x } \, dx =\lim_{ t \to \infty } \left( \int ^{t}_{0} e^{ -9x } \, dx + \int ^{0}_{-t} e^{ -9x } \, dx \right)=\lim_{ t \to \infty } \left( \left[ \frac{e^{ -9x }}{9} \right]^{t}_{0}+\left[ \frac{e^{ -9x }}{9} \right]^{0}_{-t} \right) 
$$
Observe that the following then diverges:
$$
\lim_{ t \to \infty } \left( \frac{e^{ -9t }}{9}-\frac{1}{9}-\left( \frac{1}{9} - \frac{e^{ 9t }}{9} \right) \right)= \frac{1}{9} \lim_{ t \to \infty } (e^{ -9t }+e^{ 9t })=\frac{1}{9}(0+\infty)
$$
- (ii)
We start by separating around the singularity:
$$
\int ^{9}_{4} (x-7)^{-2} \, dx = \int ^{9}_{7} (x-7)^{-2} \, dx + \int ^{7}_{0} (x-7)^{-2} \, dx
$$
The upper part of the integrand is given by:
$$
  \lim_{ \delta \to 0^{+} }\int ^{9}_{7+\delta} (x-7)^{-2} \, dx  =\lim_{ \delta \to 0^{+} } [-(x-7)^{-1}]^{9}_{7+\delta}=\lim_{ \delta \to 0^{+} } (-(2)^{-1}+(\delta)^{-1})=-(2)^{-1}+\infty
$$
This improper integral is divergent.