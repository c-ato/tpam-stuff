[[Assessed Problems.pdf]]
(a)
$$\mathcal{L} =\frac{I_{1}}{2}(\dot{\phi}^{2}\sin ^{2}\theta+\dot{\theta}^{2})+\frac{I_{3}}{2}(\dot{\phi}\cos \theta+\dot{\psi})^{2}-mgh\cos \theta$$
$\phi$ and $\psi$ are cyclic variables, so $p_{\phi}$ and $p_{\psi}$ are conserved.
$$p_{\theta}=\frac{ \partial \mathcal{L}  }{ \partial \dot{\theta} } =I_{1}\dot{\theta}\qquad p_{\phi}=\frac{ \partial \mathcal{L}  }{ \partial \dot{\phi} } =I_{1}\dot{\phi}\sin ^{2}\theta+I_{3}(\dot{\phi}\cos \theta+\dot{\psi})\cos \theta\qquad p_{\psi}=\frac{ \partial \mathcal{L}  }{ \partial \psi } =I_{3}(\dot{\phi}\cos \theta+\dot{\psi})$$
(b)
$$\mathcal{H} =\sum \dot{q}_{i}p_{i}-\mathcal{L} =\theta p_{\theta}+\phi p_{\phi}+\psi p_{\psi}-\mathcal{L} $$
$$=I_{1}\dot{\theta}^{2}+I_{1} \dot{\phi^{2}}\sin ^{2}\theta+I_{3}\dot{\phi}^{2}\cos ^{2} \theta+I_{3}\dot{\phi}\dot{\psi}\cos \theta+I_{3}\dot{\psi}\dot{\phi}\cos \theta+I_{3}\dot{\psi}^{2}-\mathcal{L} $$
$$=I_{1}\left( \dot{\theta}^{2}+ \dot{\phi}^{2}\sin ^{2}\theta-\frac{\dot{\phi}^{2}\sin ^{2}\theta+\dot{\theta}^{2}}{2} \right)+$$
$$I_{3}\left( \dot{\phi}^{2}\cos ^{2} \theta+\dot{\phi}\dot{\psi}\cos \theta+\dot{\psi}\dot{\phi}\cos \theta+\dot{\psi}^{2}- \frac{(\dot{\phi}\cos \theta+\dot{\psi})^{2}}{2} \right)+mgh\cos \theta$$
This is conserved as there is no time dependent constraints and $\mathcal{L}$ is not time dependent.
(c)
$$ \begin{pmatrix}
I_{1}\sin ^{2}\theta+I_{3}\cos ^{2}\theta & I_{3}\cos \theta \\
I_{3}\cos \theta & I_{3}
\end{pmatrix}\begin{pmatrix}
\dot{\phi} \\
\dot{\psi}
\end{pmatrix}=\begin{pmatrix}
p_{\phi} \\
p_{\psi}
\end{pmatrix}=
$$
$$\begin{pmatrix}
I_{1}\sin ^{2}\theta+I_{3}\cos ^{2}\theta & I_{3}\cos \theta \\
I_{3}\cos \theta & I_{3}
\end{pmatrix}^{-1}\begin{pmatrix}
p_{\phi} \\
p_{\psi}
\end{pmatrix}=\begin{pmatrix}
\dot{\phi} \\
\dot{\psi}
\end{pmatrix}=$$
$$\frac{1}{I_{1}I_{3}\sin ^{2}\theta+I_{3}^{2}\cos ^{2}\theta-I_{3}^{2}\cos ^{2}\theta} \begin{pmatrix}
I_{3} & -I_{3}\cos \theta \\
-I_{3}\cos \theta & I_{1}\sin ^{2}\theta+I_{3}\cos ^{2}\theta
\end{pmatrix}\begin{pmatrix}
p_{\phi} \\
p_{\psi}
\end{pmatrix}=$$
$$\frac{1}{I_{1}I_{3}\sin ^{2}\theta}\begin{pmatrix}
I_{3} & -I_{3}\cos \theta \\
-I_{3}\cos \theta & I_{1}\sin ^{2}\theta+I_{3}\cos ^{2}\theta
\end{pmatrix}\begin{pmatrix}
p_{\phi} \\
p_{\psi}
\end{pmatrix}= $$
$$\begin{pmatrix}
\frac{1}{I_{1}} \csc ^{2}\theta & - \frac{1}{I_{1}}\cot \theta \csc \theta \\
- \frac{1}{I_{1}}\cot \theta \csc \theta & \frac{1}{I_{3}}+\frac{1}{I_{1}}\cot ^{2}\theta
\end{pmatrix}\begin{pmatrix}
p_{\phi} \\
p_{\psi}
\end{pmatrix}= \begin{pmatrix}
\frac{p_{\phi}}{I_{1}} \csc ^{2}\theta - \frac{p_{\psi}}{I_{1}}\cot \theta \csc \theta \\
\frac{p_{\psi}}{I_{3}}+\frac{p_{\psi}}{I_{1}}\cot ^{2}\theta - \frac{p_{\phi}}{I_{1}}\cot \theta \csc \theta
\end{pmatrix}=\begin{pmatrix}
\dot{\phi} \\
\dot{\psi}
\end{pmatrix}$$
$$\dot{\phi}=\frac{p_{\phi}}{I_{1}} \csc ^{2}\theta - \frac{p_{\psi}}{I_{1}}\cot \theta \csc \theta\qquad\dot{\psi}=\frac{p_{\psi}}{I_{3}}+\frac{p_{\psi}}{I_{1}}\cot ^{2}\theta - \frac{p_{\phi}}{I_{1}}\cot \theta \csc \theta$$
$$\mathcal{L} =\frac{I_{1}}{2}\left( \left( \frac{p_{\phi}}{I_{1}}\csc \theta - \frac{p_{\psi}}{I_{1}}\cot  \theta \right)^{2} + \dot{\theta}^{2}  \right) -mgh\cos \theta$$
$$+\frac{I_{3}}{2}\left( \frac{p_{\phi}}{I_{1}}\cot \theta \csc \theta-\frac{p_{\psi}}{I_{1}}\cot ^{2}\theta+ \frac{p_{\psi}}{I_{3}}+\frac{p_{\psi}}{I_{1}}\cot ^{2}\theta - \frac{p_{\phi}}{I_{1}}\cot \theta \csc \theta \right)^{2}  =$$
$$\frac{I_{1}}{2}\left( \frac{p_{\phi}^{2}}{I_{1}^{2}} \csc ^{2}\theta - \frac{2p_{\phi}p_{\psi}}{I_{1}^{2}}\cot \theta \csc  \theta +\frac{p_{\psi }^{2}}{I_{1}^{2}}\cot ^{2}\theta + \dot{\theta}^{2}  \right) + \frac{I_{3}}{2}\left( \frac{p_{\psi}}{I_{3}} \right) ^{2}-mgh\cos \theta=$$
$$\frac{1}{2I_{1}}\left( p_{\phi}^{2} \csc ^{2}\theta - 2p_{\phi}p_{\psi}\cot \theta \csc  \theta +p_{\psi}^{2}\cot ^{2}\theta + I_{1}^{2}\dot{\theta}^{2}  \right)-mgh\cos \theta+\frac{p_{\psi}^{2}}{2I_{3}}=$$
$$\mathcal{L} =\underbrace{ \underbrace{ \frac{I_{1}}{2} \dot{\theta}^{2} }_{ T }-\underbrace{ \left( mgh\cos \theta+\frac{p_{\phi}p_{\psi}}{I_{1}}\cot \theta \csc \theta - \frac{p_{\psi }^{2}}{2I_{1}}\cot ^{2}\theta -\frac{p_{\phi}^{2}}{2I_{1}} \csc ^{2}\theta\right) }_{ V^{eff} } }_{ \mathcal{L} ^{eff} }+ \frac{p^{2}_{\psi}}{2I_{3}}$$
$$\frac{d}{dt} \frac{ \partial \mathcal{L}  }{ \partial \dot{\theta} } =\frac{ \partial \mathcal{L}  }{ \partial \theta } $$
$$I_{1}\ddot{\theta}=mgh\sin \theta+ \frac{p_{\phi}p_{\psi}}{I_{1}}(\csc ^{3}\theta+\cot ^{2} \theta\csc \theta)-\frac{p_{\psi }^{2}}{I_{1}}\csc ^{2}\theta\cot \theta+\frac{p_{\phi}^{2}}{I_{1}} \cot \theta\csc ^{2}\theta$$
$$I_{1}\ddot{\theta}=\frac{p_{\phi}p_{\psi }(1+\cos ^{2}\theta)-(p_{\psi }^{2}+p_{\phi}^{2})\cos \theta}{I_{1}\sin ^{3} \theta}+mgh\sin \theta$$


