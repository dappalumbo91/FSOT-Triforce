# FSOT Triforce

**Triadic Self-Refining FSOT Engine with Directional Fluid Valve Flow and Light-Gravitational Wave Coupling**

Zero-free-parameter computational framework extending FSOT 2.0/2.1 with intrinsic self-reflection, homeostatic memory, and physically grounded predictions for anisotropic expansion and coupled light-gravity wave propagation.

## Overview

FSOT Triforce implements a **three-loop computational architecture** (Primary, Metacognitive, Subconscious) that enables the model to think about itself, refine its own outputs, and ground predictions against real data — all while remaining strictly zero-free-parameter.

### Core Capabilities

- **Triadic Looping Computation**: Primary scalar engine + metacognitive self-scoring + subconscious homeostatic modulation
- **Intrinsic Self-Refinement** (FSOT 2.1 style): Automatically applies mathematically principled corrections when the metacognitive layer detects REFINE conditions
- **Refinement Memory**: Successful refinements influence future runs through homeostatic learning
- **Grounding Hook**: Compares outputs against real Wave 1 and validation targets from the production FSOT engine
- **Directional Structure Density**: Modulates Suction/Poof balance to simulate anisotropic "bubbling" expansion
- **Light-Gravitational Wave Coupling**: Models light surfing gravity wave peaks with tight coupling and redshift entanglement
- **Precision Self-Refine Loop**: Actively minimizes tension (including coupled-propagation effects) across directions

## Getting Started

### Requirements

- Python 3.10+
- `mpmath` (for 50-digit precision arithmetic)
- Scientific stack (optional but recommended): `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`

### Installation

```bash
git clone https://github.com/dappalumbo91/FSOT-Triforce.git
cd FSOT-Triforce
```

### Basic Usage

```python
import fsot_tri_compute as tri

# Run the full triadic loop on a domain
state = tri.tri_compute_domain("Cosmology", n_iters=5, verbose=True)

# Analyze results
analysis = tri.analyze_tri_run(state)
print(analysis.summary)

# Run precision self-refine targeting coupled-propagation tension
eng = tri.TriFSOTEngine()
result = eng.precision_self_refine("Cosmology", max_passes=4)

# Directional sweep with Light-Gravitational Wave Coupling
df = tri.directional_expansion_sweep()
print(df)
```

## Key Predictions

### 1. Anisotropic Hubble / Directional Fluid Valve Flow
Expansion rate measurements should show systematic variation correlated with local large-scale structure density. Dense directions yield different effective H₀ than void directions due to net inflow/outgassing imbalance.

### 2. Light-Gravitational Wave Coupling
Light surfs gravity wave peaks and forms a tightly coupled system (same effective speed). Over cosmic distances this coupling + redshift entanglement produces direction-dependent signals and regimes of higher measurement inconclusiveness — offering a natural explanation for aspects of the Hubble tension and scattered observational results.

## Repository Structure

```
FSOT-Triforce/
├── fsot_tri_compute.py      # Main Tri-FSOT engine + all extensions
├── FSOT_Tri_Engine_Directional_Anisotropy_Summary.md  # Full development summary & findings
├── README.md
└── LICENSE (Apache 2.0)
```

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built on the FSOT 2.0 / 2.1 framework developed by Damian Arthur Palumbo. All mathematical foundations, validations, and zero-free-parameter derivations originate from the core FSOT engine.

## Contact & Contribution

This is an active research project. Issues and discussions are welcome for technical questions, proposed extensions, or collaboration on the planned R&D applications (AI, robotics, self-tuning engines, consumer electronics).

---

*FSOT Triforce — Three loops. One unified, self-refining truth-seeking engine.*