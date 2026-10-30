# 02 · Nuclear reactions & cross sections

*How nuclei interact — and why splitting a uranium nucleus releases two hundred million electron-volts.*

## Overview

Nuclear engineering is, at its core, the engineering of **nuclear reactions**. This module covers the vocabulary of reactions — cross sections, *Q*-values, flux — then goes deep on the two reactions that matter most to our field: **neutron-induced fission** and **fusion**.

## Prerequisites

- [Module 01 — Nuclear physics foundations](../01-nuclear-physics-foundations/)
- Basic differential calculus

## Learning objectives

After this module you can:

- Classify nuclear reactions and compute their *Q*-values
- Explain what a cross section measures, and distinguish microscopic from macroscopic cross sections
- Describe the energy dependence of neutron cross sections (1/*v* region, resonances, fast region)
- Explain the fission process, its energy release (~200 MeV), and the origin of prompt and delayed neutrons
- Explain the physical basis of fusion and why it requires extreme conditions

## Topics

### 1. The language of reactions
- Reaction notation: *a + X → Y + b*, compound nucleus picture
- *Q*-value from mass tables; exothermic vs. endothermic reactions
- Conservation laws: nucleon number, charge, energy, momentum

### 2. Cross sections & neutron flux
- Cross section σ as an "effective area": probability of interaction per fluence (measured in barns, 1 b = 10⁻²⁸ m²)
- Reaction types: scattering (elastic, inelastic), absorption (capture, fission, (n,p), (n,α)…)
- **Macroscopic cross section** Σ = *N*σ and its meaning: probability per path length
- Neutron flux φ = *nv*; reaction rate *R* = Σφ
- Energy dependence: the 1/*v* region, resonance region (Breit-Wigner intuition), fast region
- Why cross sections are tabulated by evaluated nuclear data libraries (ENDF, JEFF, JENDL)

### 3. Fission
- Why heavy nuclei fission: the liquid-drop picture, Coulomb vs. surface tension
- Neutron-induced fission of ²³⁵U and ²³⁸U: thermal vs. fast threshold behavior
- Fission fragments: asymmetric mass split, neutron-rich, radioactive
- **The ~200 MeV budget**: ~168 MeV fission-fragment kinetic energy, prompt neutrons and gammas, and the delayed part (beta decays of fragments) — where the energy is deposited
- Prompt vs. delayed neutrons; the delayed neutron fraction β (≈ 0.0065 for ²³⁵U) — a number you will meet again in reactor kinetics
- Fissile vs. fertile nuclides (²³⁵U, ²³⁹Pu, ²³³U vs. ²³⁸U, ²³²Th) and breeding

### 4. Fusion
- The D-T reaction (17.6 MeV) and D-D reactions; why D-T is the easiest
- Coulomb barrier and the need for high temperature (~10⁸ K) — kinetic energy vs. barrier
- How stars do it (slow p-p chain) vs. how we try (thermal plasmas, magnetic/inertial confinement)
- Energy release per unit mass vs. fission — and why engineering fusion is harder

## Key terms

| Term | Meaning |
| --- | --- |
| Cross section σ | Effective target area for a reaction (barns) |
| Macroscopic cross section Σ | Reaction probability per unit path length in a material |
| Neutron flux φ | Neutrons per cm² per second; the "traffic" a material sees |
| Fissile nuclide | Can fission with thermal neutrons (²³⁵U, ²³⁹Pu, ²³³U) |
| Fertile nuclide | Converts to fissile after neutron capture (²³⁸U → ²³⁹Pu) |
| Delayed neutron fraction β | Fraction of fission neutrons emitted seconds-to-minutes later |

## Resources

**Free**
- 🎥 [MIT OCW 22.01](https://ocw.mit.edu/search/?q=22.01) — fission lectures map to §3
- 📘 [MIT OCW 22.05 — Neutron Science](https://ocw.mit.edu/search/?q=22.05) and 22.101 — deeper on neutron interactions
- 📄 *DOE Fundamentals Handbook, "Nuclear Physics and Reactor Theory", Vol. 1–2* (DOE-HDBK-1019) — free; Vol. 1 covers cross sections and fission cleanly
- 🌐 [IAEA Nuclear Data Services](https://www-nds.iaea.org/) — evaluated data libraries
- 🛠️ [JANIS](https://www.oecd-nea.org/tools/abstract/detail/nea-1998/) — NEA's free Java tool for plotting cross sections from evaluated libraries (try plotting σ_f of ²³⁵U vs. ²³⁸U)

**Standard references (not free)**
- Lamarsh & Baratta, *Introduction to Nuclear Engineering*, ch. 2–3 and 6
- Krane, *Introductory Nuclear Physics* — reactions and cross section formalism
- Duderstadt & Hamilton, *Nuclear Reactor Analysis*, ch. 1–2

## Self-check questions

1. Why can ²³⁵U sustain a chain reaction with slow neutrons while ²³⁸U cannot?
2. The macroscopic cross section of a material doubles when its density doubles. Why?
3. In the 1/*v* region, what happens to the absorption rate in a moderator as it cools down? What does this imply for reactor temperature feedback (intuition only)?
4. Where does the ~200 MeV of fission energy physically end up? Which part is deposited in the fuel itself?
5. Why are fission fragments neutron-rich, and what does that imply about their radioactivity?
6. Why is the delayed neutron fraction so important that reactor control would be practically impossible without it? (Qualitative — kinetics is Module 03.)
7. Why does D-T fusion require ~100 million kelvin while chemical reactions need only ~1000 K?

## Next

[Module 03 — Reactor physics →](../03-reactor-physics/)
