 [[1RA_Online.pdf]]

1. 
- (a) Let $f : \mathbb{R}  \mapsto  \mathbb{R}$. Define what it means that $\lim_{ x \to -\infty }f(x)=\infty$

Let $M,k\in \mathbb{R}$, where $M>0$ and $k<0$. The limit is defined as when $f(x)>M$ when $x<k$ for 

- (b)By using the definition of limit from part (a), prove that

We want to find that a $k$ exists for a given $M$ given in the definition above:
$$
f(x)=\sqrt[ 5 ]{ x^{2} }>M\impliedby x<-M^{\frac{5}{2}}
$$
$x<-M^{\frac{5}{2}}$ is in the form of $x<k$ giving a $k=-M^{\frac{5}{2}}$.
$$
x>k\implies k<\sqrt[ 2 ]{ M^{5} }
$$

- (c) Determine whether the following limits exist, and if so find their values. Justify your answers. You can use any of the results discussed in lectures, provided you clearly state what you are using.
	- (i) $$\lim_{ x \to 0 } \frac{(e^{ 5x }-1)\tan x}{\cos(2x)-1}$$
$$
\lim_{ x \to 0 } \frac{(e^{ 5x }-1)\tan x}{\cos(2x)-1}=\frac{(1-1)0}{1-1}=\frac{0}{0}
$$
This is in indeterminant form of $\frac{0}{0}$ and so we may now use L'Hopitals rule and chain rule:
$$
\lim_{ x \to x_{0} } \frac{f(x)}{g(x)}=\lim_{ x \to x_{0} } \frac{f'(x)}{g'(x)} 
$$
$$
\lim_{ x \to 0 } \frac{(e^{ 5x }-1)\tan x}{\cos(2x)-1}=\lim_{ x \to 0 }  \frac{e^{ 5x }\sec^{2}x- \sec^{2}x+5e^{ 5x }\tan x}{-2\sin (2x)}\to \frac{1(1)^{2}-(1)^{2}+5(1)(0)}{-2(0)}
$$
$$
\lim_{ x \to 0 }  \frac{e^{ 5x }\sec^{2}x- \sec^{2}x+5e^{ 5x }\tan x}{-2\sin (2x)} 
$$
$$
= \lim_{ x \to 0 } \frac{5e^{ 5x }\sec^{2}x+2e^{ 5x }\sec^{2}x\tan x-2\sec^{2}x\tan x+25e^{ 5x }\tan x+5e^{ 5x }\sec^{2}x}{-4\cos(2x)}
$$
$$
\to \frac{5+0-0+0+5}{-4}=- \frac{10}{4}=- \frac{5}{2}
$$
	- (ii) $$\lim_{ x \to \infty } \frac{3x^{3}+x^{2}+\sin (e^{ x })}{5x-8x^{3}+\arctan(\log x)}$$
$$
\lim_{ x \to \infty } \arctan (\log x) = \arctan(\lim_{ x \to \infty } \log x)\to \arctan(\infty)=\frac{\pi}{2}
$$
$$
\lim_{ x \to \infty } \sin(e^{ x })\geq -1 \forall x \in \mathbb{R}
$$
$$
\varepsilon>\lim_{ x \to \infty } \frac{3x^{3}+x^{2}+\sin (e^{ x })}{5x-8x^{3}+\arctan(\log x)}\geq \lim_{ x \to \infty } \frac{3x^{3}+x^{2}-1}{5x-8x^{3}+\frac{\pi}{2}} \forall x >2= \lim_{ x \to \infty } \frac{3+\frac{1}{x}-\frac{1}{x^{3}}}{\frac{5}{x^{2}}-8+\frac{\pi}{2x^{3}}}
$$
Using AoL:
$$
\lim_{ x \to \infty } \frac{3+\frac{1}{x}-\frac{1}{x^{3}}}{\frac{5}{x^{2}}-8+\frac{\pi}{2x^{3}}}\to \frac{3}{-8}
$$
- (d) Compute the derivative of the function $g : (0, ∞) → \mathbb{R}$ defined by $$g(x) = x^{\sin(x^{2})}$$ for all $x ∈ (0, ∞)$. Justify all the steps in your computations. You can use any of the results discussed in lectures, provided you clearly state what you are using
We will use the differential technique as followed below for ease and product rule for $\sin(x^{2})\ln x$ and chain rule when evaluating $(\sin(x^{2}))'$.
$$
g(x)=x^{\sin(x^{2})}\iff \ln(g)=\sin(x^{2})\ln x
$$
$$
(\ln(g))'= \frac{g'}{g}=\frac{\sin(x^{2})}{x}+2x\cos(x^{2})\ln x
$$
$$
g'=g\left( \frac{\sin(x^{2})}{x}+2x\cos(x^{2})\ln x \right)=x^{\sin(x^{2})}\left( \frac{\sin(x^{2})}{x}+2x\cos(x^{2})\ln x \right)
$$
2. 
- (a) Suppose that $P = \{0, 1, 2, 3\}$ and that $f : [0, 3] → \mathbb{R}$ is given by $$f(x):= \left\{ \begin{array}{} 4,  & \text{if } x = 0;  \\
x^{2} + 1, & \text{if } x ∈ (0, 3);  \\
12, & \text{if } x = 3.
\end{array} \right. $$Compute both the lower sum $L( f , P)$ and the upper sum $U( f , P)$.
$$
m_{i}:= \inf \{ f(x): x\in [x_{i-1},x] \}\qquad M_{i}:= \sup\{ f(x): x\in [x_{i-1},x] \}
$$
$$
L(f,P)=\sum^{i}_{i=0}m_{i}(x_{i}-x_{i-1})=0(1)+2(1)+5(1)=7
$$
$$
U(f,P)=\sum^{i}_{i=0}M_{i}(x_{i}-x_{i-1})=4(1)+5(1)+12(1)=21
$$
- (b) Suppose that $h : (0, 3) ∪ (3, π) → \mathbb{R}$ is given by $$h(x):=\left\{ \begin{array}{} 
x\sqrt[  ]{ 9 - x^{2} }, & \text{if } x ∈ (0, 3); \\
\sec^{6}(x) tan^{4}(x), &\text{if } x ∈ (3, π).
\end{array} \right. $$Find an antiderivative of $h$, showing all of your calculations. 

Let $a,b\in \mathbb{R}$ where $a>b$

Consider the antiderivative for $x \in (0,3)$ first. Observe it is in the form:
$$
c\cdot f'(g(x))g'(x)=(c\cdot f(g(x)))'
$$
where $g(x)=9-x^{2},\,g'(x)=-2x,\,f'(x)=\sqrt[  ]{ x }$, hence $f(x)=\frac{2}{3}x^{3/2}$ and $c=-\frac{1}{2}$
$$
\therefore\int ^{a}_{b} x\sqrt[  ]{ 9-x^{2} } \, dx = \left[ -\frac{1}{3}(9-x^{2})^{3/2} \right]^{a}_{b}=\left[ \frac{1}{3}(9-x^{2})^{3/2} \right]^{b}_{a}
$$
Now consider the antiderivative for $x \in(3,\pi)$
$$
\sec^{2}x=1+\tan ^{2}x\qquad u=\tan x\implies du=dx\sec^{2}x\qquad\int ^{a}_{b} \sec^{6}x\tan^{4}x \, dx 
$$
$$
=\int ^{a}_{b} (1+\tan ^{2}x)^{2}\tan^{4}x \,dx\sec^{2}x =\int ^{a}_{b} (1+u^{2})^{2}u^{4} \, du =\int ^{a}_{b}u^{4}+2u^{6}+u^{8}  \, du=\frac{u^{5}}{5}+\frac{2u^{7}}{7}+\frac{u^{9}}{9} 
$$
$$
=\left[ \tan^{5}x\left( \frac{1}{5}+\frac{2\tan ^{2}x}{7}+\frac{\tan^{4}x}{9} \right) \right]^{a}_{b}
$$
The antiderivative of $h(x)$ is then given by:
$$
h(x)=\left\{ \begin{matrix}
\left[ \frac{1}{3}(9-x^{2})^{3/2} \right]^{b}_{a}, &\text{if }a,b \in(0,3) \\
\left[ \tan^{5}x\left( \frac{1}{5}+\frac{2\tan ^{2}x}{7}+\frac{\tan^{4}x}{9} \right) \right]^{a}_{3}+ \left[\frac{1}{3}(9-x^{2})^{3/2} \right]^{b}_{3}, &\text{if }a\in(3,\pi),b \in(0,3) \\
\left[ \tan^{5}x\left( \frac{1}{5}+\frac{2\tan ^{2}x}{7}+\frac{\tan^{4}x}{9} \right) \right]^{a}_{b}, &\text{if }a,b \in(3,\pi) 
\end{matrix} \right. 
$$
- (c) Compute the improper integral $\int ^{4}_{0} \frac{x^{3}-2}{\left|x-1 \right|} \, dx$, showing all of your calculations, or prove that it is divergent. 
$$
\int ^{4}_{0} \frac{x^{3}-2}{\left|x-1 \right|} \, dx=\lim_{ \delta \to 0^{-} } \left( \int ^{4}_{1+\delta} \frac{x^{3}-2}{\left|x-1 \right|} \, dx+\int ^{1-\delta}_{0} \frac{x^{3}-2}{\left|x-1 \right|} \, dx \right)
$$
It is enough to prove that if one of these diverges, then the whole integral does:
$$
\lim_{ \delta \to 0^{-} }  \int ^{4}_{1+\delta} \frac{x^{3}-2}{\left|x-1 \right|} =\lim_{ \delta \to 0^{-} }  \int ^{4}_{1+\delta} \frac{x^{3}-2}{x-1 } =\int ^{4}_{1+\delta} x^{2}+x+1-\frac{1}{x-1} \, dx 
$$
$$
=\lim_{ \delta \to 0^{-} } \left[ \frac{x^{3}}{3}+\frac{x^{2}}{2}+x -\ln(x-1)\right]^{4}_{1+\delta}=\lim_{ \delta \to 0^{-} } \left[ \frac{x^{3}}{3}+\frac{x^{2}}{2}+x +\ln\left( \frac{1}{x-1} \right)\right]^{4}_{1+\delta}
$$
We will expand and use AoL:
$$
=\frac{64}{3}+8+4-\ln(3)-\lim_{ \delta \to 0^{-} } \left( \frac{(1+\delta)^{3}}{3}+\frac{(1+\delta)^{2}}{2}+(1+\delta)+\ln\left( \frac{1}{\delta} \right) \right)
$$
$$
=\frac{100}{3}-\ln (3)-\left( \frac{1}{3}+\frac{1}{2}+\ln(\infty) \right)=\frac{189}{6}-\ln(3)-\infty
$$
Hence this improper integral diverges.

- (d) Suppose that $a ∈ \mathbb{R} \ \{0\}$. Find a solution $y : [0, +∞) → \mathbb{R}$ of the initial value problem $y'-ay=x^{2},\qquad y(0)=5a$
$$
I=e^{ -ax }\implies (Iy)'=Iy'-aIy=Ix^{2} \implies Iy=\int ^{}_{} Ix^{2} \, dx
$$
$$
\int ^{}_{} x^{2}e^{-ax} \, dx =\frac{x^{2}e^{ -ax }}{-a}-\frac{1}{-a}\int ^{}_{} 2xe^{ -ax } \, dx =\frac{x^{2}e^{ -ax }}{-a}-\frac{1}{-a}\left( \frac{2xe^{ -ax }}{-a}-\frac{1}{-a}\int ^{}_{} 2e^{ -ax } \, dx  \right)
$$
$$
=-\frac{x^{2}e^{ -ax }}{a}- \frac{2xe^{ -ax }}{a^{2}}-\frac{2e^{ -ax }}{a^{3}}+C=Iy
$$
$$
\therefore y= -\frac{x^{2}}{a}-\frac{2x}{a^{2}}-\frac{2}{a^{3}}+\frac{C}{e^{ -ax }}
$$
$$
y(0)=5a=-\frac{2}{a^{3}}+C\therefore y= -\frac{x^{2}}{a}-\frac{2x}{a^{2}}-\frac{2}{a^{3}}+\frac{5a+\frac{2}{a^{3}}}{e^{ -ax }}
$$
3. 
- (a) Let $f : A → \mathbb{R}$, where $A ⊆ \mathbb{R}$, and let $c ∈ A$. Define what it means that $f$ is differentiable at $c$. 

The following limit exists:
$$
\lim_{ h \to 0 } \frac{f(c+h)-f(c)}{h} 
$$
And as $c$ was given arbitrarily as $c \in A$, the interval $A$ is entirely differentiable.

- (b) Let $g : (−π/6, π/6) → \mathbb{R}$ be defined by $$g(x) = \left\{ \begin{matrix}
\frac{\sin(x^{3})}{1-\cos(3x)} &\text{if } x \neq 0,  \\
0 & \text{if } x = 0.
\end{matrix} \right. $$By using the definition from part (a), prove that $g$ is differentiable at $0$, and determine the value of $g'(0)$. You can use any of the results discussed in lectures, provided you clearly state what you are using.

To prove that $g'(0)\exists$ we simply need to show that the limit from $(a)$ exists where $c=0$. Let 
$$
f(x)=\frac{\sin(x^{3})}{1-\cos(3x)}\qquad f(0)=\frac{0}{0}
$$
This is in indeterminant form $\frac{0}{0}$ so we may use L'Hopital's rule, along with chain rule and product rule:
$$
\lim_{ x \to 0 } \frac{\sin(x^{3})}{1-\cos(3x)}=\lim_{ x \to 0 } \frac{3x^{2}\cos(x^{3})}{3\sin(3x)}= \lim_{ x \to 0 } \frac{6x\cos(x^{3})-9x^{4}\sin(x^{3})}{9\cos(3x)}\to \frac{(0)(1)-9(0)(0)}{9(1)}=\frac{0}{1}=0
$$
Now let us now use this result in the definition:
$$
f'(0)=\lim_{ h \to 0 } \frac{f(0+h)-f(0)}{h} = \lim_{ h \to 0 } \frac{f(h)-f(0)}{h} = \lim_{ h \to 0 } \frac{f(0+h)-0}{h} = \lim_{ h \to 0 } \frac{ \frac{\sin(h^{3})}{1-\cos(3h)}}{h}\to\frac{0}{0}
$$
This is once again in indeterminant form $\frac{0}{0}$ from the previous result and we may use AoL and L'Hopital's rule.
$$
f'(0)=\lim_{ h \to 0 } \frac{ \frac{\sin(h^{3})}{1-\cos(3h)}}{h}=\lim_{ h \to 0 } \sin(h^{3})\lim_{ h \to 0 } \frac{h}{1-\cos(3h)}
$$
$$
 =\lim_{ h \to 0 } \sin(h^{3})\lim_{ h \to 0 }\frac{1}{3\sin(3h)}=\lim_{ h \to 0 } \sin(h^{3})\lim_{ h \to 0 }\frac{0}{9\cos(3h)}\to0
$$
Hence $g'(0)\exists$ and $g'(x)=0$.

- (c) Let $h$ be the real-valued function of a real variable defined by the formula $$h(x) = \sqrt[  ]{ \frac{x^{3}}{x^{2}-2} }$$
	- (i) Determine the domain of h according to the Domain Convention.
$$
h(x) = \sqrt[  ]{ \frac{x^{3}}{x^{2}-2} } \iff 0\leq\frac{x^{3}}{x^{2}-2} \qquad x \in \mathbb{R},\qquad x\geq\sqrt[  ]{ 2 }\qquad 0\geq x\geq-\sqrt[  ]{ 2 }
$$
	- (ii) Find $\inf h$ and $\sup h$, and determine whether $h$ has a maximum and/or a minimum.

We can use the property of square roots having the range of $x\geq0$, so by showing a root exists then we can show that $\inf(h)=0$ and that a minimum exists
$$
h(x)=\sqrt[  ]{ \frac{x^{3}}{x^{2}-2} }\geq 0\qquad x=0 \implies h(0)=0 \therefore \inf(h)=0
$$
For the $\sup(h)$ we can show it does not exist by showing that $h(x)$ is unbounded, specifically that for a $M>0\exists k>0$ where $M,k \in\mathbb{R}$ satisfying $h(x)>M$ where $x>k$.
$$
\sqrt[  ]{ \frac{x^{3}}{x^{2}-2} }>M \implies M^{2}< x+ \frac{2x}{x^{2}-2}=x\left( 1+ \frac{2}{x^{2}-2} \right)<x+10 \iff M-10<x \forall x>10 
$$
$$
x>k \therefore k= M-10
$$
We have hence proven that the $\sup(h)$ and maximum does not exist.
- 
	- (iii) Determine all the local minimum points of $h$
$$
h'(x)=\frac{1}{\sqrt{\frac{x^{3}}{x^{2}-2}}}\cdot\frac{1}{2}\cdot\left(\frac{3x^{2}}{x^{2}-2}-\frac{2x^{4}}{\left(x^{2}-2\right)^{2}}\right)=\sqrt[  ]{ \frac{x^{2}-2}{x^{3}} }\cdot\frac{1}{2}\cdot\left(\frac{3x^{2}(x^{2}-2)-2x^{4}}{\left(x^{2}-2\right)^{2}}\right)
$$
$$
=\left(\frac{3x^{2}(x^{2}-2)-2x^{4}}{2x^{\frac{3}{2}}\left(x^{2}-2\right)^{\frac{3}{2}}}\right)=(x^{2}-6)\left( \frac{x^{\frac{1}{2}}}{(x^{2}-2)^{\frac{3}{2}}} \right)\therefore x\neq \pm \sqrt[  ]{ 2 }\therefore 0\geq x>-\sqrt[  ]{ 2 } \cup x>\sqrt[  ]{ 2 }
$$
$$
h'(x)=0\therefore x=0,\sqrt[  ]{ 6 }
$$
$$
h(0)=0\therefore (0,0)\qquad h(\sqrt[  ]{ 6 })=\sqrt[  ]{ \frac{3\sqrt[  ]{ 6 }}{2} }\therefore \left( \sqrt[  ]{ 6 },\sqrt[  ]{ \frac{3\sqrt[  ]{ 6 }}{2} } \right)
$$
	- (iv) Determine whether $h$ is surjective (here the codomain of h is assumed to be $\mathbb{R}$)

No it is not as $h(x)\geq 0$ as the square root only gives the range of $\mathbb{R}^{+}$ which is a subset of the $\mathbb{R}$ $(\mathbb{R}^{+}\subseteq \mathbb{R})$. We can then write it as $\mathbb{R}^{+}=\text{range}(h) \subseteq \text{codom}(h)=\mathbb{R}$, satisfying surjection.

4. 
- (a) Suppose that $f : [1, 3] \mapsto \mathbb{R}$ is given by $$f(x):=\left\{ \begin{matrix}
4,&\text{if }x \in \mathbb{N}; \\
7,  & \text{if }x \notin \mathbb{N}.
\end{matrix} \right. $$
	- (i) Use Riemann's Criterion to prove that $f$ is integrable

Let $\delta>0$, let partition $P_{\varepsilon}:= \{ 1,1+\delta,2-\delta,2+\delta,3-\delta,3 \}=\{ x_{0},x_{1},x_{2},x_{3},x_{4},x_{5} \}$. Using this partition we only need to show that there exists a $P$ for $\varepsilon>0$ satisfying $U(f,P)-L(f,P)<\varepsilon$, where $\varepsilon \in \mathbb{R}$.
$$
M_{1}=7\quad M_{2}=7\quad M_{3}=7\quad M_{4}=7\quad M_{5}=7\quad m_{1}=4\quad m_{2}=7\quad m_{3}=4\quad m_{4}=7\quad m_{5}=4
$$
$$
U(f,P_{\varepsilon})= \sum^{5}_{i=1}M_{i}(x_{i}-x_{i-1})=7(\delta)+7(1-2\delta)+7(2\delta)+7(1-2\delta)+7(\delta)=14
$$
$$

L(f,P_{\varepsilon})= \sum^{5}_{i=1}M_{i}(x_{i}-x_{i-1})=4(\delta)+7(1-2\delta)+4(2\delta)+7(1-2\delta)+4(\delta)=14-12\delta
$$
$$
U(f,P_{\varepsilon})-L(f,P_{\varepsilon})=12\delta<\varepsilon 
$$
Choose $\varepsilon= 20\delta$. This satisfies Riemann's Criterion of integrability, and hence $f(x)$ is integrable.
- 
	- (ii) Use the definition of the integral to compute, with proof, the value of $\int ^{3}_{1} f$

$$
\lim_{ \delta \to 0 } U(f,P_{\varepsilon})\to 14 =\lim_{ \delta \to 0 } L(f,P_{\varepsilon})
$$
$$
\therefore U(f,P)=L(f,P)=14
$$
- (b) Suppose that $f : \mathbb{R} → \mathbb{R}$ is differentiable and that $F : [1, 10] → \mathbb{R}$ is given by $$F(x) := ∫ ^{3x^{4}}_{1} \sin ( f (t))\,dt$$for all $x ∈ [1, 10]$. Prove that F is differentiable, and find an expression for the derivative $F'(x)$ for all $x ∈ [1, 10]$, in terms of $f$ but which does not contain the integral or antiderivative symbol $∫$.

Lets first decompose $F(x)$ like such, $F(x)=G(h(x))$ where
$$
h(x)=3x^{4}\qquad G(x)=\int ^{x}_{1} \sin x \, dx 
$$
We know that $h(x)$ is integrable as it is continuous on $\mathbb{R}$, so we only need to show that $G(x)$ exists, and we can do this by proving that the integrand, $g(x)=\sin x$ is continuous. We know that trigonometric are continuous on $\mathbb{R}$ so thus $G(x)$ exists and it too is continuous. As $F(x)$ is a composition of continuous functions on the $\mathbb{R}$ we then know that $F(x)$ exists and as it is continuous on the $\mathbb{R}$ we then know that a derivative exists. We may then use chain rule to find $F'(x)=f$ as such:
$$
f=F'(x)=G'(h(x))h'(x)=\sin (3x^{4})\cdot 12x^{3}
$$
- (c) Suppose that $b ∈ R \setminus\{0\}$. Find a solution $y : [0, +∞) → \mathbb{R}$ of the initial value problem$$y'' − 4by' + 4b^{2}y = x^{2},\qquad y(0) = 0,\qquad y'(0) = \frac{1}{2b^{3}}$$
$$
y=y_{p}+p_{c}
$$
$$
y_{c}=Ae^{ \lambda_{1}x }+Be^{ \lambda_{2}x }\implies \lambda^{2}-4b\lambda+4b^{2}=0\iff\lambda =2
$$
As there is a repeat root we then change $y_{c}$ as such:
$$
y_{c}=Ae^{ 2\lambda }+Bxe^{ 2\lambda }
$$
$$
y_{p}=Cx^{2}+Dx+E\implies y'' − 4by' + 4b^{2}y = x^{2}=(2C)-4b(2Cx+D)+4b^{2}(Cx^{2}+Dx+E)
$$
$$
4b^{2}Cx^{2}+(D-8bC)x+(2C-4bD+4b^{2}E)=x^{2}
$$
$$
4b^{2}C=1\therefore C=\frac{1}{4b^{2}}\qquad D-8bC=0\therefore  D=\frac{2}{b}\qquad 2C-4bD+4b^{2}E=0\therefore E=8-\frac{1}{2b^{2}}
$$
$$
\therefore y=y_{c}+y_{p}= Ae^{ 2x }+Bxe^{ 2x }+ \frac{x^{2}}{4b^{2}}+\frac{2x}{b}+8-\frac{1}{2b^{2}}
$$
$$
y(0)=A+8-\frac{1}{2b^{2}}=0\therefore A=\frac{1}{2b^{2}}-8
$$
$$
\therefore y= \left( \frac{1}{2b^{2}}-8 \right) e^{ 2x }+Bxe^{ 2x }+ \frac{x^{2}}{4b^{2}}+\frac{2x}{b}+8-\frac{1}{2b^{2}}
$$
$$
y'(x)= \left( \frac{1}{b^{2}}-16+B \right) e^{ 2x }+2Bxe^{ 2x }+ \frac{x}{2b^{2}}+\frac{2}{b}
$$
$$
y'(0)= \left( \frac{1}{b^{2}}-16+B \right)+\frac{2}{b}= \frac{1}{2b ^{3}}\therefore B=\frac{1}{2b ^{3}} - \frac{1}{b^{2}} +16
$$
$$
\therefore y= \left( \frac{1}{2b^{2}}-8 \right) e^{ 2x }+\left( \frac{1}{2b ^{3}} - \frac{1}{b^{2}} +16 \right) xe^{ 2x }+ \frac{x^{2}}{4b^{2}}+\frac{2x}{b}+8-\frac{1}{2b^{2}}
$$