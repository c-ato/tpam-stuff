1a)
`\begin{proof}` Given $\delta>0$ and $\epsilon>0$. Where the limit is took as:
$$
\lim_{ x \to 10 }(2x+3) \to 2(10)+3=23\implies |2x+3-23|<\epsilon\implies 2|x-10|<\epsilon\implies |x-10|< \frac{\epsilon}{2}
$$
$$
x\to 10 \implies |x-10|<\delta\implies 2\delta=\epsilon
$$
Where $2\delta=\epsilon \exists \lim_{ x \to 10 }(2x+3)$.
`\end{proof}`
1b)
`\begin{proof}`Given $\delta>0$ and $\epsilon>0$. Where the limit is took as:
$$
\lim_{ x \to -7 }(-6x-2) \to -6(-7)-2=40\implies |-6x-2-40|<\epsilon\implies 6|x+7|<\epsilon\implies |x+7|< \frac{\epsilon}{7}
$$

$$
x\to -7 \implies |x+7|<\delta\implies 7\delta=\epsilon
$$
Where $7\delta=\epsilon \exists \lim_{ x \to 10 }(2x+3)$.
`\end{proof}`
2a)
$$
\lim_{ h \to 0 } \frac{2(-3+h)^{2}-18}{h}=\lim_{ h \to 0 }\frac{2h^{2}-12h+18-18}{h}=\lim_{ h \to 0 }2h-12=-12
$$
2b)
$$
\lim_{ t \to 4 }  \frac{t-\sqrt[  ]{ 3t+4 }}{4-t}=\lim_{ t \to 4 }  \frac{t-\sqrt[  ]{ 3t+4 }}{4-t} \frac{t+\sqrt[  ]{ 3t+4 }}{t+\sqrt[  ]{ 3t+4 }}=\lim_{ t \to 4 } \frac{t^{2}-3h-4}{(4-t)(t+\sqrt[  ]{ 3t+4 })}
$$
$$
= \lim_{ t \to 4 }-\frac{\cancel{ (t-4) }(t+1)}{\cancel{ (4-t) }(t+\sqrt[  ]{ 3t+4 })}=-\frac{ \lim_{ t \to 4 }(t+1)}{ \lim_{ t \to 4 }(t+\sqrt[  ]{ 3t+4 })}=-\frac{5}{8}
$$
2c)
$$
\frac{\sqrt[  ]{ 3x-2 }-\sqrt[  ]{ 5x-6 }}{\sqrt[  ]{ 2x-1 }-\sqrt[  ]{ x+1 }}=\left( \frac{\sqrt[  ]{ 3x-2 }-\sqrt[  ]{ 5x-6 }}{\sqrt[  ]{ 2x-1 }-\sqrt[  ]{ x+1 }} \right) \left( \frac{\sqrt[  ]{ 2x-1 }+\sqrt[  ]{ x+1 }}{\sqrt[  ]{ 2x-1 }+\sqrt[  ]{ x+1 }}  \right)\left( \frac{\sqrt[  ]{ 3x-2 }+\sqrt[  ]{ 5x-6 }}{\sqrt[  ]{ 3x-2 }+\sqrt[  ]{ 5x-6 }} \right)
$$
$$
\left( \frac{-2x+4}{x-2} \right)\left( \frac{\sqrt[  ]{ 2x-1 }+\sqrt[  ]{ x+1 }}{\sqrt[  ]{ 3x-2 }+\sqrt[  ]{ 5x-6 }} \right)=-2\left( \frac{\sqrt[  ]{ 2x-1 }+\sqrt[  ]{ x+1 }}{\sqrt[  ]{ 3x-2 }+\sqrt[  ]{ 5x-6 }} \right)
$$
$$
\therefore -2\lim_{ x \to 2 } \left( \frac{\sqrt[  ]{ 2x-1 }+\sqrt[  ]{ x+1 }}{\sqrt[  ]{ 3x-2 }+\sqrt[  ]{ 5x-6 }} \right)=-\cancel{ 2 } \frac{\cancel{ 2 }\sqrt[  ]{ 3 }}{\cancel{ 4 }}=-\sqrt[  ]{ 3 }
$$
3i)
$$
\lim_{ x \to \infty } x^{3}+ax^{2}+bx+c=\lim_{ x \to \infty }  x^{3}\left( 1+\frac{a}{x}+\frac{b}{x^{2}}+\frac{c}{x^{3}} \right)
$$
$$
\lim_{ x \to \infty }  x^{3}\left( 1+\lim_{ x \to \infty }\frac{a}{x}+\lim_{ x \to \infty }\frac{b}{x^{2}}+\lim_{ x \to \infty }\frac{c}{x^{3}} \right)=\infty(1)=\infty
$$
$$
\lim_{ x \to -\infty } x^{3}+ax^{2}+bx+c=\lim_{ x \to -\infty }  x^{3}\left( 1+\frac{a}{x}+\frac{b}{x^{2}}+\frac{c}{x^{3}} \right)
$$
$$
\lim_{ x \to -\infty }  x^{3}\left( 1+\lim_{ x \to -\infty }\frac{a}{x}+\lim_{ x \to -\infty }\frac{b}{x^{2}}+\lim_{ x \to -\infty }\frac{c}{x^{3}} \right)=-\infty(1+0+0+0)=-\infty
$$
3ii)
`\begin{proof}` Given that $M>0$![[sas note#^def-sas-tend-inf]] 
$$
f(x)\to \infty\exists f(x)>M>0\therefore \exists f(x)>0
$$
Similarly,
$$
f(x)\to -\infty\implies\exists f(x)<-M<0\therefore \exists f(x)<0
$$
`\end{proof}`
3iii)
`\begin{proof}` Given $\delta>0$ and using the intervals $(M,-M)$ and the IVT ![[ra note 2.1#^thm-ra-IVT]] It is then given $\exists f(x_{0})=0$
 `\end{proof}`
$$

$$
