# Changelog — VGT I: Empirical Foundations

All notable changes to the VGT I manuscript and materials.

---

## [Version 5] - 2025-11-24

### GitHub Repository Structure Standardization

#### Changes Made
- **Folder Naming:** Updated root folder from `Volume_I/` to `Vol_I/` to match global VGT project conventions
- **Figure Renaming:** Standardized all figure filenames to CamelCase convention:
  - `VGT_I_fig1_HzFit.png/pdf` (H(z) measurements and model fits)
  - `VGT_I_fig2_Corner.png/pdf` (MCMC corner plot)
  - `VGT_I_fig3_GConstraint.png/pdf` (G(z)/G₀ constraint)
- **LaTeX Updates:** Updated all figure references in `VGT_I_manuscript.tex` to match new filenames
- **PDF Recompilation:** Successfully recompiled manuscript with new figure paths (8 pages, all figures embedded)
- **Documentation Updates:** Updated README.md, summary, and changelog with ver5 information

#### Repository Quality
- Removed any temporary or unnecessary files
- Confirmed complete GitHub-ready package structure
- Verified LaTeX compilation with no errors
- All metadata files updated to reflect ver5 status

#### No Scientific Changes
- All scientific content, results, and analysis remain unchanged from ver4
- ξ = -0.00015 ± 0.00686 (68% CI)
- |ΔG/G₀| < 1.5% at z=2 (95% CI)
- 44 cosmic chronometer measurements

---

## [Version 4] - 2025-11-23

### Figure Naming Standardization

#### Changes Made
- **Figure Renaming:** All figures now follow the unified naming convention:
  - `VGT_I_fig1_Hz_fit.png/pdf` (H(z) measurements and model fits)
  - `VGT_I_fig2_corner.png/pdf` (MCMC corner plot)
  - `VGT_I_fig3_G_constraint.png/pdf` (G(z)/G₀ constraint)
- **LaTeX Updates:** All figure references in manuscript.tex updated to new paths
- **PDF Recompilation:** Manuscript PDF regenerated with new figure paths
- **Documentation Updates:** README.md updated with new figure filenames

#### Quality Improvements
- All figures regenerated at 300 DPI for publication quality
- Both PNG (raster) and PDF (vector) formats provided
- Consistent naming scheme for GitHub repository structure
- Compilation instructions updated in manuscript.tex

#### No Scientific Changes
- All scientific content, results, and analysis remain unchanged
- ξ = -0.00015 ± 0.00686 (68% CI)
- |ΔG/G₀| < 1.5% at z=2 (95% CI)
- 44 cosmic chronometer measurements

---

## [Version 1.0] - 2025-11-22 (Initial Release)

### Final Version for Physical Review D Submission

#### Content Added
- Complete 8-page manuscript with all sections
- Figure 1: H(z) measurements and model fits (44 data points)
- Figure 2: MCMC corner plot showing parameter posteriors
- Figure 3: G(z)/G₀ constraint visualization
- Comprehensive MCMC analysis with convergence diagnostics
- Model comparison using Akaike Information Criterion

#### Scientific Results
- **Main Result:** ξ = -0.00015 ± 0.00686 (68% CI)
- **Constraint:** |ΔG/G₀| < 1.5% at z=2 (95% CI)
- **Data:** 44 cosmic chronometer measurements (0 < z < 2)
- **Statistical Analysis:** 450,000 MCMC samples after burn-in
- **Convergence:** Acceptance rate 59.7%, effective sample size ~9,000

#### Document Quality
- LaTeX compilation: No errors or warnings
- All cross-references resolved correctly
- All figures embedded and referenced properly
- Bibliography: 23 references in unified format
- Title finalized: "Virtual Gravity Theory I — Empirical Foundations"

#### Release Package
- Complete manuscript in LaTeX and PDF formats
- Three high-resolution figures (PDF and PNG, 300 DPI)
- Summary document describing main results
- This changelog documenting version history
- All files follow standardized naming convention (VGT_I_*)

---

## [Pre-submission History]

### Phase 3 — Final Refinements (October-November 2025)
- Title updated to include "Virtual Gravity Theory I"
- Capital "I" confirmed in all instances
- Abstract refined to 150 words
- All equation numbers verified
- Figure captions enhanced for clarity
- Author information standardized across all documents

### Phase 2 — MCMC Analysis (September-October 2025)
- Implemented comprehensive Bayesian analysis
- 50,000 MCMC steps with 5,000 burn-in
- Multiple convergence diagnostics applied
- Generated corner plots and constraint visualizations
- Model comparison via AIC

### Phase 1 — Data Integration (August-September 2025)
- Compiled 44 H(z) measurements from literature
- Verified measurement uncertainties
- Excluded problematic data points
- Prepared dataset for statistical analysis

---

## Technical Notes

### Document Standards
- **LaTeX Class:** article (PRD-compatible formatting)
- **Figure Format:** PDF and PNG, 300+ DPI
- **Compilation:** pdflatex + bibtex
- **Validation:** All PRD submission requirements verified

### Quality Assurance
- Automated LaTeX error checking
- Figure resolution verification
- Reference format validation
- Cross-reference integrity checks
- Consistent naming across all files (VGT_I_* prefix)

---

**Maintained by:** Tsutomu Ishii  
**Last Updated:** November 2025  
**Status:** Submitted to Physical Review D (not accepted)
