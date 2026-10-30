# 03 · Reactor physics

*From chain reactions to criticality — the physics that makes a reactor a controllable machine.*

## Overview

A nuclear reactor is a chain reaction arranged to be **exactly as critical as you want, when you want**. This module covers the neutron life cycle, the multiplication factor, moderation, and the beautiful feedback physics (delayed neutrons, poisons, temperature coefficients) that makes reactors controllable machines rather than bombs.

## Prerequisites

- [Module 02 — Nuclear reactions & cross sections](../02-nuclear-reactions/)
- First-order differential equations

## Learning objectives

After this module you can:

- Trace the neutron life cycle and explain each factor in the four-factor and six-factor formulas
- Define *k*eff and *k*∞, and explain subcritical, critical, and supercritical states
- Explain neutron moderation and compare moderator materials
- Describe reactor kinetics with delayed neutrons, and explain why they make control possible
- Explain xenon-135 and samarium-149 poisoning and their operational consequences
- List the main reactivity control mechanisms in power reactors

## Topics

### 1. The neutron life cycle & criticality
- One generation of neutrons: fast fission → moderation → absorption in fuel vs. structure vs. leakage
- **The multiplication factor**: *k* = (neutrons in generation *n*+1) / (neutrons in generation *n*)
- Four-factor formula (*η*, *f*, *p*, *ε*) — what each factor rewards and punishes
- Six-factor formula adds fast and thermal non-leakage; the role of reflectors
- *k*eff < 1 subcritical · *k*eff = 1 critical · *k*eff > 1 supercritical
- Reactivity *ρ* = (*k* − 1)/*k*, in Δ*k*/k, and the "dollar" ($ = β)

### 2. Moderation
- Why slow neutrons fission ²³⁵U better (1/*v* cross sections)
- Elastic scattering energy loss; logarithmic energy decrement ξ per collision
- Number of collisions to thermalize: H₂O (~19), D₂O (~35), graphite (~114) — and the trade-offs
- Moderator requirements: low absorption, good scattering, stability under radiation
- Neutron spectra: thermalized Maxwellian vs. epithermal vs. fast reactors

### 3. Reactor kinetics
- Prompt neutrons live ~10⁻⁴ s — too fast to control mechanically
- **Delayed neutrons** from fission-product decay (seconds to minutes) carry the control timescale
- Point-kinetics intuition: prompt jump, reactor period, why small reactivity insertions < β are "gentle"
- Reactivity coefficients: fuel temperature (Doppler broadening — prompt negative feedback), moderator temperature, void coefficient — why negative feedback is the cornerstone of inherent safety

### 4. Neutron poisons & burnup
- **Xenon-135**: enormous thermal absorption cross section, produced directly and via ¹³⁵I decay
- Xenon transients after shutdown — the "xenon pit" and its operational implications
- Samarium-149 — the quieter cousin
- Fuel burnup (MWd/tU), fissile depletion vs. plutonium buildup, reactivity lifetime of a core
- Control mechanisms: control rods (B₄C, Ag-In-Cd), burnable poisons, soluble boron (chemical shim), and in CANDU/ RBMK the moderator itself

### 5. Beyond the point model (a map)
- Diffusion theory and transport theory — what reactor physicists actually solve
- Monte Carlo neutron transport (OpenMC, Serpent, MCNP) — the industry-standard tools, all free or available for research
- Lattice physics → core simulators: the computational pipeline of modern core design

## Key terms

| Term | Meaning |
| --- | --- |
| *k*eff | Ratio of neutrons between successive generations |
| Reactivity ρ | Deviation from criticality; the control lever |
| Moderator | Medium that slows neutrons without absorbing them |
| Dollar ($) | Reactivity equal to the delayed neutron fraction β |
| Neutron poison | Strong neutron absorber that suppresses reactivity |
| Burnup | Energy extracted per unit fuel mass (MWd/tU) |

## Resources

**Free**
- 🎥 [MIT OCW 22.05 — Neutron Science](https://ocw.mit.edu/search/?q=22.05) — moderation, diffusion, cross sections
- 📘 [MIT OCW 22.06 — Engineering of Nuclear Systems](https://ocw.mit.edu/search/?q=22.06) — systems view
- 📄 *DOE Fundamentals Handbook, "Nuclear Physics and Reactor Theory", Vol. 2* (DOE-HDBK-1019/2-92) — reactor theory at operator level, free
- 🛠️ [OpenMC](https://openmc.org/) — open-source Monte Carlo particle transport; try the quickstart and watch a k-eff converge
- 🛠️ [Serpent](https://serpent.vtt.fi/) — lattice-physics Monte Carlo (free license for research)
- 🌐 [NRC Glossary](https://www.nrc.gov/reading-rm/basic-ref/glossary.html) — crisp definitions of criticality terms

**Standard references (not free)**
- Lamarsh & Baratta, *Introduction to Nuclear Engineering*, ch. 4–7 — the classic path
- Duderstadt & Hamilton, *Nuclear Reactor Analysis* — the graduate standard
- Stacey, *Nuclear Reactor Physics* — modern and thorough

## Self-check questions

1. Write the four-factor formula and give a one-sentence physical meaning for each factor.
2. A reactor is exactly critical at full power. The operator withdraws control rods slightly. Describe what *k*eff and the neutron population do — and why the power doesn't run away instantly.
3. Why is heavy water (D₂O) a better moderator than light water for natural-uranium fuel, at the cost of more collisions to thermalize?
4. What is the Doppler effect on the ²³⁸U resonance region when fuel heats up, and why is this feedback fast and negative?
5. A reactor shuts down after running at full power. Sketch the xenon-135 concentration over the next 12 hours and explain the shape.
6. Why do PWRs use soluble boron in addition to control rods?
7. What is the physical meaning of a reactivity of exactly 1 dollar?

## Next

[Module 04 — Thermal-hydraulics →](../04-thermal-hydraulics/)
