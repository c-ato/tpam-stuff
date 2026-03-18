[[Assessed Promblem Sheet 7.pdf]]
(a)
$$T=\frac{1}{2}m\dot{x}^{2}\qquad V=2\left( \frac{1}{2}k(l-a)^{2} \right)=k(\sqrt[  ]{ x^{2}+b^{2} }-a)^{2}$$
$$
V'(x_{0})=0=2kx_{0}(x_{0}^{2}+b^{2})^{-\frac{1}{2}}\left((x_{0}^{2}+b^{2})^{\frac{1}{2}} -a\right)\qquad x_{0}=0$$
$$(x_{0}^{2}+b^{2})^{\frac{1}{2}}-a=0\qquad x_{0}=\pm(a^{2}-b^{2})^{\frac{1}{2}}$$
$$V''(x)=2k\left( 1-a( x^{2}+b^{2})^{-\frac{1}{2}}+ax^{2}(x^{2}+b^{2})^{-\frac{3}{2}} \right)  $$
$$V''(0)=2k\left( 1-\frac{a}{b} \right)\qquad V''\left(\pm( a^{2}-b^{2})^{\frac{1}{2}} \right)=2k\left( 1- \frac{b^{2}}{a^{2}} \right)$$
(b)
$$V(x)\approx V(x_{0})+V'(x_{0})(x-x_{0})+\frac{1}{2}V''(x_{0})(x-x_{0})^{2}$$
$$x_{0}=\pm (a^{2}-b^{2})^{\frac{1}{2}}\qquad V(x)\approx k\left( 0+0+\left( 1-\frac{b^{2}}{a^{2}} \right)(x\mp \left( a^{2}-b^{2})^{\frac{1}{2}} \right)^{2} \right)$$
For ease, use $q=x\mp(a^{2}-b^{2})^{\frac{1}{2}}$ as position, leaving $\dot{q}=\dot{x}$.
$$\mathcal{L} =\frac{1}{2}m\dot{x}^{2}-V(x)\approx \frac{1}{2}m\dot{q}^{2}-k\left( \frac{a^{2}-b^{2}}{a^{2}} \right)q^{2}$$
$$\frac{d}{dt}\frac{ \partial \mathcal{L}  }{ \partial \dot{q} } -\frac{ \partial \mathcal{L}  }{ \partial q } =m\ddot{q}-2k\left( \frac{a^{2}-b^{2}}{a^{2}} \right)q=0$$
this is can be rearranged into the form
$$\ddot{q}-\omega^{2}q=0$$
where 
$$q=\alpha_{1} \sin(\omega t)+\alpha_{2}\cos(\omega t)\qquad x=\alpha_{1} \sin(\omega t)+\alpha_{2}\cos(\omega t)\pm (a^{2}-b^{2})^{\frac{1}{2}}$$
$$\omega_{\pm}=\sqrt[  ]{ \frac{2k(a^{2}-b^{2})}{ma^{2}} }$$
This solution corresponds to the simple harmonic oscillator, and thus displays SHM around $x_{0}=\pm (a^{2}-b^{2})^{\frac{1}{2}}$

$$x_{0}=0\qquad\mathcal{L} =\frac{1}{2}m\dot{x}^{2}-V(x)\approx \frac{1}{2}m\dot{x}^{2}-k\left( \frac{b-a}{b} \right)x^{2}$$
$$\frac{d}{dt}\frac{ \partial \mathcal{L}  }{ \partial \dot{x} } -\frac{ \partial \mathcal{L}  }{ \partial x } =m\ddot{x}+k\left( \frac{b-a}{b} \right)x=0$$
this is can be rearranged into the form
$$\ddot{x}+\omega^{2}x=0$$
where
$$x=\alpha_{1}e^{ \omega t }+\alpha_{2}e^{ -\omega t }\qquad \omega_{0}=\sqrt[  ]{ \frac{2k(b-a)}{bm} }$$
This solution does not correspond to simple harmonic oscillator, so around this point $x_{0}=0$ the system does not exhibit SHM