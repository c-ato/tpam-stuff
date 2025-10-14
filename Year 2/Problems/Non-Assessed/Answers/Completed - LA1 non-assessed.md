[[2LA(1).pdf]]

1. Identify which of the structures indicated below is a vector space.
	- (a) $(\mathbb{R},+,\cdot,\mathbb{R});$ yes, elements of vect are of set, with 2 closed binary operations that form a field of the set
	- (b) $(\mathbb{C},+,\cdot,\mathbb{C});$ yes, elements of vect are of set, with 2 closed binary operations that form a field of the set
	- (c) $(\mathbb{C},+,\cdot,\mathbb{R});$ yes, elements of vect are of subset, with 2 closed binary operations that form a field of the set
	- (d) $(\mathbb{\varnothing},+,\cdot,\mathbb{R});$ no, elements of vect are not of nullset, so 2 closed binary operations that do not form a field of the set
	- (e) $(\mathbb{E^{3}},\times,\cdot,\mathbb{C});$ no, operation does not have closure or is not well defined
2. Let $V (\mathbb{F})$ be a vector space and let $S = \{\vec{v_{1}}, \vec{v_{2}}, \dots , \vec{v_{k}}\}$, where $\vec{v_{j}} ∈ V \setminus \{0\}$ for $j = 1, 2,\dots, k$. Let $\vec{u} ∈ \text{span } S$ be a non-zero vector and define $S' := S ∪ \{\vec{u}\}$.
   True or false:
	- (a) $\text{span }S'=\text{span }S$;
		 Let $\vec{u}=a_{1}\vec{v_{1}}+a_{2}\vec{v_{2}}+\dots+a_{k}\vec{v_{k}}$ as a linear combination. Suppose for contradiction that $\text{span }S'\neq\text{span }S$$\therefore \vec{w} \in \text{span }S',\vec{w}\notin\text{span }S$, where we define $\vec{w}$ as a linear combination 	  $\vec{w}=b_{1}\vec{v_{1}}+b_{2}\vec{v_{2}}+\dots+b_{k}\vec{v_{k}}+c\vec{u}=b_{1}\vec{v_{1}}+b_{2}\vec{v_{2}}+\dots+b_{k}\vec{v_{k}}+c(a_{1}\vec{v_{1}}+a_{2}\vec{v_{2}}+\dots+a_{k}\vec{v_{k}})$	  $\vec{w}=(a_{1}c+b_{1})\vec{v_{1}}+(a_{2}c+b_{2})\vec{v_{2}}+\dots+(a_{k}c+b_{k})\vec{v_{k}}$ where $a_{j},b_{j},c\in \mathbb{F}\forall j\in[1,2,\dots,k]$. We have now shown that we can compose $\vec{w}$ as a linear combination from the $\text{span }S$ so $\vec{w}\in\text{span }S\therefore \text{span }S'=\text{span }S$  
	- (b) $\text{span }S'=\text{span }S+\text{span }\{ \vec{u} \}$
		 where $\vec{v}=c_{1}\vec{v_{1}}+c_{2}\vec{v_{2}}+\dots+c_{k}\vec{v_{k}}\in \text{span }S$, and $a_{j},b,c_{j}\in\mathbb{F}\forall j\in[1,2,\dots,k]$ so $\text{span }S+\text{span }\{ \vec{u} \}=\{ \vec{v}+b\vec{u} :\vec{v}\in\text{span }S\}$	$=\{ (a_{1}b+c_{1})\vec{v_{1}}+(a_{2}b+c_{2})\vec{v_{2}} +\dots+(a_{k}b+c_{k})\vec{v_{k}}:v_{j}\in S,j\in[1,2,\dots,k]\}=\text{span }S$ and from (a) we know that $\text{span }S'=\text{span }S$ so it is true.
	- (c) The set sum $\text{span }S + \text{span }\{ \vec{u} \}$ is a direct sum.
		  By definition no as there is no unique vector, $\vec{k}=b\vec{u} =\text{span }\{ \vec{u} \}$ as $\vec{u}=a_{1}\vec{v_{1}}+a_{2}\vec{v_{2}}+\dots+a_{k}\vec{v_{k}}\in\text{span }S$
3. Let $U$ be the set of polynomials of degree $n$ divisible by $x^{2} + x + 1$.
	- (a) Is $U$ a subspace of $\mathcal{P}_{n}(\mathbb{R})$
		  We can define $U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{n-2}(\mathbb{R}) \}$ where $(x^{2}+x+1)\in\mathcal{P}_{n}(\mathbb{R})$ so $P(x^{2}+x+1)\in\mathcal{P}_{n}(\mathbb{R})\forall P \in \mathcal{P}_{n}(\mathbb{R})$. With this we may then show that this is a subspace if it satisfies closure under vector scalar multiplication and vector addition.
		  For scalar multiplication $a\in \mathbb{R},P_{1}(x^{2}+x+1)\in U\implies aP_{1}(x^{2}+x+1)$ we know that for $aP_{1}=P_{2}\in\mathcal{P}_{n}(\mathbb{R})$ so then $aP_{1}(x^{2}+x+1)=P_{2}(x^{2}+x+1)\in U$. Now for vector addition $P_{1}(x^{2}+x+1),P_{2}(x^{2}+x+1)\in \mathcal{P}_{n}(\mathbb{R})$$\implies P_{1}(x^{2}+x+1)+P_{2}(x^{2}+x+1)=(P_{1}+P_{2})(x^{2}+x+1)$ where $(P_{1}+P_{2})\in\mathcal{P}_{n}(\mathbb{R})$ so $(P_{1}+P_{2})(x^{2}+x+1)\in U$
	- (b) Find a spanning set for $U$ when $n = 2$. Do it also for $n = 3$. Are your spans minimal?
		  $U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{n-2}(\mathbb{R}) \},n=2\implies U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{n-2}(\mathbb{R}) \}$
		  $U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{0}(\mathbb{R})=\mathbb{R} \}=\{ a(x^{2}+x+1):a\in\mathbb{R} \}$ 
		  $U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{n-2}(\mathbb{R}) \},n=3\implies U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{n-2}(\mathbb{R}) \}$
		  $U:=\{ P(x^{2}+x+1):P\in\mathcal{P}_{1}(\mathbb{R}) \}=\{ (a_{1}x+a_{2})(x^{2}+x+1):a_{1},a_{2}\in\mathbb{R} \}$
		  $=\{ a_{1}(x^{3}+x^{2}+x)+a_{2}(x^{2}+x+1):a_{1},a_{2}\in\mathbb{R} \}$
4. Let $U$ be the set of polynomials $p$ of degree $n ≥ 2$ satisfying $p(0) = p(1) = 0$. Show that $U$ is a subspace of $\mathcal{P}_{n}(\mathbb{R})$. Find a basis for $U$ .
		 $p(0)\implies x,p(1)\implies x-1\implies U:=\{ P(x^{2}-x):P\in\mathcal{P}_{n-2}(\mathbb{R}) \}$ where $P=a_{1}+a_{2}x+\dots+a_{n-2}x^{n-2}\qquad a_{1},a_{2},\dots,a_{n-2}\in \mathbb{R}$
		 $\implies U=\{ (a_{1}+a_{2}x+\dots+a_{n-2}x^{n-2})(x^{2}-x):a_{1},a_{2},\dots,a_{n-2}\in \mathbb{R}\}$ 
		 $=\{ a_{1}(x^{2}-x)+a_{2}(x^{3}-x^{2})+\dots+a_{n-2}(x^{n}-x^{n-1}):a_{1},a_{2}\dots a_{n-2}\in \mathbb{R} \}$ $\therefore B=\{ (x^{2}-x),(x^{3}-x^{2}),\dots,(x^{n}-x^{n-1}) \}$

