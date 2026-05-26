# SEC/GPC Molecular Weight Analysis

Python workflows for molecular weight characterization of polymers using size exclusion chromatography (SEC) / gel permeation chromatography (GPC). 

These scripts process raw chromatogram .csv files, apply refractive index (RI) calibration curves, perform baseline correction, integrate polymer peaks, and calculate molecular weight statistics.

The workflows were developed for analysis of furanoate polyesters and related polymers in multiple solvent systems including tetrahydrofuran (THF), dimethylformamide (DMF), and hexafluoroisopropanol (HFIP).

---

## Features

- Batch SEC/GPC chromatogram processing
- RI detector calibration using polymer standards
- Adaptive polynomial baseline correction
- Peak integration over user-defined retention time ranges
- Molecular weight analysis:
  - Number-average molecular weight (Mn)
  - Weight-average molecular weight (Mw)
  - Dispersity (Đ)
- Calibration curve visualization
- Chromatogram plotting
- Automated file organization for output analysis

---

## Dependencies

Required Python packages:

```bash
pip install numpy pandas scipy matplotlib
