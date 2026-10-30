# 05 · Radiation detection & protection

*Seeing the invisible — and working safely with ionizing radiation.*

## Overview

Nuclear work stands on two pillars: **measuring** radiation reliably, and **protecting** people from it rigorously. This module covers how radiation interacts with matter (the physics behind every detector), the main detector families, the dosimetry quantities that quantify harm, and the shielding and work practices — ALARA — that keep doses as low as reasonably achievable.

## Prerequisites

- [Module 01 — Nuclear physics foundations](../01-nuclear-physics-foundations/) (decay modes)
- [Module 02 — Nuclear reactions & cross sections](../02-nuclear-reactions/) (cross sections)

## Learning objectives

After this module you can:

- Explain how alpha, beta, gamma, and neutron radiation interact with matter and lose energy
- Describe the operating principles of GM, proportional, scintillation, and semiconductor detectors, and when to use each
- Distinguish exposure, kerma, absorbed dose (Gy), equivalent dose (Sv), and effective dose
- Apply the ICRP dose limits for workers and the public
- Design shielding for each radiation type and justify material choices
- Explain ALARA and apply time–distance–shielding reasoning to work planning

## Topics

### 1. Radiation interactions with matter
- **Charged particles** (α, β): ionization and excitation; Bragg peak; range (α: micrometers; β: millimeters); bremsstrahlung from beta — why plastic goes before lead
- **Photons** (γ, X): photoelectric effect (dominant at low energy, ∝ Z⁴⁻⁵), Compton scattering (mid energies), pair production (> 1.022 MeV); exponential attenuation, half-value layer (HVL), tenth-value layer (TVL)
- **Neutrons**: moderation by elastic scattering in hydrogenous media; capture (with gamma emission); boron, cadmium, gadolinium as absorbers
- Why "radiation type" determines everything about detection and shielding

### 2. Detectors
- The universal principle: ionizing radiation leaves ionization or excitation; detectors convert it to a signal
- **Gas detectors**: ionization chamber (dose), proportional counter (spectroscopy, neutron counting via BF₃/³He), GM tube (cheap, rugged, count-rate only)
- **Scintillators**: NaI(Tl), organic plastics; PMT/SiPM readout; gamma spectroscopy with NaI — the workhorse
- **Semiconductors**: HPGe for high-resolution spectroscopy; Si diodes for dosimetry
- Counting statistics: Poisson statistics, √N uncertainty, dead time, efficiency
- Neutron detection: proportional counters with ³He/BF₃, activation foams, Bonner spheres (awareness level)

### 3. Dosimetry — quantifying harm
- The chain: **exposure/kerma → absorbed dose (Gy = J/kg) → equivalent dose (Sv, ×w_R) → effective dose (Sv, ×w_T)**
- Radiation weighting factors w_R (α: 20; γ/β: 1; neutrons: energy-dependent, 2.5–21) and tissue weighting factors w_T
- Dose rate, committed dose, dose from intake (ingestion/inhalation)
- **ICRP 103 limits** (typical regulatory values): workers 20 mSv/yr averaged (max 50 mSv in a year); public 1 mSv/yr; higher limits for the lens/skin/extremities
- Natural background: ~2–3 mSv/yr typical (cosmic, terrestrial, radon, internal K-40) — context for every number above

### 4. Shielding & ALARA
- Alpha: stopped by paper or skin — internal hazard only
- Beta: plastic or aluminum (range ~cm); add outer lead only if bremsstrahlung matters
- Gamma: lead (dense), concrete or water (cheap, structural); HVL/TVL arithmetic; build-up factor awareness
- Neutrons: hydrogenous material to slow + absorber (borated polyethylene, cadmium) to capture
- **ALARA**: time, distance (inverse-square law), shielding; work planning, dosimetry programs, zone classification
- Contamination vs. irradiation — a distinction the public constantly mixes up

## Key terms

| Term | Meaning |
| --- | --- |
| Absorbed dose (Gy) | Energy deposited per unit mass |
| Equivalent dose (Sv) | Absorbed dose × radiation weighting factor |
| Effective dose (Sv) | Weighted sum over tissues; the "whole-person" number |
| HVL / TVL | Material thickness halving / attenuating by 10× |
| ALARA | As Low As Reasonably Achievable |
| Contamination | Radioactive material where it shouldn't be (vs. irradiation) |

## Resources

**Free**
- 🎥 [MIT OCW 22.01](https://ocw.mit.edu/search/?q=22.01) — the ionizing-radiation and interaction lectures map directly to §1
- 📄 [IAEA "Radiation, People and the Environment"](https://www.iaea.org/publications) — free booklet; superb for §3 intuition
- 📄 [ICRP Publication 103 summary](https://www.icrp.org/) — the basis of modern dose limits
- 📄 NRC NUREG/BR-0024? → better: [NRC "Radiation Protection" page & glossary](https://www.nrc.gov/about-nrc/radiation.html) — regulator's plain-language explanations
- 🎥 YouTube — search "NaI gamma spectroscopy demo" for hands-on detector intuition

**Standard references (not free)**
- Knoll, *Radiation Detection and Measurement* — the detection bible
- Turner, *Atoms, Radiation, and Radiation Protection* — protection physics
- Martin, *Physics for Radiation Protection* — practical depth

## Self-check questions

1. Why is an alpha emitter essentially harmless outside the body but among the most dangerous inside it?
2. A 2 MeV gamma source sits behind 3 half-value layers of concrete. What fraction of the intensity remains?
3. Why do we place plastic shielding *before* lead when shielding a high-energy beta source?
4. An absorbed dose of 10 mGy from alphas vs. 10 mGy from gammas: which has the higher equivalent dose, and by how much?
5. Why does neutron shielding need hydrogenous material *plus* an absorber, while gamma shielding just needs dense material?
6. A task takes 4 hours at 25 μSv/h. Name three ways to reduce the dose and estimate one of them.
7. Explain the difference between being irradiated and being contaminated.

## Next

[Module 06 — Fuel cycle & waste →](../06-fuel-cycle-waste/)
