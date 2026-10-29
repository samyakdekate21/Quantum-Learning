# Quantum Random Number Generator — Day 21

Mini-project for the **30-Day Quantum Computing Challenge**. Generate a configurable sequence of binary outcomes from an ideal 50/50 qubit measurement model.

## Files
- `Quantum_Random_Number_Generator.pdf` — concept, procedure, interpretation, limitations
- `quantum_random_number_generator.ipynb` — executable notebook, plots, optional Qiskit Aer circuit
- `results.png` — sample seeded experiment visualization

## Run
```bash
pip install numpy matplotlib jupyter
jupyter notebook quantum_random_number_generator.ipynb
```
Optional Qiskit Aer circuit: `pip install qiskit qiskit-aer`.

## Sample run
- Number of bits: **100**
- Seed: **2026**
- Zeros: **53**; ones: **47**

**Accuracy note:** The default experiment uses NumPy pseudorandom sampling of the ideal quantum measurement distribution; Qiskit Aer is a circuit simulator. Neither constitutes a certified physical quantum random-number source.
