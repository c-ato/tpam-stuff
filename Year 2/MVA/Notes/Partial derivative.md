> [!definition|*]- Partial derivatives
> For some $z=f(x,y)$, fix $y=b$ where $b$ is some constant
> $$\left. \frac{ df(x,y) }{ dx } \right|_{y=b}= \lim_{ \Delta x \to 0 } \frac{f(x+\Delta x,b)-f(x,b)}{\Delta x}\equiv \frac{ \partial f(x,y) }{ \partial x }   \text{ or }f_{x}(x,y)$$
> Similarly
> $$\left. \frac{ df(x,y) }{ dx } \right|_{x=b}= \lim_{ \Delta y \to 0 } \frac{f(a,y+\Delta y)-f(a,y)}{\Delta y}\equiv \frac{ \partial f(x,y) }{ \partial y }   \text{ or }f_{y}(x,y)$$
 ^def-mva-par-deriv

> [!theorem|*]- Linearity, product and quotient rules of partial derivatives
> For $u=u(x,y)$ and $v=(x,y)$, and constants $a$ and $b$.
> $$\frac{ \partial  }{ \partial x }(au+bv)=a\frac{ \partial u }{ \partial x }+b\frac{ \partial v }{ \partial x }$$
> $$\frac{ \partial  }{ \partial x } (uv)=\frac{ \partial u }{ \partial x } v+\frac{ \partial v }{ \partial x } u$$
> $$\frac{ \partial  }{ \partial x } \left( \frac{u}{v} \right)=\frac{1}{v^{2}}\left( \frac{ \partial u }{ \partial x } v-\frac{ \partial v }{ \partial x } u \right)$$
 ^thm-mva-par-der-prop

> [!definition|*]- Higher Order Partial Derivative
> - $\frac{ \partial  }{ \partial x }\left( \frac{ \partial f }{ \partial y } \right)=f_{xy}$
> - $\frac{ \partial  }{ \partial y }\left( \frac{ \partial f }{ \partial x } \right)=f_{yx}$
> - $\frac{ \partial  }{ \partial x }\left( \frac{ \partial^{n} f }{ \partial y^{n} } \right)=f_{x\underbrace{ y\dots y }_{ n }}$
> - $\frac{ \partial^{n}  }{ \partial x^{n} }\left( \frac{ \partial f }{ \partial y } \right)=f_{\underbrace{ x\dots x }_{ n }y}$
 ^def-mva-high-par-der

> [!theorem|*]- Mixed partial derivative commute (if continuous)
> If partial derivatives are continuous, the mixed derivatives commute:$f_{xy}\equiv f_{yx}\impliedby f_{x}\text{ and }f_{y}$ are continuous
 ^thm-mva-par-der-comm
