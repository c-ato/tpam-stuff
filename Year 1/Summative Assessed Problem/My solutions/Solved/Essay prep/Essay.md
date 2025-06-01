# ***A Brief Aside into the Development of Renormalisation***

## Introduction

The motivation behind this essay is to build the foundation for a Summer Research Programme that delves into TQFT (topological quantum field theory). However, as this topic is vast and well out of reach of a first-year essay with a rather meagre word cap, it is enough to settle with a small subsection, specifically the historical grounding around renormalisation.

The structure will present a definition and distinction between the techniques and then 2 brief accounts of early developments of renormalisation in a somewhat chronological manner.

## Definitions

Renormalisation is a set of techniques that deals with divergence (when infinities arise - usually due to integrations) that give undefined results and are dealt with by manipulating the model to give a definitive value. These two techniques are regularisation and renormalisation of parameters (actually called renormalisation - but for the sack of clarity I will explicitly mention "renormalisation of parameters/variables" to differentiate it from from renormalisation as a whole). 

The renormalisation of parameters can be described as transformative as we change the parameters to "absorb" the infinities that would arise. This is usually used for theoretical models whose parameters have no experimental support and can compensate for the lack of information on small scales (Annick Lesne, 2021, p.2)[^1].

Whereas regularisation is a technique that can limit the integrals (giving finite values for the initial model), using $\Lambda$ as the regulator (the finite limit of the integral) and $\mathcal{M}$ as the model. Another method is to introduce $\lambda$ as a coupling constant, which numerically describes how strongly particles or fields interact with each other. A counter term is then added such that $\lambda \mathcal{M}_{\Lambda}+\:\delta\lambda \mathcal{M_{\Lambda}}$ (Annick Lesne, 2021, p.5)[^1] so that when removing the limit by taking $\lim_{ \Lambda \to x }$, where $x$ is the previous divergence point, ensuring that the infinities do not arise (Annick Lesne, 2021, p.4)[^1]. This process can be described as constructive.

These are often used in conjunction following the general order of, regulation - adding limits to the integral and adding a counter term, renormalising the parameters - changing parameters so they absorb the infinities. Then removing the limits by taking the limit of $\Lambda$ to the previous divergence point (a regularisation technique) (Annick Lesne, 2021, p.4)[^1].

## Mathematical Regularisation Analogue 

Perhaps a suitable analogy for regularisation is solving for a particular $\infty-\infty=c$ where $c$ is some real finite number that occurs when dealing with infinite series. A simple case is given below:
$$
\sum^{\infty}_{n=1} \frac{1}{2(n+1)}-\sum^{\infty}_{n=1} \frac{1}{2(n+6)}
$$
We may apply an analogous regulator by taking the partial sum:
$$
\sum^{N}_{n=1} \frac{1}{2(n+1)}-\sum^{N}_{n=1} \frac{1}{2(n+6)}
$$
We can expand this and realise that terms cancel and "absorb" the infinities giving a much simpler partial sum:
$$
\frac{1}{2}\left( \left( \frac{1}{2}+\frac{1}{3}+\cancel{ \frac{1}{4} }+\dots+\cancel{ \frac{1}{N} }+\cancel{ \frac{1}{N+1} } \right)-\left( \cancel{ \frac{1}{4} }+\cancel{ \frac{1}{5} }+\dots +\cancel{ \frac{1}{N+1} }+\frac{1}{N+2}+\frac{1}{N+3} \right) \right)
$$
$$
=\frac{1}{2}\left( \frac{1}{2}+\frac{1}{3}-\frac{1}{N+2}-\frac{1}{N+3} \right)
$$
We then remove the regulator by taking the limit of $N\to \infty$ and see that the final result is finite and exact:
$$
\sum^{\infty}_{n=1} \frac{1}{2(n+1)}-\sum^{\infty}_{n=1} \frac{1}{2(n+6)}=\frac{5}{12}
$$
## The Ultraviolet Catastrophe 

In this particular case, the model (the Rayleigh-Jeans model) was a model that predicted the emissions of blackbody radiators. While the model was relatively accurate for low frequencies, there was a divergence at high frequencies, which would have meant that they radiated infinite energy. This naturally did not match experimental observations and was later experimentally solved and determined by Plank with a new model in 1900. However, he had to make an unjustified assumption that the energies of light are quantised (that they were proportional to integral multiples of the frequency). 
$$
E=nh\nu\qquad B_{\nu}(\nu,T)=\frac{2h\nu^{3}}{c^{2}} \frac{1}{e^{ \frac{h\nu}{kT} }-1}
$$
While he did not understand why it happened to be this way, 5 years later Einstein in 1905 published his seminal paper on the photoelectric effect and later Bohr in 1913 for the energy levels of the hydrogen atom justifying the quantisation of energy and frequency (A Douglas Stone, 2015, p.5-14)[^5]. 

Einstein demonstrated and explained the quantisation of light whereby only high (enough) frequency photons were able to emit electrons, while lower frequency light could not, no matter the intensity, demonstrating quantisation of light (A. Einstein, 1905)[^6]:
$$
E=h \nu
$$
Bohr's model used the justification that electrons do not continuously emit light all while radially collapsing into the nucleus, and experimental data for emission spectra to reason that electrons must form standing waves across its entire orbit. This would mean they have an integer number of modes and built upon $E=hf$ was able to successfully model a hydrogen model for the Balmer series(N. Bohr, 1913)[^7].
$$
\nu= R_{H}\left( \frac{1}{n_{1}^{2}}-\frac{1}{n_{2}^{2}} \right)
$$
The works of Plank acted to rescale and renormalise the variable dissolving the divergence found in the original model. While not in the method expected or usually seen actual renormalisation, it still serves as a close analogue of the method.

### An Early Formation of Renormalisation - Mass of an Electron

"Renormalisation" has been used by many physicists and its origins are hard to pinpoint but it grew and found mass adoption with QFT. One such example is the "bare" mass of the electron which could not be measured directly due to interactions with other phenomena increasing the measured mass. 

In the early 20th century a pervasive idea of classical electrodynamics was the existence of the aether, a medium through which all electromagnetic waves permeated through. J. J. Thomson evoked an analogue from hydrodynamics to model the additional mass in 1893. 

As the electron transverse through and displaced the aether it caused "drag" (an interaction with its magnetic field) which could have explained additional observed mass, so we have equations such as:
$$
1.\qquad m=m_{0}+m'
$$
Where $m$ was the experimentally observed mass, $m_{0}$ was the actual electron mass which could not be directly modelled or observed and $m'$ is the additional mass depending on the geometry of the object (L.M. Brown, 1993, p.33-34)[^2]. Here we can see where the proper use case of renormalisation of parameters will later be used from a simple rearrangement $m-m'=m_{0}$. From theoretical and experimental investigations Thompson was then able to compute the kinetic energy as:
$$
2. \qquad T= \frac{1}{2}\left( m+\frac{4}{15} \frac{\mu e^{2}}{a} \right)v^{2}
$$
Where $\mu$ is the magnetic permeability of the medium. He then was able to find the additional mass (which he called the electromagnetic mass, or the electron's self mass), where $a$ is the semi-major axis, or in the case of the electron, its radius:
$$
3.\qquad m'= \frac{2e^{2}}{3ac^{2}}
$$
Now consider if an electron was a point charge as we would in classical electrodynamics during this time. We can easily see how this results in a divergence, so a regulator was required - in this case physically this meant defining the electron radius. J.J Thomson found this through a scattering experiment giving an upper bound to the electron radius being $2.82\times 10^{-15}m$ (Pauling, Linus, 1964, p.57)[^3]. 

Later aether was discredited with the Michelson-Morsley experiment and special relativity (Staley, 2008)[^4], and other developments in QED that found that the mass of the electron was not given so simply - virtual particles arising momentarily also contributing differing masses at different scales, potentially being infinite. 

Hans Kramer later built upon Lorentz who believed that there was only the electromagnetic mass and calculated the radiation reaction force (the force that a charge feels due to self-interactions):
$$
4. \qquad \mathbf{F}_{self}=- \frac{2}{3c^{2}}\ddot{\mathbf{x}}\iint d^{3}x\,d^{3}x' \frac{\rho(\mathbf{x})\rho(\mathbf{\mathbf{x'}})}{|\mathbf{x}-\mathbf{x}'|}+ \frac{2}{3} \frac{e^{2}}{c^{3}} \dddot{\mathbf{x}}+g \frac{ae^{2}}{c^{4}}+(a^{2})+\dots
$$
Where $a$ is the radius of the charge distribution $\rho(\mathbf{x})$ Lorentz then derived his version of Lorentz's theory to be:
$$
5.\qquad m_{0}\ddot{\mathbf{x}}=\mathbf{K}+\mathbf{F}_{ext}+\mathbf{F}_{self}
$$
where $F_{ext}$ is the external force and $K$ a non-electromagnetic force. He then subbed equations $4$ and $1$ into $4$ ending up with:
$$
m_{\exp} \ddot{\mathbf{x}}=\mathbf{K}+ e\left( \mathbf{E}_{ext}+ \frac{[\mathbf{v}\times \mathbf{B}_{ext}]}{c} \right)+ \frac{2}{3} \frac{e^{2}}{c^{2}} \ddot{\mathbf{x}}
$$
This equation includes the experimental mass and observable external fields. This also implicitly includes the $m'$ of the original model which diverges, but it has been contained by the experimental mass - in other words, renormalised. Kramer shared his results in the Shelter Island Conference in 1947, from which it popularised (L.M. Brown, 1993, p.51)[^2].
## Conclusion

There is not much to be said about this essay's account of renormalisation other than lacking in depth, or a comprehensive story on how renormalisation came to be. However, this is inevitable due to the berth and complexity of entwining individual advances, that eventually manifested renormalisation into a powerful tool.
## Reference

[^1]: Annick Lesne (2021). Regularization, renormalization, and renormalization groups. _Hal.science_, [online] p.pp. 121–154. doi:https://hal.science/hal-03104870.

[^2]: L.M. Brown, (1993). _Renormalization From Lorentz to Landau_. Springer.

[^3]:Pauling, Linus, (1964). _College Chemistry_. San Francisco: Freeman.

[^4]:Staley, R. (2008). _Einstein’s generation : the origins of the relativity revolution_. Chicago ; London: University Of Chicago Press.

[^5]:A Douglas Stone (2015). _Einstein and the quantum : the quest of the valiant Swabian_. Princeton: Princeton University Press.

[^6]:Einstein, A., (1905). On a heuristic point of view concerning the production and transformation of light. _Annalen der Physik_, _17_(132), pp.1-16.

[^7]:Bohr, N. (1913). XXXVII. On the constitution of atoms and molecules. _The London, Edinburgh, and Dublin Philosophical Magazine and Journal of Science_, [online] 26(153), pp.476–502. doi:https://doi.org/10.1080/14786441308634993.