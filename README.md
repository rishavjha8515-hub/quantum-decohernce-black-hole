# Quantum Decoherence Visualization Framework

**Interactive simulation of quantum decoherence in extreme gravitational fields**

DOI: [10.5281/zenodo.17781173](https://doi.org/10.5281/zenodo.17781173) · License: MIT (code) / CC BY 4.0 (docs) · Version: v3.2 (February 2026)

Author: Rishav Anand Kumar Jha · ORCID: [0009-0008-4552-4154](https://orcid.org/0009-0008-4552-4154)

---

## Where this came from

It starts at 12:43 a.m.

Mumbai. Everyone else is asleep. One phone. 1GB of data. And a question that arrived uninvited and refused to leave:

*If a black hole destroys everything that falls into it — where does the information go?*

No teacher assigned this. No lab. No physicist in the family. I just started reading — Brian Greene, Wikipedia spirals, YouTube videos with titles I barely understood. I hit the wall every self-taught person hits: quantum mechanics says particles exist in superposition, but the world I see doesn't do that. Chairs don't exist in two places. Something kills the quantum weirdness before it reaches everyday reality.

What is it?

The Copenhagen Interpretation said measurement collapses superposition. An observer causes the wavefunction to choose. That felt like a cop-out. Who counts as an observer? Does a rock observing something collapse a wavefunction?

Then I found decoherence. Wojciech Zurek, 1970s and 80s. The answer wasn't measurement. The answer was the *environment*.

Every quantum system leaks information into its surroundings with every interaction — every photon, every air molecule, every gravitational nudge. Each interaction entangles the system with the environment. The quantum interference terms get scrambled across 10²³ particles. And once information is distributed across that many degrees of freedom, it's gone. Not destroyed. Just irreversibly dispersed.

Then the next question arrived: what does decoherence look like near a black hole? Where time dilates, Hawking radiation is itself a quantum process, and the gravitational field is extreme enough to change how fast information leaks into the environment?

Nobody had built a visualisation tool for this. Not for students. Not for people with curiosity and no lab.

So I built one.

---

## Recognition

- **Silver Medal — IRIS National Science Fair 2026**
- **Empirically validated**: 41.9% → 81.1% mean scores (n=27, p < 0.001, Cohen's d = 1.80)
- **Global reach**: 4,500+ interactions across 30+ countries (Zenodo, COUNTER-compliant)
- **100% recommendation rate** among study participants

---

## What it does

A browser-based interactive simulator that visualises how quantum coherence degrades in extreme gravitational environments near black holes. Three decoherence channels run simultaneously:

**Thermal channel (Hawking radiation):**
```
Γ_thermal = Γ₀ × (TH/T₀) × (rs/r)^1.5
```
Dominates near the horizon; scales inversely with black hole mass.

**Gravitational channel (tidal forces):**
```
Γ_grav = Γ₀ × (rs/r)² × (1 + (rs/r)³)
```
Captures tidal force scaling proportional to GM/r³.

**Vacuum channel (modified QFT):**
```
Γ_vacuum = Γ₀ × (rs/r)^2.5 × ln(r₀/r)
```
Quantum field theory phenomenology in curved spacetime.

These are phenomenological models — order-of-magnitude estimates with explicit ±50-100% uncertainty bands, not rigorous QFT calculations. The tool is honest about this.

---

## Controls

- Black hole mass: 1–1000 solar masses (M☉)
- Observer distance: 1.5–10 Schwarzschild radii
- Channel weights: adjust thermal/gravitational/vacuum contributions
- Real-time response: <50ms parameter updates

Particles transition blue (coherent) → red (decoherent) as parameters change. Coherence meter shows C(t)/C₀ decay in real time.

---

## What this is not

This is an educational tool. It is not:
- A rigorous quantum field theory calculation
- A quantitatively precise prediction tool
- A treatment of rotating or charged black holes
- Appropriate for engineering calculations or research predictions

The full limitations analysis is in the paper (quantum_decoherence_v3.2.pdf, 24 pages).

---

## Quick start

```bash
git clone https://github.com/rishavjha8515-hub/quantum-decoherence-black-hole.git
cd quantum-decoherence-black-hole
open blackhole_simulation.html
```

No installation. No dependencies. Just open the HTML file in a modern browser.

**Stack:** HTML5 / CSS3 / JavaScript / Chart.js — ~1500 lines, zero external requirements.

---

## Empirical validation

Controlled pre-test/post-test study across two independent settings (IRIS National Fair 2026 + coaching classroom):

| Metric | Value |
|--------|-------|
| Participants | 27 (26 high school, 1 undergraduate) |
| Pre-test mean | 41.9% (SD = 22.2%) |
| Post-test mean | 81.1% (SD = 15.6%) |
| Improvement | 39.3 percentage points (93.8% relative gain) |
| Statistical significance | p < 0.001 (paired t-test) |
| Effect size | Cohen's d = 1.80 (very large) |
| Recommendation rate | 100% |

Full methodology and analysis in the paper.

---

## Citation

**APA:**
Jha, R. A. K. (2026). *Interactive Framework for Visualizing Quantum Decoherence in Extreme Gravitational Fields* (Version 3.2). Zenodo. https://doi.org/10.5281/zenodo.17781173

**BibTeX:**
```bibtex
@software{jha2026quantum,
  author    = {Jha, Rishav Anand Kumar},
  title     = {Interactive Framework for Visualizing Quantum Decoherence
               in Extreme Gravitational Fields},
  month     = feb,
  year      = 2026,
  publisher = {Zenodo},
  version   = {3.2},
  doi       = {10.5281/zenodo.17781173},
  url       = {https://doi.org/10.5281/zenodo.17781173}
}
```

---

## Contact

Rishav Anand Kumar Jha · rishavjha8515@gmail.com · ORCID: 0009-0008-4552-4154

Bug reports: GitHub Issues · Collaboration: email with subject "Collaboration: [Topic]"

---

*MIT License (code) · CC BY 4.0 (documentation) · © 2026 Rishav Anand Kumar Jha*
