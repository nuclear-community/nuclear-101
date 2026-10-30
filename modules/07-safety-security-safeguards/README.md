# 07 · Safety, security & safeguards

*Why nuclear power is among the safest energy sources — and the machinery that keeps it that way.*

## Overview

"Nuclear safety" is not a vibe; it's an engineered, regulated, internationally inspected system. This module covers the three S's — **safety** (preventing accidents), **security** (preventing attacks and theft), and **safeguards** (preventing proliferation) — plus the deterministic and probabilistic methods used to reason about rare, severe events.

## Prerequisites

- [Module 04 — Thermal-hydraulics](../04-thermal-hydraulics/) (decay heat, ECCS)
- [Module 06 — Fuel cycle & waste](../06-fuel-cycle-waste/) (plutonium, proliferation basics)

## Learning objectives

After this module you can:

- Explain defense in depth and its five levels
- Describe design-basis accidents and the systems that respond to a LOCA
- Explain what a probabilistic safety assessment (PSA) computes at levels 1–3
- Compare the three major accidents (Three Mile Island, Chernobyl, Fukushima) by cause and lesson
- Describe how nuclear plants are licensed and independently regulated
- Distinguish safety, security, and safeguards, and describe IAEA safeguards tools

## Topics

### 1. Defense in depth (DiD)
- Five levels: (1) prevent deviations → (2) control abnormal operation → (3) control accidents within design basis → (4) prevent accident progression (severe accident management) → (5) mitigate radiological consequences
- **Safety culture**: the human factor — questioning attitude, reporting culture, learning organization
- Redundancy, diversity, separation, and single-failure criteria (the engineering grammar of DiD)

### 2. Design basis & accident analysis
- Postulated initiating events: LOCA (loss-of-coolant accident), transients, loss of offsite power, main steam line break
- The LOCA sequence: blowdown → refill → reflood; ECCS (accumulators, high/low-pressure injection)
- Containment: the last engineered barrier (pressure suppression in BWR Mark III / ESBWR, filtered venting)
- Safety classification of systems; qualification for harsh environments
- Severe accidents "beyond design basis": core melt, hydrogen (recombiners — a Fukushima lesson), corium coolability, IVR

### 3. Probabilistic safety assessment (PSA)
- The idea: fault trees (how systems fail) + event trees (how events progress) → frequencies
- **Level 1**: core damage frequency (CDF); **Level 2**: containment response → large release frequency (LERF); **Level 3**: offsite consequences (health, land, economics)
- Modern plant targets: CDF < 10⁻⁵–10⁻⁶ /reactor-year for new designs
- Risk-informed regulation: how PSA feeds decisions and inspection priorities
- INES scale (1–7) for communicating event severity — Three Mile Island: 5; Chernobyl & Fukushima: 7

### 4. The three accidents that shaped the field
- **Three Mile Island (1979)**: stuck-open PORV, misleading indications, operator error → partial melt, negligible offsite release. Lesson: human factors, control-room design → gave birth to modern HFE
- **Chernobyl (1986)**: positive void coefficient + control rod design flaw + test conducted outside safety envelope → prompt-critical power excursion. Lesson: inherent safety of design matters; safety culture (INSAG-1 → INSAG-7 reassessment)
- **Fukushima Daiichi (2011)**: beyond-design-basis tsunami → station blackout → decay heat → hydrogen explosions, releases. Lesson: external hazards, station blackout coping, filtered venting, "beyond design basis" thinking
- Post-accident reforms: severe accident management guidelines, FLEX portable equipment, stress tests

### 5. Regulation & licensing
- Licensing lifecycle: siting → construction → operation → decommissioning; the safety analysis report (SAR)
- Independence: regulator separate from promoter (the IAEA safety standard, not always the historical reality)
- Examples of regulators: US NRC, Finland STUK, France ASN, UK ONR — and their international peer reviews (IAEA IR missions)

### 6. Security & safeguards (the other two S's)
- **Security**: physical protection of facilities and material against adversaries; design basis threat; the Convention on the Physical Protection of Nuclear Material
- **Safeguards**: verifying the peaceful use of nuclear energy — the NPT bargain
  - IAEA Comprehensive Safeguards Agreements, the Additional Protocol (strengthened verification)
  - Tools: material balance accountancy (measure what's there), containment & surveillance (seals, cameras), environmental sampling, remote monitoring
  - The inspection challenge: detecting diversion across the entire fuel cycle (Module 06 connects here)
- The 3S framework: safety, security, safeguards — increasingly managed together

## Key terms

| Term | Meaning |
| --- | --- |
| Defense in depth | Layered prevention → mitigation of escalating conditions |
| DBA | Design-basis accident: the envelope plants must tolerate |
| PSA | Probabilistic safety assessment (levels 1–3) |
| CDF / LERF | Core damage / large early release frequencies |
| INES | International Nuclear Event Scale (1–7) |
| Additional Protocol | Strengthened IAEA inspection authority |

## Resources

**Free**
- 🌐 [IAEA Safety Standards](https://www.iaea.org/resources/safety-standards) — the SSR/GSR series, free PDFs; SSR-2/1 is the cornerstone document
- 🌐 [NRC reading room — NUREG reports](https://www.nrc.gov/reading-rm/doc-collections/nuregs/) — including NUREG-1150 (the landmark US PSA study) and accident reports
- 📄 [INSAG-7](https://www-pub.iaea.org/) — the IAEA's definitive Chernobyl reassessment; free
- 📄 [The Fukushima Daiichi Accident — IAEA report (2015)](https://www.iaea.org/topics/reviewing-safety-fukushima-daiichi) — free; the definitive technical account
- 🌐 [WENRA](https://www.wenra.org/) — Western European nuclear regulators' reference levels
- 🎥 [NRC YouTube channel](https://www.youtube.com/@NRCgov) — training videos on LOCA/ECCS concepts

**Standard references (not free)**
- Safety standards and textbooks: any graduate-level "nuclear safety" course reader
- Keller & Modarres, "A historical overview of probabilistic risk assessment" — how PSA grew from WASH-1400

## Self-check questions

1. Name the five levels of defense in depth and give one engineered example of each.
2. What does a PSA Level 2 compute that a Level 1 does not?
3. Why did TMI produce almost no offsite release despite a partial meltdown?
4. Explain the Chernobyl positive void coefficient in one paragraph, and why Western LWRs don't share that behavior.
5. What was the single failure that cascaded into the Fukushima disaster, and what industry-wide changes followed?
6. What's the difference between a safeguards inspection and a safety inspection?
7. Why must a regulator be independent from the organization promoting nuclear power?

## Next

[Module 08 — Applications & society →](../08-applications-policy/)
