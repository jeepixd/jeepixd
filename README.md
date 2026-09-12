## 🔬 Published Research & Preprints

### [A Hybrid Two-Tier Architecture for LLM-Assisted Adaptive Video Game Boss AI](https://doi.org/10.13140/RG.2.2.33359.85929)
[![DOI](https://img.shields.io/badge/DOI-10.13140%2FRG.2.2.33359.85929-blue.svg)](https://doi.org/10.13140/RG.2.2.33359.85929)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Publication-00CCBB?logo=researchgate&logoColor=white)](https://doi.org/10.13140/RG.2.2.33359.85929)

> **Author:** Jeevsan Shrestha<br>
> **Affiliation:** School of Engineering, Pokhara University<br>
> **Permanent DOI:** [`10.13140/RG.2.2.33359.85929`](https://doi.org/10.13140/RG.2.2.33359.85929)

- **Core Problem:** Standard LLMs cannot run within strict 16–33ms frame budgets without game lag or hallucinated tactics.
- **Solution:** A confidence-gated two-tier engine architecture decoupling high-frequency tactical execution (C# FSM) from asynchronous LLM strategic planning (`Qwen2.5-Instruct`).
- **Validated Benchmarks (RTX 4060):**
  - Strategic inference: **517.85 ms** (3B) / **713.20 ms** (7B)
  - Strategic acceptance rate: **92%** (gated by safety & oscillation dampers)
  - Frame-rate impact: **0% frame drops** (deterministic 60 FPS preserved)

```bibtex
@article{shrestha2025hybrid,
  title={A Hybrid Two-Tier Architecture for LLM-Assisted Adaptive Video Game Boss AI: A Confidence-Gated Approach to Real-Time Strategic Decision-Making on Consumer Hardware},
  author={Shrestha, Jeevsan},
  journal={ResearchGate Preprint},
  year={2025},
  doi={10.13140/RG.2.2.33359.85929},
  url={https://doi.org/10.13140/RG.2.2.33359.85929}
}
