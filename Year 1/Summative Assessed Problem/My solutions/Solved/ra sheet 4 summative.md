[[ra sheet 4 summative]]

\section{Find the derivatives of the following functions according to the definition, where they exist.}

\subsection{$f(x)=x^{3}$}

$$
f'(x)=\lim_{ h \to 0} \frac{f(x+h)-f(x)}{h} =\lim_{ h \to 0 } \frac{(x+h)^{3}-(x)^{3}}{h}
$$
$$
=\lim_{ h \to 0 } \frac{(x^{3}+3hx^{2}+3h^{2}x+h^{3})-(x^{3})}{h}=\lim_{ h \to 0 } \frac{3hx^{2}+3h^{2}x+h^{3}}{h}=\lim_{ h \to 0 } (3x^{2}+3hx+h^{2})=3x^{2}
$$
$$
\therefore f(x)=x^{3}\implies f'(x)=3x^{2}$$

\subsection{$f(x)=\cos x$}

$$
f'(x)=\lim_{ h \to 0} \frac{f(x+h)-f(x)}{h} =\lim_{ h \to 0 } \frac{\cos(x+h)-\cos(x)}{h}=\lim_{ h \to 0 } \frac{(\cos x \cos h - \sin x \sin h) -\cos(x)}{h}
$$
$$
=\lim_{ h \to 0 } \frac{\cos x \cos h-\cos x - \sin x \sin h }{h}=\lim_{ h \to 0 } \frac{(\cos h-1)}{h}-\sin x\lim_{ h \to 0 } \frac{\sin h}{h}=0-\sin x
$$
$$
\therefore f(x)=\cos x\implies f'(x)=-\sin x
$$

\section{Find the derivatives of the following functions. Detailed computation is needed.}

\subsection{$f(x)=2x^{3}+5x-1$}

Following that $(\lambda f + \mu g)′(x) = \lambda f ′(x) + \mu g′(x)$ and $f(x)=x^{n}\implies f'(x)= nx^{n-1}$ and derivative of a constant is 0.
$$
f'(x)=(2x^{3})'+(5x)'-(1)'=6x^{2}+5
$$

\subsection{$f(x)=x\ln x$}

Following that $(\ln x)'=\frac{1}{x}$ and $( g)′(x) = f ′(x)g(x) + f (x)g′(x)$ (product rule).
$$
f'(x)=x(\ln x)'+(x)'\ln x=1+\ln x
$$

\subsection{$f(x)=\ln(x^{2}+1)$}

Following that $(g(f (x)))′ = g′(f (x))f ′(x)$ (chain rule) and $(\ln x)'=\frac{1}{x}$. 
$$
f'(x)=\frac{1}{x^{2}+1}(x^{2}+1)'=\frac{2x}{x^{2}+1}
$$

\subsection{$f(x)=\frac{(x-1)(x-2)}{x^{\frac{1}{3}}}$}

Following $\left( \frac{f}{g} \right)'= \frac{f'(x)g(x)-f(x)g'(x)}{(g(x))^{2}}$
$$
f(x)= \frac{x^{2}-3x+2}{x^{\frac{1}{3}}}
$$
$$
f'(x)= \frac{(x^{2}-3x+2)'\left( x^{\frac{1}{3}} \right)-(x^{2}-3x+2)\left( x^{\frac{1}{3}} \right)'}{\left( x^{\frac{1}{3}} \right)^{2}}
$$
$$
\frac{(2x-3)\left( x^{\frac{1}{3}} \right)-(x^{2}-3x+2)\left( \frac{1}{3} x^{-\frac{2}{3}} \right)}{\left( x^{\frac{1}{3}} \right)^{2}} = \frac{\frac{5}{3}x^{\frac{4}{3}}-2x^{\frac{1}{3}}-\frac{2}{3}x^{- \frac{2}{3}}}{x^{\frac{2}{3}}}=\frac{5x^{2}-6x-2}{3x^{\frac{4}{3}}}
$$

\subsection{$f(x)=(x\sin x)^{x}$}

Following $(\ln x)'=\frac{1}{x}$, $(\sin x)'=\cos x$, chain rule and product rule.

$$
\ln f(x) = \ln x+x\ln \sin x\implies \frac{f'(x)}{f(x)}=\frac{f'(x)}{(x\sin x)^{x}}=(\ln x)'+(x\ln \sin x)'
$$
$$
f'(x)=(x\sin x)^{x}\left( \frac{1}{x}+\left( x\left( (\sin x)' \frac{1}{\sin x} \right)+(x)'\ln \sin x \right) \right)=(x\sin x)^{x}\left( \frac{1}{x} +x\cot x+\ln \sin x\right)
$$

\subsection{$f(x)=\cos(\sin x)$}
$$
f(x)'=(\sin x)'\sin(\sin x)=-\cos x\sin(\sin x)
$$
Following chain rule and $(\sin x)'=\cos x$ and $(\cos x)'=-\sin x$

\section{Determine the types of the following indeterminate form ( $\frac{0}{0}, \frac{\infty}{\infty},0\cdot \infty,\infty\cdot-\infty,0^{0},\infty^{0},1^{\infty}$), and use L’Hopital’s rule to find their limits where applicable}

\subsection{$\lim_{ x \to \frac{1}{2} } \frac{6x^{2}+5x-4}{4x^{2}+16x-9}$}
$$
\lim_{ x \to \frac{1}{2} }\frac{6x^{2}+5x-4}{4x^{2}+16x-9}\to \frac{0}{0}
$$
$$
\lim_{ x \to \frac{1}{2} }\frac{6x^{2}+5x-4}{4x^{2}+16x-9}= \lim_{ x \to \frac{1}{2} }  \frac{\cancel{ (2x-1) }(3x+4)}{(2x+9)\cancel{ (2x-1) }}= \lim_{ x \to \frac{1}{2} }\frac{3x+4}{2x+9}\to\frac{11}{20}
$$

\subsection{$\lim_{ x \to \infty} \frac{\ln x}{\sqrt[  ]{ x }}$}
$$
\lim_{ x \to \infty} f(x)=\lim_{ x \to \infty} \frac{\ln x}{\sqrt[  ]{ x }}\to \frac{\infty}{\infty}
$$
$$
\lim_{ x \to \infty} \frac{\frac{d}{dx}(\ln x)}{\frac{d}{dx}(\sqrt[  ]{ x })}=\lim_{ x \to \infty} \frac{2\sqrt[  ]{ x }}{x} = \lim_{ x \to \infty} \frac{2}{\sqrt[  ]{ x }}\to 0 \therefore \lim_{ x \to \infty} f(x)\to0
$$

\subsection{$\lim_{ x \to 1 } \frac{x^{8}-1}{x^{5}-1}$}
$$
\lim_{ x \to 1 } \frac{x^{8}-1}{x^{5}-1}\to \frac{0}{0}
$$
$$
\lim_{ x \to 1 } \frac{\frac{d}{dx}(x^{8}-1)}{\frac{d}{dx}(x^{5}-1)}=\lim_{ x \to 1 } \frac{8x^{7}}{5x^{4}}=\lim_{ x \to 1 } \frac{8x^{3}}{5}\to \frac{8}{5}
$$
$$
\therefore \lim_{ x \to 1 } \frac{x^{8}-1}{x^{5}-1}\to \frac{8}{5}
$$

\subsection{$\lim_{ x \to 0^{+} }(1+\sin3x)^{\frac{1}{x}}$}
$$
\lim_{ x \to 0^{+} }(1+\sin3x)^{\frac{1}{x}}\to 1^{\infty}
$$
$$
\lim_{ x \to 0^{+} }\ln f(x)=\lim_{ x \to 0^{+} }\frac{\ln(1+\sin 3x)}{x}=\frac{0}{0}
$$
$$
\lim_{ x \to 0^{+} } \frac{\frac{d}{dx}(\ln(1+\sin 3x))}{\frac{d}{dx} (x)}=\lim_{ x \to 0^{+} }\frac{\frac{3\cos 3x}{1+\sin 3x}}{1}
$$
$$
=\lim_{ x \to 0^{+} }\frac{3\cos 3x}{1+\sin 3x}\to3\therefore \lim_{ x \to 0^{+} }\ln f(x)\to3 \iff \lim_{ x \to 0^{+} }f(x)\to e^{3}
$$
