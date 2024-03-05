---
id: bdpft4grjhkkbejvnhl9078
title: Sodium Cooled Fast Reactor Sfr
desc: ''
updated: 1709671336527
created: 1709667707935
isDir: false
---
# Features

The SFR is actually very flexible. The [[conversion-ratio]] of the reactor can be
adjusted.

# Void Coefficient of Sodium 

Different from the normal reactors, for [[sodium-cooled-fast-reactor-sfr]], the void coefficient is
actually complex. Mostly, the void coefficient is positive. But there
are also exceptions, e.g. Toshiba Corp. reactor concept 4S, the void
coefficient is clearly negative, cite:
[@schulenbergFourthGenerationNuclear2022]
(P. 109).

There are two trade-off effects.

Firstly, sodium doesn\'t moderate neutrons by absorbing neutrons.
However, sodium interacts with neutrons by scattering.

For the high-energy neutrons, they interact with the sodium nucleus by
[[inelastic-scattering]], which
means this is an endothermal reaction. For the low-energy neutrons, they
interact with the sodium nucleus by [Elastic
Scattering](id:d59ea60c-97a5-4ec9-a5c4-fd831a1a3ba8). Therefore, when
the sodium void fraction increases, the sodium density decreases. Then,
the neutrons with high energy can not be well removed. Thus, the
neutrons become \"harder\" and thus more energetic. Actually, neutrons
at higher energy will produce more neutrons during the fission reaction.
(This is indicated by $\eta$, which equals the emitted neutrons per
inducing neutron in the fission. $\eta$ must be higher than 1 to reach
the critical reaction of the fission, and Uranium is the only natural
[[fissile-material]], of which
$\eta>1$.) This effect tends to lead to the void coefficient being
positive.

Secondly, the increase in the void fraction leads on the other hand to
the neutron leakage. This means the fuel receives less neutrons. This
effect tends to lead to the void coefficient negative.

Nevertheless, the neutron leakage is highly dependent on the location of
the void. Void in the core: (almost) no leakage. Void around the wall:
leakage --\> negative void coefficient.

All in all, the void efficiency of the sodium is complex and needs to be
investigated based on different situations. A negative coefficient is
needed, but apparently, it is not easily guaranteed as negative.

This section is cited from
[@lamarshIntroductionNuclearEngineering2001]
(P. 375)

# [[two-phase-flow-in-sfr]]
