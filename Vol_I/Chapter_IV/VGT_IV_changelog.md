# VGT IV Changelog

This document tracks the version history and modifications made to VGT IV (Volume I / Chapter IV).

---

## 2025-11-24 — ver1 (GitHub Ready)

**Release Type:** Initial GitHub Release

### Changes Made

#### Manuscript Organization
- Unified manuscript into `VGT_IV_manuscript.tex` with all figures included
- Source: Based on `VGT_IV_Manuscript_NEW.tex` (improved version with ORCID)
- Added `\graphicspath{{../figures/}}` for proper figure referencing
- Updated figure references to use new standardized filenames

#### Figure Standardization
- Standardized figure filenames to `VGT_IV_fig[N]_[Description].png` format
- Updated all `\includegraphics` commands in LaTeX source
- Organized figures into dedicated `figures/` folder

| Original Filename | New Filename |
|-------------------|--------------|
| `Ishii_VGT_IV_HypA_SelfEnergy_Plot.png` | `VGT_IV_fig1_HypA_SelfEnergy.png` |
| `Ishii_VGT_IV_HypA_RGE_Flow.png` | `VGT_IV_fig2_HypA_RGEFlow.png` |
| `Ishii_VGT_IV_HypB_SelfEnergy_Plot.png` | `VGT_IV_fig3_HypB_SelfEnergy.png` |
| `Ishii_VGT_IV_HypB_RGE_Flow.png` | `VGT_IV_fig4_HypB_RGEFlow.png` |
| `Ishii_VGT_IV_Causality_Checks.png` | `VGT_IV_fig5_CausalityChecks.png` |

#### Documentation
- Created `README.md` with project overview and folder structure
- Created `VGT_IV_summary.md` with detailed scientific summary
- Created `VGT_IV_changelog.md` (this file)

#### Folder Structure
- Created dedicated `manuscript/` and `figures/` folders
- Moved original materials to `VGT_IV_archive_original_materials/` (not in Chapter_IV)

---

## 2025-11-06 — Kaizen a_1 (PRD Figure Integration)

**Release Type:** PRD Submission Preparation

### Changes Made

- Integrated all 5 figures into single PDF per PRD editorial request
- Created `VGT_IV_Complete_With_All_Figures.pdf` (903 KB)
- Figures placed in appropriate sections:
  - Figures 1-2 (Self-Energy): After Section 3
  - Figure 3 (Causality): After Section 4
  - Figures 4-5 (RG Flow): After Section 5
- Generated `Paper_IV_Figure_Integration_Report.md`
- Created `PRD_Resubmission_Quick_Guide.md`

---

## 2025-11-03 — Original Submission

**Release Type:** Initial PRD Submission

### Files Submitted

- `VGT_IV_Manuscript.tex` — Original manuscript
- `VGT_IV_Manuscript_NEW.tex` — Corrected version with ORCID
- `VGT_IV_Cover_Letter_FINAL.tex` — Cover letter
- `Ishii_VGT_IV_References.bib` — Bibliography
- 5 figure files (PNG format)

### Manuscript Details

- Title: "Virtual Gravity Theory IV: Autonomous Completion through Self-Consistent Running Coupling Dynamics"
- Author: Tsutomu Ishii
- Submission ID: es2025nov03_588

---

## Version Comparison

| Version | Date | Status | Key Changes |
|---------|------|--------|-------------|
| Original | 2025-11-03 | PRD Submitted | Initial manuscript |
| Kaizen a_1 | 2025-11-06 | Figures Integrated | PDF with all figures |
| **ver1** | **2025-11-24** | **GitHub Ready** | Standardized structure |

---

## Planned Future Updates

- **ver2**: Post-PRD review revisions (if required)
- **ver3**: Final published version synchronization

---

*Last updated: 2025-11-24*
