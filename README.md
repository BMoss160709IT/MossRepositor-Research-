# SNN for Adaptive Residential Systems - Simulation Code

**Paper:** Spiking Neural Networks for Adaptive Residential Systems: A Multi-Scale Conceptual Framework

**Authors:** Benedicto Moses Miharja, Arnoldus Purbrayen Delasabetje

---

## Quick Start

### Install dependencies (one time):

### Run simulation:


For Google Colab / Jupyter, open `code_snnforars.py` and run cell by cell.

---

## File Contents

Single file `code_snnforars.py` includes:
- Micro-scale SNN simulation (100 runs, 7 days)
- Meso-scale coordination simulation (50 runs, coordinated vs uncoordinated)
- All supporting functions (LIF neuron, R-STDP learning, differential privacy, etc.)

---

## Expected Results (from paper)

| Metric | Result (mean ± std) |
|--------|---------------------|
| Energy savings (micro) | 78.8% vs rule-based |
| Peak reduction (micro) | 57.6% vs rule-based |
| Violation rate (micro) | 6.8% |
| Peak reduction (meso) | 20.6% |

---

## Notes

The code runs out-of-the-box. Results vary slightly between runs due to random seeds (occupancy, building parameters, sensor noise).

For questions: benedictomoses1607@gmail.com

---

## AI Use Disclosure (Transparency)

AI tools (Qwen 3.6) were used **only** for:
- Docstring formatting
- Language polishing

All algorithmic logic, parameter choices, and simulation design are the original work of the authors. See AI declaration in the manuscript (page 26).
