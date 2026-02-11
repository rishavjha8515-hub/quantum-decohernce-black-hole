# 🌌 Quantum Decoherence Visualization Framework

**Interactive Educational Simulation of Quantum Decoherence in Extreme Gravitational Fields**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18604527.svg)](https://doi.org/10.5281/zenodo.18604527)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()

**Latest Version:** v3.2 (February 2026)

**Author:** Rishav Anand Kumar Jha ([ORCID: 0009-0008-4552-4154](https://orcid.org/0009-0008-4552-4154))  
**Institution:** Shri L. R. Tiwari College of Science, Commerce and Arts, Mumbai, India

---

## 🏆 Recognition

- 🥈 **Silver Medal — IRIS National Science Fair 2026**
- 📊 **Empirically Validated:** 41.5% → 82.1% learning gains (p < 0.001, Cohen's d = 2.67)
- 🌍 **Global Reach:** 1,500+ users across 30+ countries
- 📚 **Academic Impact:** OpenAIRE indexed, peer-reviewed with 30 participants
- 💯 **100% Recommendation Rate** from all study participants

---

## 📋 Overview

**Quantum Decoherence Visualization Framework** is an interactive, browser-based educational tool that demonstrates how quantum coherence degrades in extreme gravitational environments near black holes.

The simulator integrates phenomenological models grounded in established physics—including **Hawking radiation**, **gravitational tidal effects**, and **quantum vacuum fluctuations**—into a real-time interactive environment built with **HTML5, CSS3, JavaScript, and Chart.js**.

**Design Philosophy:**
- Make graduate-level quantum gravity concepts accessible to high school and undergraduate students
- Explicitly communicate phenomenological approximations and uncertainties
- Enable hands-on parameter space exploration
- Clearly distinguish established physics from phenomenological estimates

---

## ✨ What's New in v3.2 (February 2026)

### 🔬 Empirical Validation

Controlled pre-test/post-test assessment at IRIS National Fair 2026 with 30 participants (26 high school, 4 undergraduate):

- **Learning Gains:** 41.5% → 82.1% mean scores
- **Statistical Significance:** p < 0.001
- **Effect Size:** Cohen's d = 2.67 (very large)
- **Key Finding:** Equally effective across diverse baseline knowledge levels

### 🚀 Research Applications

Three prospective directions connecting educational visualization to frontier research:

1. **Quantum Error Correction Extreme Benchmarking** - Multi-channel decoherence stress-testing
2. **Space-Based Quantum Communication** - Gravitational effects on coherence windows
3. **Information Complexity Modeling** - Quantum scrambling and information paradox visualization

### 📚 Enhanced Documentation

- Complete assessment methodology and statistical analysis (24-page paper)
- Expanded theoretical framework with 25 academic references
- Comprehensive limitations analysis

---

## ⚙️ Key Features

### 🎛️ Interactive Controls

- **Black Hole Mass:** 1–1000 solar masses (M☉)
- **Observer Distance:** 1.5–10 Schwarzschild radii (rs)
- **Channel Weights:** Adjust thermal/gravitational/vacuum contributions
- **Real-Time Updates:** <50ms parameter response

### 📊 Multi-Channel Decoherence Model

**Thermal Channel (Hawking Radiation):**
```
Γ_thermal = Γ₀ × (TH/T₀) × (rs/r)^1.5
```
Dominates near horizon; inverse mass scaling

**Gravitational Channel (Tidal Forces):**
```
Γ_grav = Γ₀ × (rs/r)² × (1 + (rs/r)³)
```
Captures tidal force scaling ∝ GM/r³

**Vacuum Channel (Modified QFT):**
```
Γ_vacuum = Γ₀ × (rs/r)^2.5 × ln(r₀/r)
```
QFT in curved spacetime phenomenology

### 🎨 Visualization Features

- Particle system: Blue (coherent) → Red (decoherent) transitions
- Black hole rendering with gravitational lensing effects
- Hawking radiation visualization
- Real-time coherence meter: C(t)/C₀ decay
- Dynamic charts with explicit uncertainty bands (±50-100%)

### 💻 Technical Details

- **Platform:** 100% browser-based (HTML5/CSS3/JavaScript)
- **Code:** ~1500 lines custom physics engine
- **Visualization:** Chart.js for real-time plotting
- **Dependencies:** Zero external requirements
- **Compatibility:** Chrome, Firefox, Safari, Edge

---

## 🚀 Quick Start

### Option 1: Live Demo

Visit the deployed version: **[Live Demo](#)** *(if hosted)*

### Option 2: Local Usage

```bash
# Clone repository
git clone https://github.com/rishavjha8515-hub/quantum-decoherence-black-hole.git
cd quantum-decoherence-black-hole

# Open in browser
open black_hole_simulation.html

# Or use local server
python -m http.server 8000
# Navigate to http://localhost:8000
```

**No installation required** — just open the HTML file in a modern browser.

### Usage

1. Adjust black hole mass slider (1-1000 M☉)
2. Change observer distance (1.5-10 rs)
3. Modify channel weights if desired
4. Observe particle color transitions and real-time plots

---

## ⚠️ Limitations & Disclaimers

### What This Model IS ✓

- Educational visualization tool with empirical validation
- Phenomenological exploration with order-of-magnitude estimates
- Platform for conceptual understanding
- Transparent communication of uncertainties (±50-100%)

### What This Model IS NOT ✗

- Rigorous quantum field theory calculation
- Quantitatively precise experimental predictions
- Complete treatment of information recovery mechanisms
- Treatment of rotating or charged black holes

**Intended Use:** Physics education (high school through undergraduate), outreach, conceptual exploration

**Not Appropriate For:** Quantitative research predictions, engineering calculations, policy decisions

**See full paper (quantum_decoherence_v3.2.pdf) for detailed limitations analysis.**

---

## 📄 Full Documentation

For complete details, please see:

📝 **[quantum_decoherence_v3.2.pdf](docs/quantum_decoherence_v3.2.pdf)** (24 pages)

Includes:
- Theoretical background and equation derivations
- Complete phenomenological methodology
- Empirical validation study design and results
- Seven computational figures
- Exploratory research applications
- Comprehensive limitations and future work
- 25 academic references

---

## 📚 Citation

If you use this framework in educational or research contexts, please cite:

**APA:**
```
Jha, R. A. K. (2026). Interactive Framework for Visualizing Quantum Decoherence 
in Extreme Gravitational Fields: A Phenomenological Approach to Black Hole Physics 
and Quantum Information Science (Version 3.2). Zenodo. 
https://doi.org/10.5281/zenodo.18604527
```

**BibTeX:**
```bibtex
@software{jha2026quantum,
  author       = {Jha, Rishav Anand Kumar},
  title        = {Interactive Framework for Visualizing Quantum Decoherence 
                  in Extreme Gravitational Fields},
  month        = feb,
  year         = 2026,
  publisher    = {Zenodo},
  version      = {3.2},
  doi          = {10.5281/zenodo.18604527},
  url          = {https://doi.org/10.5281/zenodo.18604527}
}
```

---

## 📜 License

- **Source Code:** [MIT License](LICENSE)
- **Documentation:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Free to use, modify, and distribute with attribution.

---

## 🤝 Contributing

Contributions welcome! Areas of interest:

**Physics:** Kerr black holes, improved calibration, semiclassical corrections  
**Technical:** Performance optimization, mobile responsiveness, accessibility  
**Educational:** Tutorial modules, assessment tools, teacher guides

**Process:**
1. Fork repository
2. Create feature branch
3. Commit changes
4. Open Pull Request

---

## 🙏 Acknowledgments

**Thanks to:**
- IRIS National Fair 2026 organizers for facilitating empirical validation
- 30 study participants for their engagement and feedback
- Online physics education community for inspiration
- Open-source maintainers (Chart.js, Zenodo, OpenAIRE, GitHub)

---

## 📬 Contact

**Rishav Anand Kumar Jha**

📧 Email: rishavjha8515@gmail.com  
🔗 ORCID: [0009-0008-4552-4154](https://orcid.org/0009-0008-4552-4154)  
🐙 GitHub: [@rishavjha8515-hub](https://github.com/rishavjha8515-hub)  
📚 Zenodo: [10.5281/zenodo.18604527](https://doi.org/10.5281/zenodo.18604527)

**Feedback:**
- Bug reports: [GitHub Issues](https://github.com/rishavjha8515-hub/quantum-decoherence-black-hole/issues)
- General inquiries: rishavjha8515@gmail.com
- Collaboration: Email with subject "Collaboration: [Topic]"

---

<div align="center">

**Made with 🌌 for physics education and quantum information science**

**© 2026 Rishav Anand Kumar Jha · MIT License**

[⬆ Back to Top](#-quantum-decoherence-visualization-framework)

</div>

**© 2026 Rishav Anand Kumar Jha. Released under MIT License.**

[⬆ Back to Top](#-quantum-decoherence-visualization-framework)

</div>
