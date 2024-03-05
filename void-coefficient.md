---
id: am3vygywrxa9ppwsona334i
title: Void Coefficient
desc: ''
updated: 1709673856165
created: 1709667707937
isDir: false
---
This coefficient describes the relationship between void fraction and the
reactivity:

```{=latex}
\begin{equation}
\alpha_v = \frac{d\rho}{dx}
\end{equation}
```
cite:[@lamarshIntroductionNuclearEngineering2001]

For water reactors:

-   Positive: void fraction increases --\> reactivity increases --\>
    void fraction increases again, this is an unstable loop.
-   Negative: void fraction increases --\> reactivity decreases --\>
    void fraction decreases, this is a stable loop.

Nowadays, for all reactor to be licensed, the void coefficient should
**always** be negative. In the most severe hazard in human history
[[accident-chernobyl-1986]], the
reactor was designed with a high positive Doppler coefficient.
Additionally, the [[candu-reactors]] were also desighed
with a positive void coefficient. The [[fast-breeder-reactor]] uses lead or sodium as
coolant, it also has a positive void coefficient.

For [[sodium-cooled-fast-reactor-sfr]], it is more complex.
There are two trade-off effects.

Firstly, sodium doesn\'t moderate neutrons by absorbing neutrons.
However, sodium interect with neutrons by scattering.

For the high-energy neutrons, they interact with the sodium nucleus by [[inelastic-scattering]], which
means this is a endothermal reaction. For the low-energy neutrons, they
interact with the sodium nucleus by [[elastic-scattering]]. Therefore, when
the sodium void fraction increases, the sodium density decreases. Then,
the neutrons with high energy can not be well removed. Thus, the
neutrons becomes \"harder\" thus more energetic. And actually, neutrons
at higher energy will produce more neutrons during the fission reaction.
(This is indicated by $\eta$, which equals to the the emitted neutrons
per inducing neutron in the fission. $\eta$ must higher than 1 to reach
the critical reaction of the fission, and Uranium is the only one
natural [[fissile-material]], of
which $\eta>1$.) This effect tends to lead the void coefficient
positive.

Secondly, the increase in the void fraction leads on the other hand to
the neutron leakage. This means, the fuel receives less neutrons. This
effect tend to lead the void coefficient negative.

Nevertheless, the neutron leakage is highly dependent on the location of
the void. Void in the core: (almost) no leakage. Void around the wall:
leakage --\> negative void coefficient.

All in all, the void efficient of the sodium is complex and need to be
investigated based on different situations. A negative coefficient is
needed, but apparently, it is not easily guaranteed as negative.
