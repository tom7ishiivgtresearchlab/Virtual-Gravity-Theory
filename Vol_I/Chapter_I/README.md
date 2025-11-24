# Virtual Gravity Theory (VGT) — Volume I / Chapter I

This folder contains the GitHub-ready package of **VGT I (Volume I / Chapter I)** in the Virtual Gravity Theory (VGT) project.

**Current Version:** verX (2025-11-24)  
**Author:** Tsutomu Ishii  
**ORCID:** [0009-0001-3019-3929](https://orcid.org/0009-0001-3019-3929)  
**Contact:** vgt.researchlab@gmail.com

---

## Overview

Virtual Gravity Theory I establishes the first empirical constraint on the time variation of Newton's gravitational constant *G* using cosmic chronometers, providing observational foundations for testing gravitational theories at cosmological scales.

## Main Results

Using 44 high-precision *H(z)* measurements from cosmic chronometers spanning redshifts 0 < *z* < 2, rigorous Bayesian MCMC analysis yields:

- **ξ = -0.00015 ± 0.00686** (68% confidence interval)
- **|ΔG/G₀| < 1.5%** at *z* = 2 (95% confidence interval)

These constraints demonstrate that Newton's gravitational constant *G* has remained constant within 1.5% precision over the past 11 billion years, fully consistent with Einstein's General Relativity.

## Structure

```
Chapter_I/
├── manuscript/
│   ├── VGT_I_manuscript.pdf  # Main article (8 pages, with embedded figures)
│   └── VGT_I_manuscript.tex  # LaTeX source (re-compilable)
├── figures/
│   ├── VGT_I_fig1_HzFit.png / .pdf      # H(z) measurements and model fits
│   ├── VGT_I_fig2_Corner.png / .pdf     # MCMC corner plot
│   └── VGT_I_fig3_GConstraint.png / .pdf # G(z)/G₀ constraint visualization
├── VGT_I_summary.md      # Executive summary
├── VGT_I_changelog.md    # Version history
└── README.md             # This file
```

All figures provided in dual format: PDF (vector) and PNG (raster, 300 DPI).

## Metadata

- **Author:** Tsutomu Ishii  
- **Affiliation:** Independent Researcher, Japan  
- **ORCID:** 0009-0001-3019-3929  
- **Contact:** vgt.researchlab@gmail.com  
- **Current Version:** ver5 (2025-11-24)  
- **Status:** Submitted to Physical Review D (not accepted)

## Scientific Summary

This work establishes empirical groundwork for understanding gravitational phenomena at cosmological scales. The analysis validates the consistency of current observational data with constant *G*, while the VGT parametrization G(z) = G₀[1 + ξ ln(1+z)] provides clear falsifiable predictions for future high-precision surveys including DESI, Euclid, JWST, and LSST.

## Methodology

- **Data:** 44 cosmic chronometer measurements (model-independent H(z) constraints)
- **Statistical Analysis:** Bayesian MCMC with 450,000 samples after burn-in
- **Convergence:** Acceptance rate 59.7%, effective sample size ~9,000
- **Model Comparison:** Akaike Information Criterion validation

## Citation

If you use materials from this work in your research, please cite:

```
Ishii, T. (2025). Virtual Gravity Theory I — Empirical Foundations. 
Submitted to Physical Review D. arXiv:XXXX.XXXXX
```

*(Note: arXiv identifier to be added upon preprint publication)*

## Technical Notes

- **LaTeX Compilation:** `pdflatex VGT_I_manuscript.tex` (run twice for references)
- **Document Class:** article (PRD-compatible formatting)
- **Figure Format:** PDF (vector) and PNG (raster, 300 DPI)
- **Bibliography:** 23 references in unified format

## License

All materials in this package are released under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to share and adapt the material with appropriate attribution.

---

**Package Version:** ver5 (2025-11-24)  
**Repository Structure:** GitHub-ready (Vol_I/Chapter_I)
