[[Practice Questions 3 - 2024.pdf]]

1a) $f(x)=x^{2}$
$$
f'(x)=\lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h}=\lim_{ h \to 0 } \frac{x^{2}+2hx+h^{2}-x^{2}}{h}=\lim_{ h \to 0 } 2x+h
$$
$$
f'(x)=2x
$$
1b) $f(x)=e^{ x }$
$$
f'(x)= \lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h}=\lim_{ h \to 0 } \frac{e^{ x+h }-e^{ x }}{h}=\lim_{ h \to 0 } \frac{e^{ x }(e^{h}-1)}{h}=e^{ x }\lim_{ h \to 0 } \frac{1-e^{ h }}{h}
$$
$$
f'(x)=e^{ x }
$$
2)
As the function is even, and as $\exists f'(0)\implies \exists f(0)$ it follows that:
$$
f(x)=f(-x)\therefore \lim_{ x^{+} \to 0 } f(x) = \lim_{ x^{-} \to 0 } f(x) =f(0)
$$
If's a function is continuous then so its derivative will then follow:
$$
f'(x)=-f'(-x)\therefore f'(0)=-f'(0)\iff 2f'(0)=0\therefore f'(0)=0
$$
As it is even, it then follows that there will be a sign at $x=0$ (y-axis) to preserve symmetry.

3)
$$
f_{n}(x)=x^{n}\sin\left( \frac{1}{x} \right)\implies f_{n}'(x)=nx^{n-1}\sin \left( \frac{1}{x} \right)-x^{n-2}\cos\left( \frac{1}{x} \right)
$$

$$
n=0\qquad f_{0}(x)=\sin\left( \frac{1}{x} \right)
$$
$$
\lim_{ x \to 0 } \sin\left( \frac{1}{x} \right)\overset{ y= \frac{1}{x} }{ = } \lim_{ y \to \infty } \sin(y)
$$
Let $y=2z\pi$ and then consider $y=\left( 2z- \frac{1}{2} \right)\pi$ and or $y=\left( 2z+ \frac{1}{2} \right)\pi$, where $z\in \mathbb{N}$
$$
\lim_{ y \to \infty } \sin(y) \to 0,1,-1
$$
$\therefore$ cannot be continuous and $\therefore$ not differentiable, furthered by
$$
f'_{0}(x)=- \frac{\cos\left( \frac{1}{x} \right)}{x^{2}}\therefore x=0\text{ is not defined - not differentiable}
$$
$$
f'_{1}(x)=\sin\left( \frac{1}{x} \right)-\frac{\cos\left( \frac{1}{x} \right)}{x}\because x=0\text{ is not defined - not differentiable}
$$
$$
x\sin\left( \frac{1}{x} \right)\text{ is defined for all reals, $\therefore$ is continuous}
$$
$$
x^{2}\sin\left( \frac{1}{x} \right)\text{ is defined for all reals $\therefore$ is continuous}
$$
$$
f_{2}'(x)=2x\sin\left( \frac{1}{x} \right)-\cos\left( \frac{1}{x} \right) \text{ This is not defined for all reals (0) $\therefore$ is not differentiable everywhere}
$$
4a)
$$
f(x)=\frac{x}{\sin x}\implies f'(x)=\csc x(1-\cot x)
$$
$$
f'\left( \frac{\pi}{3} \right)= \frac{2}{\sqrt[  ]{ 3 }}\left( 1- \frac{1}{\sqrt[  ]{ 3 }} \right)=\frac{3-\sqrt[  ]{ 3 }}{6}
$$
4b)
$$
y=\sqrt[  ]{ 1+\sqrt[  ]{ x } }\implies \frac{dy}{dx}= \frac{1}{2\sqrt[  ]{ x }} \frac{1}{2\sqrt[  ]{ 1+\sqrt[  ]{ x } }}= \frac{1}{4\sqrt[  ]{ x+x\sqrt[  ]{ x } }}
$$
5a)
$$
\frac{x^{2}}{3}+\frac{y^{2}}{6}=1 \implies \frac{2x}{3}+\frac{y}{3} \frac{dy}{dx}=0\therefore \frac{dy}{dx}=- \frac{2x}{y}
$$
$$
\frac{x^{2}}{3}+\frac{y^{2}}{6}=1\overset{ x=\frac{1}{4} }{ \implies } y=\pm \sqrt[  ]{ \frac{47}{8} }\implies \frac{dy}{dx}=\mp\sqrt[  ]{ \frac{2}{47} }
$$
5b)
$$
x^{\cos x}\implies \frac{d}{dx}(\cos x\ln x)= \frac{\cos x}{x}- \sin x\ln x\implies \frac{d}{dx}(x^{\cos x})=\left( \frac{\cos x}{x}-\sin x\ln x \right)x^{\cos x}
$$
6
First step:
$$
(\sin x)'=\cos x=\sin \left( x+\frac{\pi}{2} \right)
$$
$$
(\cos x)'=-\sin (x)=\sin(x+\pi)=\cos\left( x+\frac{\pi}{2} \right)
$$
Given that at least $P(k)$ and $Q(k)$ is true:
$$
P(k)=(\sin x)^{(k)}=\sin\left( x+ \frac{n\pi}{2} \right)\qquad Q(k)=(\cos x)^{(k)}=\cos\left( x+ \frac{n\pi}{2} \right)
$$
Then considering $k+1$
$$
(\sin x)^{(k+1)}=\frac{d}{dx}((\sin)^{(k)})=\frac{d}{dx}\left( \sin\left( x+ \frac{k\pi}{2} \right) \right)=\cos\left( x+\frac{k\pi}{2} \right)=\sin\left( x+ \frac{(k+1)\pi}{2} \right)
$$
$$
(\cos x)^{(k+1)}=\frac{d}{dx}\left( \left( \cos x \right) ^{(k)} \right) =\frac{d}{dx}\left( \cos\left( x+ \frac{k\pi}{2} \right) \right)=-\sin\left( x+\frac{k\pi}{2} \right)=\cos\left( x+ \frac{(k+1)\pi}{2} \right)
$$
7.1)
$$
y= \frac{x^{2}+4x+3}{\sqrt[  ]{ x }}\implies \ln y=\ln(x^{2}+4x+3)-\ln (\sqrt[  ]{ x })\implies \frac{dy}{dx}=y\left( \frac{2x+4}{x^{2}+4x+3}-\frac{1}{2\sqrt[  ]{ x }} \right)
$$
$$
= \frac{2x+4}{\sqrt[  ]{ x }}- \frac{x^{2}+4x+3}{2x}
$$
7.2)
$$
g(x)=(x^{2}+1)^{3}(x^{2}+2)^{6}\implies g'(x)=6x(x^{2}+1)^{2}(x^{2}+2)^{6}+12x(x^{2}+1)^{3}(x^{2}+2)^{5}
$$
7.3)
$$
B(u)=(u^{3}+1)(2u^{2}-u-6)\implies B'(u)=3u^{2}(2u^{2}-u-6)+(4u-1)(u^{3}+1)
$$
$$
=10u^{4}-6u^{3}-6u^{2}+4u-1
$$
7.4)
$$
g(t)=(t+1)^{2/3}(2t^{2}-1)^{3}\implies g'(t)=\frac{2(2t^{2}-1)^{3}}{3(t+1)^{1/3}}+12t(t+1)^{2/3}(2t^{2}-1)^{2}
$$
7.5)
$$
y=\frac{1}{t^{3}-2t^{2}+1}\implies \frac{dy}{dt}=-\frac{3t^{2}-6t}{(t^{3}-2t^{2}+1)^{2}}
$$
7.6)
$$
f(x)= \sqrt[  ]{ \frac{1+\sin x}{1+\cos x} }=f(x)^{2}= \frac{1+\sin x}{1+\cos x}\implies 2f'(x)f(x)= \frac{\cos x+\cos ^{2}x+\sin x+\sin ^{2}x}{(1+\cos x)^{2}}
$$
$$
\frac{1+\sin x+\cos x}{2(1+\cos x)^{2}} \sqrt[  ]{ \frac{1+\cos x}{1+\sin x} }
$$
7.7)
$$
y=\frac{x}{x+\frac{2}{x}}=\frac{x^{2}}{x^{2}+2}\implies \frac{dy}{dx}=\frac{2x(x^{2}+2)-2x(x^{2})}{(x^{2}+2)^{2}}=\frac{4x}{(x^{2}+2)^{2}}
$$
7.8)
$$
f(x)=\sqrt[  ]{ x+\sqrt[  ]{ x+\sqrt[  ]{ x } } }\implies f'(x)= \frac{1}{2\sqrt[  ]{ x+\sqrt[  ]{ x+\sqrt[  ]{ x } } }} \frac{1}{2\sqrt[  ]{ x+\sqrt[  ]{ x } }} \frac{1}{2\sqrt[  ]{ x }}
$$
$$
=\frac{1}{8\sqrt[  ]{ x }\sqrt[  ]{ x+\sqrt[  ]{ x } }\sqrt[  ]{ x+\sqrt[  ]{ x+\sqrt[  ]{ x } } }}
$$
7.9)
$$
y=\frac{t\sin t}{1+t}\implies \frac{dy}{dt}= \frac{(\sin t+t\cos t)(1+t)-t\sin t}{(1+t)^{2}}= \frac{\sin t+t\cos t+t^{2}\cos t}{(1+t)^{2}}
$$
7.10)
$$
y=(x+(x+\sin ^{2}x)^{3})^{4}\implies \frac{dy}{dx}=4(1+3(1+2\sin x\cos x)(x+\sin ^{2}x)^{2})(x+(x+\sin ^{2}x)^{3})^{3}
$$
7.11)
$$
y=x\sin x\tan x=\sin x\tan x+x\sin x+x\tan x\sec^{}x
$$
7.12)
$$
y=\tan(\sec(\cos x))\implies \frac{dy}{dx}=\sin x\tan(\cos x)\sec(\cos x)\sec^{2}(\sec(\cos x))
$$
8a)
$$
y=\sqrt[  ]{ x }e^{ x^{2} -x}(x+1)^{2/3}
$$
$$
\ln(y)=\ln (\sqrt[  ]{ x })+x^{2}-x+\frac{2}{3}\ln (x+1)\implies \frac{dy}{dx}=\sqrt[  ]{ x }e^{ x^{2} -x}(x+1)^{2/3}\left( \frac{1}{2x} +2x-1+\frac{2}{3(x+1)}\right)
$$
$$
\frac{dy}{dx}=\frac{e^{ x^{2} -x}(x+1)^{2/3}}{2\sqrt[  ]{ x }} +(2x-1)\sqrt[  ]{ x }e^{ x^{2} -x}(x+1)^{2/3}+\frac{2\sqrt[  ]{ x }e^{ x^{2} -x}}{3(x+1)^{1/3}}
$$
8b)
$$
y=x^{x}\implies \frac{dy}{dx}=(1+\ln x)x^{x}
$$
8c)
$$
y=\sin(x^{x})\implies \frac{dy}{dx}=(1+\ln x)x^{x}\cos(x^{x})
$$
8d)
$$
y=x^{\sin x}\implies \frac{dy}{dx}=\left( \frac{\sin x}{x}+\ln x\cos x \right)x^{\sin x}
$$
8e)
$$
y=(\sin x)^{\ln x}\implies \frac{dy}{dx}=\left( \frac{\ln(\sin x)}{x}+\cot x\ln x \right)(\sin x)^{\ln x}
$$
8f)
$$
y=(\ln x)^{\sin x}\implies \frac{dy}{dx}=\left( \frac{\sin x}{x\ln x}+ \ln \ln x\cos x\right)(\ln \ln x)^{\sin x}
$$
9)
$$
x^{y}=y^{x}\implies y\ln x=x\ln y\implies \frac{y}{x}+ \frac{dy}{dx}\ln x=\frac{x}{y} \frac{dy}{dx}+\ln y\implies \frac{dy}{dx}=\frac{\frac{y}{x}-\ln y}{\frac{x}{y}-\ln x}
$$
10)
Suppose that $f(x)=C,\forall x\in \mathbb{R}$ this means $f(x)$ is continuous, we may now use the definition of a derivative:
$$
f'(x)= \lim_{ y \to x } \frac{f(x)-f(y)}{x-y}=\lim_{ y \to x } \frac{C-C}{x-y}\overset{ x-y=h }{ = }\lim_{ h \to 0 } \frac{0}{h}=\lim_{ h \to 0 } 0=0\therefore |f(x)-f(y)|\leq|x-y|
$$
$$
\implies|f(x)-f(y)|\leq|x-y|^{\alpha},\forall\alpha\geq1
$$
Now consider:
$$
0=f'(x)= \lim_{ h \to 0 } \left| \frac{f(x+h)-f(x)}{h} \right| \leq \lim_{ h \to 0 } \left| \frac{h^{\alpha}}{h} \right| =0\therefore \alpha>1
$$
11)
Let $0<\epsilon\in \mathbb{R}$
$$
\left| f(a,b) \right| > \epsilon
$$
12)
$$
\frac{\tan x-x}{x^{2}}=\frac{\sec^{2}x-1}{2x}= \tan x\sec^{2}x=0
$$
Using the definition of a derivative and then taking the limit using L'Hopitals rule:
$$
f'(x)=\lim_{ h \to 0 } \frac{f(x+h)-f(x)}{h}\overset{ x=0 }{ \underset{}{ \implies } } \lim_{ h \to 0 }  \frac{\tanh-h}{h^{3}}= \lim_{ h \to 0 } \frac{\sec^{2}h-1}{3h^{2}}= \frac{1}{3} \lim_{ h \to 0 }  \frac{\tan ^{2}h}{h^{2}} 
$$
$$
= \frac{1}{3} \lim_{ h \to 0 }  \frac{\sin ^{2}h}{h^{2}\cos h}\to \frac{1}{3}
$$
$\therefore$ where the derivative exists, the function is continuous at $x=0$

13a)
$$
\lim_{ x \to -1 }  \frac{x^{2}-1}{\sin(1+x)}= \lim_{ x \to -1 }  \frac{2x}{\cos(1+x)}\to-2
$$
13b)
$$
\lim_{ x \to 0 } \frac{k^{x}-1}{x}=\lim_{ x \to 0 } \frac{k^{x}\ln k}{1}\to\ln k
$$
13c)
$$
\lim_{ x \to 0 } \frac{x\sin x}{1-\cos x}=\lim_{ x \to 0 } \frac{\sin x+x\cos x}{\sin x}=\lim_{ x \to 0 } \frac{2\cos x-x\sin x}{\cos x}\to2
$$
13d)
$$
\lim_{ x \to 0 } \frac{e^{ x }-1-x}{x^{2}}=\lim_{ x \to 0 } \frac{e^{ x }-1}{2x}=\frac{1}{2}\lim_{ x \to 0 } \frac{e^{ x }-1}{x}\to \frac{1}{2}
$$
14a)
$$
x^{2}-4xy+y^{2}=4\implies 2x-4y-4x \frac{dy}{dx}+2y \frac{dy}{dx}=0\iff \frac{dy}{dx}= \frac{2x-4y}{4x-2y}= \frac{x-2y}{2x-y}
$$
14b)
$$
\cos(xy)=x \sin y\implies -y\sin(xy)-\frac{dy}{dx}\sin(xy)=1+\frac{dy}{dx}\cos y\iff \frac{dy}{dx}=-\frac{y\sin(xy)+1}{\cos y+\sin(xy)}
$$
14c)
$$
\tan\left( \frac{x}{y} \right)=x+y\implies \frac{\sec^{2}\left( \frac{x}{y} \right)}{y}-\frac{x\sec^{2}\left( \frac{x}{y} \right)}{y^{2}} \frac{dy}{dx}=1+\frac{dy}{dx}\iff \frac{dy}{dx}= \frac{\frac{\sec^{2}\left( \frac{x}{y} \right)-y}{y}}{\frac{x\sec^{2}\left( \frac{x}{y} \right)+y^{2}}{y^{2}}}
$$
$$
=\frac{y\left( \sec^{2}\left( \frac{x}{y} \right)-y \right)}{x\sec^{2}\left( \frac{x}{y} \right)+y^{2}}
$$
15)
$$
\frac{x^{2}}{a^{2}}+ \frac{y^{2}}{b^{2}}=1\implies \frac{dy}{dx}= -\frac{b^{2}x}{a^{2}y}
$$
$$
\frac{(y-y_{0})}{(x-x_{0})}= -\frac{b^{2}x_{0}}{a^{2}y_{0}}\implies 0 = \frac{(y-y_{0})y_{0}}{b^{2}}+\frac{(x-x_{0})x_{0}}{b^{2}}=\frac{xx_{0}}{a^{2}}+ \frac{yy_{0}}{b^{2}}\underbrace{ -\frac{x_{0}^{2}}{a^{2}}- \frac{y_{0}^{2}}{b^{2}} }_{ -1 }
$$
$$
\implies \frac{xx_{0}}{a^{2}}+ \frac{yy_{0}}{b^{2}} = 1
$$
16)
$$
\frac{dx}{dt}=1\implies x=t+\overset{ 0 }{ c }\implies y=\sqrt[  ]{ 100-x^{2} }=\sqrt[  ]{ 100-t^{2} }\implies \frac{dy}{dt}=-\frac{t}{\sqrt[  ]{ 100-t^{2} }}
$$
$$
x=6\implies t=6\implies \frac{dy}{dt}= -\frac{3}{4}
$$
17)
$$
\frac{dx}{dt}=4\implies x=4t+\overset{ 0 }{ c }\qquad \tan \theta= \frac{x}{20}\implies \theta = \tan^{-1}\left( \frac{x}{20} \right) \implies\frac{d\theta}{dt} = \frac{20}{x^{2}+400} \overset{ 4 }{ \frac{dx}{dt} }
$$
$$
\overset{ x=15 }{ \implies }\frac{d\theta}{dt} = \frac{80}{x^{2}+400} = \frac{16}{125}
$$
18)
$$
A_{C}=\pi r_{C}^{2}\qquad A_{S}=r_{S}^{2}
$$
$$
A_{C}+A_{S}=\pi r_{C}^{2}+r_{S}^{2}=A_{T}\qquad 2\pi r_{C}+4r_{S}=L\implies r_{S} = \frac{L-2\pi r_{C}}{4} \implies r_{S}^{2} = \frac{(L-2\pi r_{C})^{2}}{16}
$$
$$
\pi r_{C}^{2}+r_{S}^{2}=\pi r_{C}^{2}+ \frac{(L-2\pi r_{C})^{2}}{16}=\frac{16\pi r_{C}^{2}+L^{2}-4L\pi r_{C}+4\pi^{2} r_{C}^{2}}{16}
$$
$$
\frac{(16\pi +4\pi^{2})r_{C}^{2}-4L\pi r_{C}+L^{2}}{16}=A_{T}\qquad(A_{T})'=0=\left( \frac{\pi^{2}}{2}+ 2\pi \right)r_{C}- \frac{L\pi}{2}\implies r_{C}= \frac{L}{\pi+4}
$$