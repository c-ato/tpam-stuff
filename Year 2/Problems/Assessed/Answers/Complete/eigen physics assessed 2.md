![[Pasted image 20260212125222.png]]
(a) 
$$- \frac{d^{2}\psi}{dx^{2}}+\left[ x^{2}+ \frac{l(l+1)}{x^{2}}-E \right] =0\qquad x\to 0\qquad\left[ x^{2}+ \frac{l(l+1)x^{2}}{x^{2}}-E \right]\to \frac{l(l+1)}{x^{2}}$$
$$\frac{d^{2}\psi}{dx^{2}}=l(l+1)x^{l-1}\qquad- \frac{d^{2}\psi}{dx^{2}}+ \frac{l(l+1)}{x^{2}}\psi=-l(l+1)x^{l-1}+l(l+1)x^{l-1}=0$$

$$- \frac{d^{2}\psi}{dx^{2}}+\left[ x^{2}+ \frac{l(l+1)}{x^{2}}-E \right] =0\qquad x\to \infty\qquad\left[ x^{2}+ \frac{l(l+1)x^{2}}{x^{2}}-E \right]\to x^{2}$$
$$\frac{d^{2}\psi}{dx^{2}}=(x^{2}-1)e^{ - \frac{x^{2}}{2} }\qquad- \frac{d^{2}\psi}{dx^{2}}+ x^{2}\psi=-(x^{2}-1)e^{ - \frac{x^{2}}{2} }+x^{2}e^{ -\frac{x^{2}}{2} }=e^{ ^{- \frac{x^{2}}{2}} }$$
$$x\to \infty\qquad e^{ -\frac{x^{2}}{2} }\to 0$$
(b)
$$\psi(x)=x^{l+1}e^{ - \frac{x^{2}}{2} }\phi(x)=fgh\qquad f=x^{l+1}\qquad g=e^{ -\frac{x^{2}}{2} }\qquad h=\phi\qquad\psi'=(f'g+fg')h+fgh'$$
$$\psi''=(f''g+2f'g'+fg'')h+2(f'g+fg')h'+fgh''$$
$$-\frac{ \partial^{2} \psi }{ \partial x^{2} } +\left[ x^{2}+\frac{l(l+1)}{x^{2}} \right]\psi=E\psi$$
$$-(f''g+2f'g'+fg'')h-2(f'g+fg')h'-fgh''+x^{2}fgh+ \frac{l(l+1)}{x^{2}}fgh=Efgh$$
$$-\frac{f''g+2f'g'+fg''}{fg}h-\frac{2(f'g+fg')}{fg}h'-h''+x^{2}h+ \frac{l(l+1)}{x^{2}}h=Eh$$
$$h''+\underbrace{ \frac{2(f'g+fg')}{fg} }_{ s(x) }h'+\underbrace{ \left( \frac{f''g+2f'g'+fg''}{fg}+E -x^{2}- \frac{l(l+1)}{x^{2}} \right) }_{ t(x) }h=0$$
$$\frac{2(f'g+fg')}{fg}=\frac{2((l+1)x^{l}g-x^{l+2}g)}{x^{l+1}g}= \frac{2((l+1)-x^{2})}{x}=2\left( \frac{l+1}{x}-x \right)=s(x)$$
$$\frac{f''g+2f'g'+fg''}{fg}=\frac{l(l+1)x^{l-1}g-2(l+1)x^{l+1}g+x^{l+1}(x^{2}-1)g}{x^{l+1}g}= \frac{l(l+1)}{x^{2}}- 2(l+1)+x^{2}-1$$
$$\implies t(x)=\frac{l(l+1)}{x^{2}}- 2l-2+x^{2}-1+E-x^{2}- \frac{l(l+1)}{x^{2}}=E-2l-3$$
$$\therefore \frac{d^{2}\phi}{dx^{2}} +2\left( \frac{l+1}{x}-x \right)\frac{ d \phi }{ d x } +(E-2l-3)\phi$$
(c)
$$z=x^{2}\implies \frac{dz}{dx}=2x=2z^{\frac{1}{2}}\implies \frac{d}{dx}=2z^{\frac{1}{2}} \frac{d}{dz} $$
$$\frac{d^{2}}{dx^{2}}=\frac{d}{dx}\left( 2z^{\frac{1}{2}} \frac{d}{dz} \right)=2z^{\frac{1}{2}} \frac{d}{dz}\left( 2z^{\frac{1}{2}} \frac{d}{dz} \right)=4z \frac{d^{2}}{dz^{2}}+2 \frac{d}{dz}$$
$$\frac{d^{2}\phi}{dx^{2}}=4z \frac{d^{2}\phi}{dz}+2 \frac{d\phi}{dz}\qquad \frac{d\phi}{dx}=2z^{\frac{1}{2}} \frac{d\phi}{dz}$$
$$ \frac{d^{2}\phi}{dx^{2}} +2\left( \frac{l+1}{x}-x \right)\frac{ d \phi }{ d x } +(E-2l-3)\phi=4z \frac{d^{2}\phi}{dz}+2 \frac{d\phi}{dz}+4z^{\frac{1}{2}}\left( \frac{l+1}{z^{\frac{1}{2}}}-z^{\frac{1}{2}} \right) \frac{d\phi}{dz}+(E-2l-3)\phi$$
$$=4z \frac{d^{2}\phi}{dz}+(4l+6-4z) \frac{d\phi}{dz}+(E-2l-3)\phi=0$$
(d)
$$\phi=\sum_{k=0}^{\infty} a_{k}z^{k}\qquad \frac{d\phi}{dz}=\sum_{k=0,1}^{\infty} ka_{k}z^{k-1}\qquad \frac{d^{2}\phi}{dz^{2}}=\sum_{k=0,1,2}^{\infty} k(k-1)a_{k}z^{k-2}$$
$$4z \frac{d^{2}\phi}{dz}+(4l+6-4z) \frac{d\phi}{dz}+(E-2l-3)\phi$$
$$=\sum_{k=1}^{\infty} 4k(k-1)a_{k}z^{k-1}+\sum_{k=1}^{\infty} (4l+6)ka_{k}z^{k-1}-\sum_{k=0}^{\infty} 4ka_{k}z^{k}+\sum_{k=0}^{\infty} (E-2l-3) a_{k}z^{k}$$
$$=\sum_{k=0}^{\infty} 4k(k+1)a_{k+1}z^{k}+ (4l+6)(k+1)a_{k+1}z^{k}- 4ka_{k}z^{k} + (E-2l-3) a_{k}z^{k}=0$$
$$\implies \frac{a_{k+1}}{a_{k}}= \frac{4k-E+2l+3}{(k+1)(4l+6+4k)}=\frac{4k-E+2l+3}{4(k+1)\left( l+k+ \frac{3}{2} \right)}$$