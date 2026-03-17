# Functional Brain Imaging: Response Inhibition in an Emotional Go/No-go Task

<p align="center">
  <img src="https://img.shields.io/badge/Neuroimaging-fMRI-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Analysis-SPM12-0A84FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Preprocessing-Python%20%7C%20pandas-2ea44f?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Task-Go%2FNo--go-orange?style=for-the-badge" />
</p>

<p align="center">
  A polished research portfolio repository documenting an end-to-end workflow for task-fMRI modeling, from behavioral event extraction to individual- and group-level statistical inference.
</p>

---

## Overview

This repository packages a functional brain imaging course project into a recruiter-friendly and research-ready GitHub portfolio. It follows the full analytical path from extracting successful trial onsets in task logs to modeling response inhibition with SPM-style first-level and second-level analyses.

The project is organized around an emotional Go/No-go paradigm, a classic experimental framework for studying inhibitory control, prepotent responding, and cognitive control processes that are frequently discussed in ADHD-related neuroimaging research.

## Project Story

### Project 2 — Behavioral event extraction
The first stage focuses on transforming E-Prime-derived task files into model-ready onset information. Successful trials are filtered, Go and No-go events are separated, scanner-start timing is corrected, and onset values are converted into seconds for downstream fMRI analysis.

### Project 3 — fMRI modeling and interpretation
The second stage applies an SPM-style workflow to model successful Go and No-go events, estimate task contrasts, and examine both individual-level and group-level effects. The resulting interpretation emphasizes methodological clarity, multiple-comparisons caution, and transparent discussion of small-sample limitations.

## What this repo demonstrates

- Behavioral preprocessing for neuroimaging experiments.
- Translating raw timing logs into GLM-ready regressors.
- Task-fMRI design reasoning in an event-related paradigm.
- First-level contrast generation and second-level inference.
- Scientific communication suitable for academic and industry portfolios.

## Technical Snapshot

| Area | Details |
|---|---|
| Domain | Functional MRI, cognitive control, response inhibition |
| Task | Emotional face Go/No-go |
| Preprocessing | Event filtering, scanner offset correction, onset conversion |
| Modeling | Canonical HRF, first-level contrasts, second-level t tests |
| Tools | Python, pandas, SPM-style analysis |
| Output | Portfolio-quality documentation and original reports |

## Key Results

- Successful event onset correction aligns trial timing to scanner time.
- Corrected onset series preserve realistic event-related jitter.
- Subject-level contrast maps show expected heterogeneity.
- Group-level findings are exploratory at uncorrected thresholds.
- Whole-brain corrected significance is not retained in the small-sample design.

## Repository Structure

```text
functional-brain-imaging-response-inhibition-premium/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── github-profile-text.md
│   ├── portfolio-summary.md
│   ├── project-2-onset-extraction.md
│   ├── project-3-spm-analysis.md
│   └── repo-tour.md
├── reports/
│   ├── Gnana-Midde-gam54-project-2.docx
│   └── Gnana-Midde-gam54-project-3-2.pdf
├── .gitignore
├── CITATION.cff
├── LICENSE
├── README.md
└── requirements.txt
```

## Why this is portfolio-ready

This repo is designed for clean presentation on GitHub. It tells a complete technical story, keeps the original submitted reports for evidence, and turns course work into a polished public-facing artifact that can support applications in neuroimaging, biomedical data science, computational neuroscience, and research engineering.

## Included Reports

- `reports/Gnana-Midde-gam54-project-2.docx`
- `reports/Gnana-Midde-gam54-project-3-2.pdf`

## Suggested future upgrades

- Add the original Python onset-extraction script under `src/`.
- Add SPM batch scripts or MATLAB files used in modeling.
- Export result figures into an `assets/` directory.
- Add selected screenshots of activation maps to the README.

## Citation

If you reference this repository in a portfolio, application, or report, please cite the repository and retain the original reports included in the `reports/` directory.
