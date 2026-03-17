# Project 3: Individual- and Group-Level SPM Analysis

## Goal
Model response inhibition in an emotional Go/No-go task and interpret the resulting fMRI contrasts at both subject and group levels.

## Dataset and task
- Six adults from a de-identified course dataset
- Emotional face paradigm
- Go condition: respond to sad faces
- No-go condition: withhold response to neutral faces

## Analysis flow
1. Realignment
2. Slice-timing correction
3. Coregistration
4. Normalization
5. Smoothing
6. First-level GLM estimation
7. Contrast generation: `go`, `nogo`, `go > nogo`, `nogo > go`
8. Second-level one-sample and illustrative two-sample tests

## Findings
- Single-subject maps show visible inter-subject variability.
- Group `go > nogo` results show exploratory clusters at uncorrected thresholds.
- No corrected whole-brain significance is retained.
- Illustrative group comparisons are also not significant after correction.

## Why it matters
This stage highlights how to communicate fMRI findings responsibly. It pairs standard SPM modeling logic with careful interpretation, reporting transparency, and realistic discussion of power limitations.
