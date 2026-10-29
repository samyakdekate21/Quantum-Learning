# Bell State Simulator — Day 22

**30-Day Quantum Computing Challenge | Samyak Dekate**

Prepare the Bell state `( |00> + |11> ) / sqrt(2)` using a Hadamard gate and a CNOT gate, then measure 1,000 shots and visualize the joint distribution.

## Files
- `Bell_State_Simulator.pdf` — concept, execution steps, results and review
- `bell_state_simulator.ipynb` — runnable notebook (NumPy default; optional Qiskit Aer)
- `circuit.png` — Bell-state circuit
- `results.png` — 1,000-shot results and probability heatmap

## Run
```bash
pip install numpy matplotlib notebook
jupyter notebook bell_state_simulator.ipynb
```
Run all cells from top to bottom. For optional Qiskit circuit simulation, install `qiskit qiskit-aer` and uncomment the optional cells.

## Reference run (seed=22)

| Outcome | Count |
|---|---:|
| 00 | 504 |
| 01 | 0 |
| 10 | 0 |
| 11 | 496 |

The ideal Bell state produces only `00` and `11` in the computational basis. A single-basis correlation does not by itself certify entanglement.

## Next experiment
Day 23 — Quantum State Visualization.
