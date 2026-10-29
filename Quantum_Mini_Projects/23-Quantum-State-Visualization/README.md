# Quantum State Visualization

**Day 23 | 30-Day Quantum Computing Challenge**

Visualize single-qubit state changes caused by X, Y, Z and H gates, plus H→Z and H→X sequences. Includes Bloch sphere plots and measurement-probability comparison.

## Files
- `Quantum_State_Visualization.pdf` — experiment guide and interpretation
- `quantum_state_visualization.ipynb` — runnable notebook
- `results.png` — Bloch sphere comparison
- `probabilities.png` — Z-basis measurement comparison

## Run
```bash
pip install numpy matplotlib notebook
jupyter notebook quantum_state_visualization.ipynb
```
Optional Qiskit verification: `pip install qiskit`.

## Expected results
- |0⟩ and Z|0⟩ point toward +z.
- X|0⟩ and Y|0⟩ point toward −z (global phase is not observable).
- H|0⟩ points toward +x, ZH|0⟩ toward −x.
- H|0⟩ and ZH|0⟩ each measure 0/1 with 50% probability in the computational basis.

Ideal statevector simulation only; no claim of quantum advantage or physical hardware execution.

**SAMYAK DEKATE**
