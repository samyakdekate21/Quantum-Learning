# Quantum Gate Playground

**Day 24 | 30-Day Quantum Computing Challenge**

Compare X, Y, Z, H, S and T gates on |0> and |+> using NumPy statevectors, measurement probabilities, and Bloch sphere vectors. Includes editable gate sequences and optional Qiskit verification.

## Files
- `Quantum_Gate_Playground.pdf` — project guide and interpretation
- `quantum_gate_playground.ipynb` — executable notebook
- `results.png` — Z-basis probability comparison
- `bloch_states.png` — Bloch sphere comparison

## Run
```bash
pip install numpy matplotlib notebook
jupyter notebook quantum_gate_playground.ipynb
```
Optional: `pip install qiskit`.

## Core lesson
Z, S and T leave |0> unchanged but modify the relative phase of superposition states. Therefore, identical Z-basis measurement probabilities do not imply identical quantum states.

All results are ideal statevector simulations; no physical quantum hardware is used.

**SAMYAK DEKATE**
