# Transpiler Benchmark: Qbraid vs Qiskit

*Status: Project Setup - Implementation Starting Soon*

## 🎯 Objective
Compare quantum circuit compilation efficiency between Qbraid and Qiskit transpilers, focusing on circuit depth optimization for NISQ-era hardware.

## 📊 Planned Analysis
- **Test Cases**: Random unitary matrices of various sizes (1-5 qubits)
- **Transpilers Compared**:
  - Qbraid's optimized transpiler (target: {U3, CNOT} gates)
  - Qiskit's default transpiler (optimization_level=3)
- **Primary Metric**: Circuit depth (lower = better for noisy hardware)
- **Secondary Metrics**: Gate count, transpilation time, circuit fidelity

## 🔬 Methodology
1. Generate random unitary operations
2. Transpile using both frameworks
3. Decompose to hardware-native gates ({U3, CNOT})
4. Compare resulting circuit depth and structure
5. Analyze implications for quantum algorithm efficiency

## 🛠️ Tools & Technologies
- **Quantum SDKs**: Qiskit 0.44+, Qbraid SDK
- **Programming**: Python, Jupyter Notebooks
- **Analysis**: NumPy, Matplotlib, Pandas
- **Visualization**: Circuit diagrams, comparative plots

## 📁 Project Structure
