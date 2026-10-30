# 04 · Thermal-hydraulics

*A reactor is also a heat engine — moving fission energy from a pellet to a turbine.*

## Overview

Fission releases energy; engineering turns it into electricity and, above all, **keeps the fuel cool**. This module covers how heat is generated and deposited in the core, how it travels through fuel, cladding, and coolant, the two-phase phenomena that limit power, and how plant systems tie together — ending with decay heat, the number one driver of nuclear safety systems.

## Prerequisites

- [Module 03 — Reactor physics](../03-reactor-physics/) (fission energy, power density)
- Undergraduate heat transfer (conduction, convection) — refreshed below

## Learning objectives

After this module you can:

- Describe where fission energy is deposited in fuel, coolant, and structure
- Explain the temperature field inside a fuel rod and why centerline temperature limits power
- Describe the thermal-hydraulic design of PWR and BWR primary systems
- Explain boiling regimes and critical heat flux (CHF) and why CHF limits reactor power
- Explain decay heat: magnitude after shutdown, and why it must be removed for years
- Describe natural circulation and passive safety concepts

## Topics

### 1. Heat generation in the core
- The energy budget from Module 02, revisited as heat sources: ~85–90% of fission energy deposits directly in the fuel pellets; the rest in coolant and structure via neutron slowing-down and gamma absorption
- Volumetric heat generation, power density (kW/l), and core power distribution (cosine-shaped axial, radially peaked)
- Why "hot channel" and "hot rod" analysis exists

### 2. From pellet to coolant
- Fuel rod anatomy: UO₂ pellets, helium gap, Zircaloy cladding
- Conduction with internal generation: the parabolic radial temperature profile; gap conductance as the stubborn resistance
- Centerline melting and cladding integrity as key design limits
- Convection to coolant; Dittus-Boelter intuition (no need to memorize)

### 3. Coolants and two-phase flow
- What a coolant must do: remove heat, moderate (sometimes), stay cool at high temperature, be transparent to neutrons (or not)
- PWR vs. BWR: 15.5 MPa subcooled water vs. 7 MPa boiling water; the steam generator vs. in-core boiling
- Boiling regimes: nucleate boiling (good — high heat transfer) → critical heat flux / dryout (climb of vapor blanketing) → film boiling (bad)
- **CHF/dryout as the power-limiting phenomenon**: the margin that caps reactor power
- Alternative coolants: heavy water, gas (CO₂, He), liquid metal (Na, Pb-Bi), molten salt — one paragraph each on why you'd choose them

### 4. The plant as a system
- The Rankine cycle in one page; the nuclear steam supply system
- PWR loops: reactor → steam generator → turbine → condenser → pump; pressurizer
- BWR: direct cycle; steam separators and dryers
- Load-following basics: why thermal inertia and xenon (Module 03) make reactors sluggish but stable

### 5. Decay heat & cooling after shutdown
- Decay heat: roughly 6–7% of prior full power at the moment of shutdown, ~1% after an hour, ~0.4% after a day — and measurable for years
- Why the ECCS (emergency core cooling) exists; the LOCA picture (quantitatively in Module 07)
- **Natural circulation**: density-driven flow — how some designs remove decay heat with no pumps at all
- Passive safety: AP1000 passive containment cooling, natural-circulation SMR concepts

## Key terms

| Term | Meaning |
| --- | --- |
| Power density | Thermal power per unit core volume (kW/l) |
| Gap conductance | Heat-transfer coefficient across the pellet-cladding gap |
| CHF / dryout | Boiling transition beyond which fuel cooling collapses |
| Decay heat | Residual heat from fission-product decay after shutdown |
| Natural circulation | Coolant flow driven by buoyancy, not pumps |
| ECCS | Emergency core cooling system |

## Resources

**Free**
- 📘 [MIT OCW 22.06 — Engineering of Nuclear Systems](https://ocw.mit.edu/search/?q=22.06) — systems and thermal analysis
- 📄 *DOE Fundamentals Handbook, "Thermodynamics, Heat Transfer, and Fluid Flow"* (DOE-HDBK-1012, 3 volumes) — free; excellent for refreshing heat-transfer fundamentals
- 📄 NRC NUREG-series technical training on PWR/BWR systems — [NRC doc collections](https://www.nrc.gov/reading-rm/doc-collections/nuregs/) — search for "reactor concepts" training manuals
- 🎥 [NRC YouTube — Nuclear Reactor Concepts](https://www.youtube.com/@NRCgov) — visual plant-system walkthroughs

**Standard references (not free)**
- Todreas & Kazimi, *Nuclear Systems I & II* — the thermal-hydraulics bible
- El-Wakil, *Nuclear Heat Transport* — compact classic
- Glasstone & Sesonske, *Nuclear Reactor Engineering* — plant-level view

## Self-check questions

1. Roughly what fraction of fission energy is deposited directly in the fuel pellets, and where does the rest go?
2. Sketch the radial temperature profile inside an operating fuel rod from centerline to bulk coolant. Which resistance dominates?
3. Why does nucleate boiling *help* heat transfer while film boiling destroys it?
4. Why is CHF — not fuel temperature alone — the limiting phenomenon for BWR power?
5. A 3000 MWth reactor trips. Estimate the decay heat immediately, after one hour, and after one day. Why does this number drive the entire safety-system design?
6. Explain how natural circulation can cool a shutdown reactor with no pumps, and what it requires geometrically (e.g., elevated steam generators).
7. Compare PWR and BWR: pressure, boiling location, number of loops to the turbine.

## Next

[Module 05 — Radiation detection & protection →](../05-radiation-detection-protection/)
