---
tags:
  - maths
  - analysis
---
$$
\begin{array}{}
\sin ^{-1}x=\sin ^{-1}\sin y=y \\
x=\sin y \\
\frac{dx}{dy}=\cos y= \sqrt[  ]{ 1-\sin ^{2}y }=\sqrt[  ]{ 1-x^{2} } \\
\implies \int \frac{^{}_{}1}{\sqrt[  ]{ 1-x^{2} }} \, dx =y \therefore \frac{d}{dx}(\sin^{-1}x)=\frac{1}{\sqrt[  ]{ 1-x^{2} }}
\end{array}
$$
$$
\begin{array}{}
\cos ^{-1}x=\cos ^{-1}\cos y=y \\
x=\cos y \\
\frac{dx}{dy}=-\sin y=- \sqrt[  ]{ 1-\cos ^{2}y }=-\sqrt[  ]{ 1-x^{2} } \\
\implies \int -\frac{^{}_{}1}{\sqrt[  ]{ 1-x^{2} }} \, dx =y \therefore \frac{d}{dx}(\sin^{-1}x)=-\frac{1}{\sqrt[  ]{ 1-x^{2} }}
\end{array}
$$
$$
\frac{d}{dx}(\csc x)=\frac{d}{dx}\left( \frac{1}{\sin x} \right)=-\cos x \frac{1}{\sin ^{2} x}=-\cot x \csc x
$$
$$

\frac{d}{dx}(\sec x)=\frac{d}{dx}\left( \frac{1}{\cos x} \right)=\sin x \frac{1}{\cos ^{2} x}=\tan x \sec x
$$
$$
\begin{array}{}
\csc ^{-1}x=\csc ^{-1}\csc y=y \\
x=\csc y \\
\frac{dx}{dy}=-\cot y\csc y = -x^{2} \cos y=-x^{2}  \sqrt[  ]{ 1- \frac{1}{\csc ^{2} y} }=-x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} } \\
y=\int ^{}_{} -\frac{1}{x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} }} \, dx  \\
\therefore \frac{d}{dx}\csc ^{-1}x=-\frac{1}{x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} }}
\end{array}
$$
$$
\begin{array}{}
\sec ^{-1}x=\sec ^{-1}\sec y=y \\
x=\sec y \\
\frac{dx}{dy}=\tan y\sec y = x^{2} \sin y=x^{2}  \sqrt[  ]{ 1- \frac{1}{\sec ^{2} y} }=x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} } \\
y=\int ^{}_{} \frac{1}{x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} }} \, dx  \\
\therefore \frac{d}{dx}\sec^{-1}x=\frac{1}{x^{2} \sqrt[  ]{ 1-\frac{1}{x^{2}} }}
\end{array}
$$

$$
\begin{array}{}
\tanh x = \frac{\sinh x}{\cosh x}\implies(\tanh x)'=1+ \frac{\sinh ^{2}x}{\cosh ^{2}x}= \text{sech}^{2}x \\
\coth x= \frac{\cosh x}{\sinh x}\implies (\coth x)'=-(1+\coth ^{2}x)=-\text{csch}^{2}x 
\end{array}
$$