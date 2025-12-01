
Polyacetylene is a long chain polymer, of the form (-CH=CH-CH=CH-) where ‘-’ is a single bond and ‘=’ is a double bond. Longitudinal vibrations parallel to the main chain can be calculated by modelling the polymer as a 1-D chain of identical masses $M$ , representing a ‘CH’ unit, separated by springs of alternating strength representing the single and double bonds, with force constants $K_{1}$ and $K_{2}$.

(a) Identify the smallest possible unit cell. [Hint: are the ‘CH’ groups all identical?] Write down the (two) equations of motion for the longitudinal displacements of the carbon atoms.

![[QaTS assessed 2 2025-11-24 22.42.35.excalidraw]]
$$m\ddot{u}=(v_{n}-u_{n})K_{1}-(u_{n}-v_{n-1})K_{2}\qquad m\ddot{v}=(u_{n+1}-v_{n})K_{2}-(v_{n}-u_{n})K_{1}$$
(b) By use of appropriate trial solutions, show that the characteristic frequencies for these motions along the chain are given by $$\omega^{2}=\frac{K_{1}+K_{2}}{m}\left[ 1\pm \left\{ 1-\frac{4K_{1}K_{2}\sin ^{2}\left( \frac{1}{2}qa \right)}{(K_{1}+K_{2})^{2}} \right\} ^{\frac{1}{2}}  \right] $$where $q$ is the wavenumber and $a$ is the length of the unit cell.

Using exponential ansats for trial solution
$$u_{n}=Ae^{ i(qna-\omega t) }\qquad v_{n}=Be^{ i(qna-\omega t) }\therefore u_{n+1}=A e^{ iqa }e^{ i(qna-\omega t) }\qquad v_{n-1}=Be^{ -iqa }e^{ i(qna-\omega t) }$$
$$\implies -A\omega^{2}m=(B-A)K_{1}-(A-Be^{ -iqa })K_{2}\qquad -B\omega^{2}m=(Ae^{ iqa }-B)K_{2}-(B-A)K_{1}$$
$$\iff A(K_{1}+K_{2}-\omega^{2}m) =B(K_{1}+K_{2}e^{ -iqa })\qquad B(K_{1}+K_{2}-\omega^{2}m) =A(K_{1}+K_{2}e^{ iqa })$$
$$\implies B(K_{1}+K_{2}-\omega^{2}m) = \frac{B(K_{1}+K_{2}e^{ iqa })(K_{1}+K_{2}e^{ -iqa })}{(K_{1}+K_{2}-\omega^{2}m)}$$
$$\implies \omega^{4}m ^{2}-2(K_{1}+K_{2})\omega^{2} m+(K_{1}+K_{2})^{2}= K_{1}^{2}+K_{1}K_{2}(e^{ iqa }+e^{ -iqa })+K_{2}^{2}$$
$$=K_{1}^{2}+2K_{1}K_{2}\cos(qa)+K_{2}^{2}$$
$$\implies \omega^{4}-\frac{2(K_{1}+K_{2})}{m}\omega^{2}+ \frac{2K_{1}K_{2}(1-\cos(qa))}{m ^{2}}=0$$
$$\omega^{4}-\frac{2(K_{1}+K_{2})}{m}\omega^{2}+ \frac{4K_{1}K_{2}\sin ^{2}\left( \frac{qa}{2} \right) }{m ^{2}}=0$$
$$\implies \omega^{2}= \frac{K_{1}+K_{2}}{m}\pm \sqrt[  ]{ \left( \frac{K_{1}+K_{2}}{m} \right)^{2} -\frac{4K_{1}K_{2}\sin ^{2}\left( \frac{qa}{2} \right)}{m ^{2}}}$$
$$\omega^{2}=\frac{K_{1}+K_{2}}{m}\pm \frac{K_{1}+K_{2}}{m}\sqrt[  ]{ 1-\frac{4K_{1}K_{2}\sin ^{2}\left( \frac{qa}{2} \right)}{(K_{1}+K_{2})^{2}} }$$
$$\omega^{2}=\frac{K_{1}+K_{2}}{m}\left[ 1\pm \left\{ 1-\frac{4K_{1}K_{2}\sin ^{2}\left( \frac{qa}{2} \right)}{(K_{1}+K_{2})^{2}} \right\} ^{\frac{1}{2}}  \right] $$