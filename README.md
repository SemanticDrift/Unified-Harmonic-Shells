# Unified Harmonic Shells (UHS)

**Series:** Harmonic Structures in Natural Systems
**Author:** Carolina Johnson (CJ)
**Date:** December 2025
**License:** CC BY 4.0, Attribution required
**DOI:** https://doi.org/10.5281/zenodo.18307184
**ORCID:** https://orcid.org/0009-0002-8819-3347

## What This Does

Shells are not passive spatial boundaries; they are candidate nodes of phase-locked harmonic resonance. UHS establishes a radial quantization law derived by composing the curvature-frequency mapping of The Phi-Operator (Λ²·Φ) with discrete harmonic boundary conditions, positioned within the Stratified Axiomatics hierarchy.

The resulting sequence is calibrated against the atomic K-shell scale (the Bohr radius, a₀) and shown to admit a defined closure relation consistent with the Bohr model's n²a₀ radius scaling. This paper establishes the mathematical foundation only: the radial law, its atomic calibration, and its formal shell-classification conditions. Application beyond the atomic calibration case is left to dependent papers in the series.

## The Core Law

UHS imports the differential mapping established by The Phi-Operator:

f(r) = Λ² · Φ(r) = Λ² / r^(3/2)

Discrete shell layers emerge when the system's characteristic frequency locks into an allowed harmonic state, governed by a fundamental mode f₀ and discrete harmonic order n ∈ ℕ:

f_n = n · f₀

Inverting for the quantized radial shell distance:

r_n = (Λ² / (n · f₀))^(2/3)

`r_n` decreases as `n` increases: higher harmonic order corresponds to tighter binding at smaller radius.

## K-Shell Calibration

Setting the n=1 internal node to the Bohr radius a₀ calibrates the sequence for the atomic case:

r_n = a₀ / n^(2/3)

K-shell (n=1): 1.000a₀
L-shell (n=2): 0.630a₀
M-shell (n=3): 0.480a₀
N-shell (n=4): 0.397a₀

The outer spatial boundary is defined via a structural closure relation:

⟨r_n⟩ = a₀ · (a₀/r_n)³ = a₀ · n²

This closure is a defined structural identity within UHS, not an independent first-principles derivation of the Bohr model's n²a₀ scaling. UHS does not derive the K-shell; it calibrates against it and shows the resulting sequence closes consistently.

## Shell Conditions

A radial layer is classified as a candidate stable harmonic shell when it satisfies three tier-stratified constraints:

- **Frequency Quantization:** f_n ∈ {n·f₀ | n ∈ ℕ}
- **Curvature Matching:** χ_n = 1/r_n = (n·f₀/Λ²)^(2/3)
- **Phase Closure:** ∮ k(r) dr = 2πm along a closed phase path, where k(r) is the local wavenumber and m ∈ ℤ

## Dependencies

| Framework | DOI |
|---|---|
| Stratified Axiomatics | https://doi.org/10.5281/zenodo.18227025 |
| The Φ-Operator (Λ²·Φ) | https://doi.org/10.5281/zenodo.18484604 |

Full publication list: https://www.SemanticDrift.net

## Repository Contents

- `README.md` — this file
- `Unified Harmonic Shells (UHS).pdf` — full paper

## Citation
```
Johnson, C. (2025). *Unified Harmonic Shells (UHS)*.
Series: Harmonic Structures in Natural Systems. SemanticShift.
DOI: https://doi.org/10.5281/zenodo.18307184
License: CC BY 4.0
```

## License

© 2025 Carolina Johnson (CJ)
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)
Attribution required. https://creativecommons.org/licenses/by/4.0/
