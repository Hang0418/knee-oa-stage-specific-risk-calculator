# Knee OA Stage-Specific Risk Calculator

This repository accompanies the manuscript:

**Stage-specific prediction of knee osteoarthritis progression and arthroplasty risk with real-world recalibration**

It contains only manuscript figure/table assets, summary CSV tables, reproducibility scripts, and a static research-use web calculator. Raw CHECK, OAI, or MRKR source data are not included.

## Online calculator

The static calculator is served from `index.html` and implements two stage-matched modules:

- **Early Radiographic Progression**: 24-month risk of incident KL >=2 in symptomatic baseline KL0/1 knees.
- **Knee Arthroplasty Risk**: 60-month target-knee TKA/KR risk after the OAI 24-month landmark.

MRKR is represented as a model-transport and target-cohort recalibration page rather than as a patient-facing model-entry point.

## Repository structure

```text
index.html                  Static web calculator for GitHub Pages
figures/main/               Main manuscript figures
figures/supplementary/      Supplementary Figures S1-S14
tables/main/                Main manuscript tables extracted as CSV
tables/supplementary/       Supplementary Tables S1-S25 extracted as CSV
scripts/                    Figure/table/calculator preparation scripts
screenshots/                Web-calculator screenshots used for Figure S14
```

## Use and limitations

The calculator is for research communication and reproducibility. It is not validated for treatment decisions or surgical eligibility. The threshold displays are exploratory and intended for risk enrichment, follow-up planning, and research use.

## Data availability

Only aggregate figure/table outputs are provided. Original cohort-level source data must be obtained through the relevant cohort data-access mechanisms.
