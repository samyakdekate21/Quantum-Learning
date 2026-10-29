# Grover Search Simulation

**Day 26 — 30-Day Quantum Computing Challenge**  
**Author:** Samyak Dekate

A small, reproducible implementation of Grover's search algorithm over four bitstrings: `00`, `01`, `10`, `11`. The marked target is `10`.

## Files
- `Grover_Search_Simulation.pdf` — project notes and execution guide
- `grover_search_simulation.ipynb` — runnable experiment with NumPy and optional Qiskit Aer
- `results.png` — before/after measurement histograms
- `circuit.png` — algorithm workflow illustration
- `requirements.txt` — Python dependencies

## Run
```bash
pip install -r requirements.txt
jupyter notebook grover_search_simulation.ipynb
```
Run the cells in order. The primary simulation uses NumPy, so Qiskit is not needed. Install `qiskit qiskit-aer` only for the optional circuit experiment.

## Expected result
The initial ideal distribution is 25% per state. After one oracle-plus-diffusion iteration, the ideal target probability is 100%. The actual pre-Grover sampled frequencies fluctuate around 25%; the post-Grover ideal simulator returns `10` in every shot.

**Important:** This is a noiseless teaching example. It is not evidence of quantum advantage over a classical computer, and its perfect success is specific to this four-item example.
