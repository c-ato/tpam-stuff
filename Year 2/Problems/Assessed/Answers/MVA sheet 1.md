[[2MVA Problem Sheet 1-2.pdf]]

1. Calculate all second order partial derivatives of $z = f (g(x, y), h(x, y))$ with respect to $x$ and $y$, given that $g(x, y) = 2x + y$ and $h(x, y) = 2x – y$, assuming that f is sufficiently smooth. [20]
$$
f_{x}=f_{g}g_{x}+f_{h}h_{x}=2(f_{g}+f_{h})\qquad f_{y}=f_{g}-f_{h}\qquad f_{xy}=f_{yx}=f_{gg}g_{x}+f_{gh}h_{x}-f_{hg}g_{x}-f_{hh}h_{x}
$$
$$
=2f_{gg}+2f_{gh}-2f_{hg}-2f_{hh}=2(f_{gg}-f_{hh})\qquad f_{xx}=2(f_{gg}g_{x}+f_{gh}h_{x}+f_{hg}g_{x}+f_{hh}h_{x})
$$
$$
=4(f_{gg}+2f_{gh}+f_{hh})\qquad f_{yy}=f_{gg}g_{y}+f_{gh}h_{y}-f_{hg}g_{y}-f_{hh}h_{y}=f_{gg}-2f_{gh}+f_{hh}
$$
2. The function $z(x, y)$ is defined by the following equation $$\cos(xy)+\ln(z)=yz-\frac{1}{2}$$Find the partial derivatives $z_{x}$ and $z_{y}$ and calculate their values at the point $\left( \pi, \frac{1}{2}, 1 \right)$. [15]
   $$f(x,y,z)=\cos(xy)+\ln(z)-yz=-\frac{1}{2}\qquad f_{x}=-y\sin(xy)+\frac{z_{x}}{z}-yz_{x}=0\implies z_{x}=\frac{zy\sin(xy)}{1-yz}$$
   $$f_{y}=-x\sin(xy)+\frac{z_{y}}{z}-z=0\implies z_{y}=z^{2}+xz\sin(xy)$$
   $$z_{x}\left( \pi, \frac{1}{2}, 1 \right)=1\qquad z_{y}\left( \pi, \frac{1}{2}, 1 \right)=1+\frac{\pi}{2}$$
3. Consider $f(x, y, z) = e^{ xyz }$ at point $\vec{a} = (1, 2, 3)$, find
   - (i) The direction and rate of steepest ascent for $f$ at $\vec{a}$
     $$\nabla f=yze^{ xyz }\mathbf{i}+xze^{ xyz }\mathbf{j}+xye^{ xyz }\mathbf{k} \implies (6\mathbf{i}+3\mathbf{j}+2\mathbf{k})e^{ 6 }$$
     Steepest ascent is $7e^{ 6 }$ and direction is $\vec{u}=\frac{1}{7}(6\mathbf{i}+3\mathbf{j}+2\mathbf{k})$
   - (iii) Write the equation for a curved level surface passing through the point with the normal $\nabla f(a)$ [20] 
     $$e^{ xyz }=e^{6}$$
1. In the partial differential equation $$(x+y)\frac{ \partial z }{ \partial x } -(x-y)\frac{ \partial z }{ \partial y } =0$$change the variables $(x, y) → (u, v)$, where $u=\ln \sqrt[  ]{ x^{2}+y^{2} },v=\tan ^{-1}\left( \frac{y}{x} \right)$
$$u_{x}=\frac{x}{x^{2}+y^{2}}\qquad u_{y}=\frac{y}{x^{2}+y^{2}}\qquad v_{x}=-\frac{y}{x^{2}} \frac{1}{1+\frac{y^{2}}{x^{2}}}=\frac{y}{x^{2}+y^{2}}$$
$$v_{y}=\frac{1}{x} \frac{1}{1+\frac{y^{2}}{x^{2}}}=\frac{x}{x^{2}+y^{2}}\qquad z_{x}=z_{u}u_{x}+z_{v}v_{x}=\frac{1}{x^{2}+y^{2}}(xz_{u}+yz_{v})$$
$$z_{y}=z_{u}u_{y}+z_{v}v_{y}=\frac{1}{x^{2}+y^{2}}(yz_{u}+xz_{v})$$
$$
(x+y)\frac{1}{x^{2}+y^{2}}(xz_{u}+yz_{v}) -(x-y)\frac{1}{x^{2}+y^{2}}(yz_{u}+xz_{v}) =0
$$