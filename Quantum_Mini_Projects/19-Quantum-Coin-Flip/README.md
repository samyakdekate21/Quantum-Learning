# Day 19 — Quantum Coin Flip 🎲

**30-Day Quantum Computing Challenge — Phase 1**

Prepare `|0⟩`, apply a Hadamard gate, and measure 1,000 times. The theoretical outcome probabilities are 50% / 50%; actual measured counts fluctuate.

## Files
- `quantum_coin_flip.ipynb` — runnable NumPy-based ideal measurement model plus optional Qiskit Aer circuit
- `results.png` — sample output (NumPy ideal measurement simulation, seed 19)
- `Quantum_Coin_Flip.pdf` — explanation, procedure and interpretation

## Run
Open the notebook in Jupyter or Google Colab and run all cells. Requires `numpy` and `matplotlib`. Optional Qiskit section requires `qiskit` and `qiskit-aer`.

## Sample results
With seed 19 and 1,000 shots: `0 = 483`, `1 = 517`. The numbers are sample outcomes, not exact physical probabilities.

**Author:** Samyak Dekate
