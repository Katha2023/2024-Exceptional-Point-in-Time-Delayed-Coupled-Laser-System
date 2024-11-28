# Computational Exploration of Quantum Dynamics

This project delves into the time evolution and spectral analysis of wavefunctions under varying dissipation rates (`γ`) in quantum systems. The primary objectives include solving coupled differential equations for `ψ₁` and `ψ₂` and exploring their behavior in both time and frequency domains.

## Features
1. **Time Evolution Analysis**:
   - Numerical integration of Schrödinger-like equations using the Euler-Cromer method.
   - Visualization of the probabilities \( |\psi_1(t)|^2 \) and \( |\psi_2(t)|^2 \) over time.

2. **Spectral Analysis**:
   - Application of FFT to investigate frequency domain characteristics.
   - Identification of peak frequencies to reveal dominant dynamics.

3. **Hamiltonian Analysis**:
   - Computation of eigenvalues and eigenvectors for different \( \gamma \).
   - Orthogonality checks to understand quantum coherence and dissipation effects.

4. **Advanced Visualization**:
   - High-quality plots with detailed annotations and dynamic subplots.
   - Complex plane representation of eigenvalues, shaded by dissipation strength.

## Methods
- **Numerical Integration**: Implemented using Python libraries such as `numpy` and `matplotlib`.
- **FFT Analysis**: Explored spectral properties using `numpy.fft`.
- **Linear Algebra**: Eigenvalue computations conducted with `numpy.linalg`.

## Applications
This project provides insights into dissipative quantum systems and can be extended to:
- Quantum thermodynamics.
- Open quantum system simulations.
- Lindbladian exceptional point analysis.

**Tools**: Python, Matplotlib, NumPy, SciPy.
