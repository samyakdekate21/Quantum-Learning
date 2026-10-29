# Quantum Probability Simulator

**Day 20 — 30-Day Quantum Computing Challenge**

Compare 10, 100, 1,000 and 10,000 measurements of a Hadamard-prepared qubit. The notebook includes an ideal measurement model using NumPy and an optional Qiskit Aer circuit.

## Contents
- `Quantum_Probability_Simulator.pdf` — project explanation, sample results, execution guide and interpretation
- `quantum_probability_simulator.ipynb` — executable notebook with graphs
- `results.png` — saved visualization

## Run
1. Open the notebook in Jupyter or Google Colab.
2. Install `numpy` and `matplotlib` if necessary.
3. Run all cells to reproduce the simulation and save `results.png`.
4. Optionally install `qiskit` and `qiskit-aer` for the circuit simulator cell.

## Sample results (seed = 2026)

| Shots | Zeros | Ones | P(0) |
|---:|---:|---:|---:|
| 10 | 6 | 4 | 60.0% |
| 100 | 47 | 53 | 47.0% |
| 1,000 | 465 | 535 | 46.5% |
| 10,000 | 4,989 | 5,011 | 49.9% |

The ideal theoretical distribution is 50% / 50%. Individual measurements vary due to sampling. The NumPy model is a classical simulation of ideal quantum probabilities, not physical hardware randomness.

**Author:** Samyak Dekate
