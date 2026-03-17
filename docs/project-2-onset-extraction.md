# Project 2: Successful Trial Onset Extraction

## Goal
Extract successful Go and No-go event onsets from E-Prime-derived task logs for task-fMRI analysis.

## Main variables
- `Subject`
- `Stimulus.ACC`
- `Stimulus.OnsetTime`
- `TrialType`

## Pipeline
1. Read converted task files into a pandas-friendly table.
2. Keep only successful trials where accuracy equals 1.
3. Split successful trials into Go and No-go conditions.
4. Estimate scanner-start offset using the reported 30-second initialization window.
5. Convert onset timing from milliseconds to seconds.
6. Export corrected onset values for downstream modeling.

## Reported design details
- Scanner initiation time: 30 s
- Event-related task duration: 192 s
- Approximate ITI: 2 s with jitter
- Trial totals: 72 Go and 24 No-go

## Why it matters
This stage bridges raw behavioral task logs and neuroimaging statistics. It shows practical data wrangling, timing correction, and condition-wise event construction for reproducible fMRI analysis.
