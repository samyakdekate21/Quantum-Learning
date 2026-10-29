# Quantum Teleportation Simulation | Day 25

An educational three-qubit teleportation experiment demonstrating a Bell pair, Alice's two-bit measurement, and Bob's conditional X/Z corrections.

## Files
- `Quantum_Teleportation_Simulation.pdf` — concept, protocol, math, execution and interpretation.
- `quantum_teleportation_simulation.ipynb` — runnable NumPy statevector simulation and optional Qiskit circuit.
- `circuit.png` — conceptual three-qubit circuit.
- `results.png` — Alice's measurement outcome histogram (seed 25, 1,000 shots).

## Run
```bash
pip install numpy matplotlib notebook
jupyter notebook quantum_teleportation_simulation.ipynb
```
Qiskit is optional: `pip install qiskit`.

## Expected results
Four Alice outcomes with ideal probability 25% each; fidelity 1.0 after Bob's conditional correction for every branch. Observed counts fluctuate with finite shots.

**Note:** This is an ideal numerical simulation, not physical quantum hardware or instantaneous transmission.
