[[data2.pdf|data2]]

\section{A loaded beam with dimensions ℓ, b and t is supported at the ends; the sag s at the midpoint is given by$$s= \frac{\mathcal{k\ell^{3}}}{tb ^{3}}$$where $\mathcal{k}$ is a constant. If there is a $1\%$ error in $\ell$, $2\%$ error in $b$, a $3\%$ error in $t$, what is the percentage error in $s$}
$$
\ell^{3}=x, \frac{1}{b^{3}}=y, \frac{1}{t}=z
$$
$$
s = xyz
$$
$$
E[s]=E\left[ kxyz \right] =k E\left[ xyz \right] =k\left( E[x]E\left[ y \right]E\left[ z \right]  \right) 
$$
Using the errors in the case of multiplication and then the general powers:
$$
\frac{\sigma^{2}(s)}{\mu^{2}(s)}=\frac{\sigma^{2}(x)}{\mu^{2}(x)}+\frac{\sigma^{2}(y)}{\mu^{2}(y)}+\frac{\sigma^{2}(z)}{\mu^{2}(z)}=9\frac{\sigma^{2}(\ell)}{\mu^{2}(\ell)}+9\frac{\sigma^{2}(b)}{\mu^{2}(b)}-\frac{\sigma^{2}(t)}{\mu^{2}(t)}=9\times 0.01^{2}+9\times 0.02^{2}+1\times0.03^{2}
$$
$$
\sqrt[  ]{ \frac{\sigma^{2}(s)}{\mu^{2}(x)} }=\sqrt[  ]{ 0.0054 }=0.07348\dots=7.34\dots\%
$$
\section{Physically observable variables $x,   y$ and $z$ are related by $$z=ax^{\alpha}y^{\beta}$$ where $a,\,\alpha$ and $\beta$ are constants. Show that their mean values and standard deviations are related by $$\mu(z)=a\mu(x)^{\alpha}\mu(y)^{\beta},\qquad \left( \frac{\sigma(z)}{\mu (z)} \right)^{2}=\left(\alpha \frac{\sigma(x)}{\mu (x)} \right)^{2}+\left( \beta\frac{\sigma(y)}{\mu (y)} \right)^{2}$$}
$$
x^{\alpha}=c,y^{\beta}=d\implies z=acd
$$
Observe and use binomial expansion
$$
c=\mu(c)+\sigma (d)=x^{\alpha}=(\mu(x)+\sigma(x))^{\alpha}\approx \mu(x)^{\alpha}+\alpha \mu(x)^{\alpha-1}\sigma(x)
$$
This follows that 
$$
\mu(c)=\mu(x)^{\alpha}\qquad and\qquad \sigma (c)=\alpha\mu(x)^{\alpha-1}\sigma(x)
$$
Similarly:
$$
d=\mu(d)+\sigma (d)=y^{\beta}=(\mu(y)+\sigma(y))^{\beta}\approx \mu(y)^{\beta}+\beta \mu(y)^{\beta-1}\sigma(y)
$$
This follows that 
$$
\mu(d)=\mu(y)^{\beta}\qquad and\qquad \sigma (d)=\beta\mu(y)^{\beta-1}\sigma(y)
$$
$$
\mu(z)=E[acd]=aE[c]E[d]=a\mu(c)\mu(d)=a\mu(x)^{\alpha}\mu(y)^{\beta} 
$$
$$
E[z^{2}]=E[a^{2}c^{2}d^{2}]=a^{2}E[c^{2}]E[d^{2}]
$$
$$
\sigma^{2}(z)=E[z^{2}]-E[z]^{2}=a^{2}\left( [\mu^{2}(c)+\sigma^{2}(c)] [\mu^{2}(d)+\sigma^{2}(d)] -\mu(c)\mu(d)\right ) 
$$
$$
=a^{2}\left( \mu^{2}(c)\sigma^{2}(d)+\mu^{2}(d)\sigma^{2}(c) +\sigma^{2}(c)\sigma^{2}(d)\right) \approx a^{2}\left( \mu^{2}(c)\sigma^{2}(d)+\mu^{2}(d)\sigma^{2}(c)\right)
$$
Ignoring 2nd order smallness above.
$$
\implies \frac{\sigma^{2}(z)}{\mu^{2}(z)}= \frac{\sigma^{2}(c)}{\mu^{2}(c)}+\frac{\sigma^{2}(d)}{\mu^{2}(d)} = \left( \frac{\sigma(c)}{\mu(c)} \right)^{2}+\left( \frac{\sigma(d)}{\mu(d)}  \right)^{2}
$$
Now subbing in from earlier:
$$
\implies \frac{\sigma^{2}(z)}{\mu^{2}(z)}=\left( \frac{\sigma(c)}{\mu(c)} \right)^{2}+\left( \frac{\sigma(d)}{\mu(d)}  \right)^{2}=\left( \frac{\alpha \mu(x)^{\cancel{ \alpha }-1}\sigma(x)}{\cancel{ \mu(x)^{\alpha} }} \right)^{2}+\left( \frac{\beta \mu(y)^{\cancel{ \beta }-1}\sigma(y)}{\cancel{ \mu(y)^{\beta} }} \right)^{2}=
$$
$$
\therefore\frac{\sigma^{2}(z)}{\mu^{2}(z)}=\left(\alpha \frac{\sigma(x)}{\mu (x)} \right)^{2}+\left( \beta\frac{\sigma(y)}{\mu (y)} \right)^{2}
$$
Wasn't sure how rigorous I needed to be with this so I replicated the proofs in the notes.

\subsection{Physically observable variables $x$ and $z$ are related by $z = f (x)$. Use Taylor’s theorem to show that their mean values and standard deviations are related by$$\mu(z)=f(\mu(x)),\qquad \sigma(z)=|f'(\mu(x))|\sigma(x)$$}
Taylor expansion is given in the form:
$$
f(y + d) = f(y) + f'(y)d + f''(y) \frac{d^{2}}{2!} + \dots 
$$
Let $y=\mu(x)$ and $d=x-\mu(x)$ for the above:
$$
f(x) = f(\mu(x)) + f'(\mu(x))(x-\mu(x)) + f''(\mu(x)) \frac{(x-\mu(x))^{2}}{2!} + \dots
$$
Also given that 
$$
x=\mu(x)+\sigma(x)\qquad and\qquad f(x)=\mu(f(x))+\sigma(f(x))
$$
Notice that $\sigma(x)=x-\mu(x)$ and thus we may ignore 2nd order smallness (third order Taylor expansion) onwards:
$$
\mu(f(x))+\sigma(f(x))=f(\mu(x))+f'(\mu(x))(x-\mu(x))=f(\mu(x))+f'(\mu(x))(\sigma (x))
$$
Now comparing the $\sigma$ values:
$$
\sigma(f(x))=f'(\mu(x))\sigma(x)
$$
This leaves:
$$
\mu(f(x))=f(\mu(x))
$$
The $\sigma$ values should have the same signs regardless of $f'(\mu (x))$ so:
$$
\sigma(f(x))=|f'(\mu(x))|\sigma(x)
$$

\section{Physically observable variables $x$, $y$ and $z$ are related by $z = f (x, y)$. Use Taylor’s theorem to show that their mean values and standard deviations are related by}
$$
\begin{align}\mu(z)&=f(\mu(x),\mu(y)) \\
\sigma^{2}(z) &= \left| \frac{ \partial f }{ \partial x } (\mu(x),\mu(y)) \right|^{2}\sigma^{2}(x) +\left| \frac{ \partial f }{ \partial y } (\mu(x),\mu(y)) \right|^{2}\sigma^{2}(y) 
\end{align}$$


Lets start with:
$$
z=\mu(z)+\sigma(z)\qquad x=\mu(x)+\sigma(x)\qquad y=\mu(y)+\sigma(y)
$$
The bivariate Taylor expansion is given by:
$$
f(c+h,d+k)= \sum^{n}_{m=0} \frac{1}{m!}\left( h \frac{ \partial  }{ \partial c } +k\frac{ \partial  }{ \partial d }  \right)^{m}f(c,d)
$$
Now let $c=\mu(x)$, $d=\mu(y)$, $h=x-\mu(x)$ and $k=y-\mu(y)$, and we will expand $z$ to only 2nd order. This is because onwards there will be 2nd degree (and higher) smallness in individual factors which can be ignored, and cross products will $=0$ as they are independent:
$$
z=\mu(z)+\sigma(z)=f(\mu(x),\mu(y))+(x-\mu(x))\frac{ \partial f }{ \partial x } (\mu(x),\mu(y))+(y-\mu(y))\frac{ \partial f }{ \partial y } (\mu(x),\mu(y))
$$
Now using $\sigma(x)=x-\mu(x)$ and $\sigma(y)=y-\mu(y)$ and comparing $\sigma$ values:
$$
=f(\mu(x),\mu(y))+\sigma(x)\frac{ \partial f }{ \partial x } (\mu(x),\mu(y))+\sigma(y)\frac{ \partial f }{ \partial y } (\mu(x),\mu(y))
$$
$$
\sigma (z)= \sigma(x)\frac{ \partial f }{ \partial x } (\mu(x),\mu(y))+\sigma(y)\frac{ \partial f }{ \partial y } (\mu(x),\mu(y))
$$
$$
\therefore\mu(z)=f(\mu(x),\mu(y))
$$
$$
\implies\sigma^{2}(z)=\sigma^{2}(x)\left( \frac{ \partial f }{ \partial x } (\mu(x),\mu(y)) \right)^{2}+\sigma^{2}(y)\left( \frac{ \partial f }{ \partial y } (\mu(x),\mu(y)) \right)^{2} 
$$
$$
+\,\sigma(x)\sigma(y)\frac{ \partial f }{ \partial x } (\mu(x),\mu(y))\frac{ \partial f }{ \partial y } (\mu(x),\mu(y))
$$
As mentioned before cross terms can be ignored as they are independent:
$$
\implies\sigma^{2}(z)=\sigma^{2}(x)\left| \frac{ \partial f }{ \partial x } (\mu(x),\mu(y)) \right|^{2}+\sigma^{2}(y)\left| \frac{ \partial f }{ \partial y } (\mu(x),\mu(y)) \right|^{2} 
$$

$$

$$