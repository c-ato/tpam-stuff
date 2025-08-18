---
tags:
  - maths/category
aliases:
  - pullbacks
---

> [!definition|*]- Pullback (Category)
> Given two morphisms $f:X\to Z$ and $g:Y\to Z$, their pullback (or fibre product) is $P=X\times_{Z} Y$, that is the set of all pairs satisfying $f(x)=g(y),x \in X,y\in Y$ such it is an object with its two natural morphisms that act on $P$, being $p_{1}:P\to X$ and $p_{2}: P\to Y$ such the diagram commutes:
> ```tikz
> \usepackage{tikz-cd}
> \begin{document}
> \begin{tikzcd} P & Y \\ X & Z \arrow["{p_2}", from=1-1, to=1-2] \arrow["{p_1}"', from=1-1, to=2-1] \arrow["g"', from=1-2, to=2-2] \arrow["f"', from=2-1, to=2-2] \end{tikzcd}
> \end{document}
>```
>Further, for any object - $Q$, $q_{1}:Q\to X$ and $q_{2}:Q\to Y$, where $f\circ q_{1}=g \circ q_{2}$ there exists a unique morphism $u:Q\to P$ such that $p_{1} \circ u= q_{1}$ and $p_{2}\circ u=q_{2}$ such the commutative diagram holds:
>```tikz
> \usepackage{tikz-cd}
> \begin{document}  
> \begin{tikzcd}
>	Q & & \\
>	& P & Y \\
>	& X & Z
>	\arrow["{q_1}"', bend right=30, from=1-1, to=3-2]
>	\arrow["{q_2}", bend left=30, from=1-1, to=2-3]
>	\arrow["u"', dashed, from=1-1, to=2-2]
>	\arrow["{p_2}", from=2-2, to=2-3]
>	\arrow["{p_1}"', from=2-2, to=3-2]
>	\arrow["g"', from=2-3, to=3-3]
>	\arrow["f"', from=3-2, to=3-3]
> \end{tikzcd}
> \end{document}
>```
 ^def-cat-pullback

We will be using pullbacks in the context of topologies and fibre bundles, where $g:Y\to Z$ is called a bundle projection, where this is a bundle where $Y$ is a total space over the base space $Z$. $P$ is also denoted as $f^{*}Y$, that is $Y$ pulled back along $f$, where $f^{*}Y$ represents a new fibre bundle over $X$, whoms fibres over points $x \in X$ are isomorphic to fibres of $Y$ over corresponding points $f(x) \in Z$. This mathematically describes how structures are restricted or preserved on morphisms.

If we are to define a fibre pullback from the general categorical definition of pullbacks, with mind for consistency to previously used notation, a fibre pullback is the following:

> [!definition|*]- Fibre Pullback 
> Given two morphisms $f:B'\to B$ and $\pi: E\to Z$, their pullback is $f^{*}E$, that is the set of pairs $\{(b',e): f(b')=\pi(e),b' \in B',e\in E \}$ such it is an object with its two natural morphisms that act on $f^{*}E$, being $\pi':f^{*}E\to B'$ and $h: f^{*}E\to E$ such the diagram commutes:
> ```tikz
> \usepackage{tikz-cd}
> \begin{document}
> \begin{tikzcd} f^*E & E  \\ B' & B \arrow["{h}", from=1-1, to=1-2] \arrow["{\pi'}"', from=1-1, to=2-1] \arrow["\pi"', from=1-2, to=2-2] \arrow["f"', from=2-1, to=2-2] \end{tikzcd}
> \end{document}
>```
>Further, for any object - $Q$, $q_{1}:Q\to B'$ and $q_{2}:Q\to E$, where $f\circ q_{1}=\pi \circ q_{2}$ there exists a unique morphism $u:Q\to f^{*}E$ such that $\pi' \circ u= q_{1}$ and $h\circ u=q_{2}$ such the commutative diagram holds:
>```tikz
> \usepackage{tikz-cd}
> \begin{document}  
> \begin{tikzcd}
>	Q & & \\
>	& f^*E & E \\
>	& B' & B
>	\arrow["{q_1}"', bend right=30, from=1-1, to=3-2]
>	\arrow["{q_2}", bend left=30, from=1-1, to=2-3]
>	\arrow["u"', dashed, from=1-1, to=2-2]
>	\arrow["{h}", from=2-2, to=2-3]
>	\arrow["{\pi'}"', from=2-2, to=3-2]
>	\arrow["\pi"', from=2-3, to=3-3]
>	\arrow["f"', from=3-2, to=3-3]
> \end{tikzcd}
> \end{document}
>```
 ^def-cat-pullback
 