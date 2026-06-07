# PET Biomarker Go/No-Go Simulation

### Overview

This project is a small personal exploration of how PET imaging signals might be used in early drug development to support simple go/no-go decisions.

The idea is to compare two simplified conditions (control vs. treatment) and see how differences in signal distributions might translate into a decision rule under uncertainty.

The project is purely exploratory and does not represent a real clinical dataset or validated model.

### What the simulation does

- Generates synthetic PET-like signal data for a control group
- Generates a second group with a simulated treatment effect
- Compares the average signal between groups
- Estimates a simple effect size to describe the difference

### Decision rule

A basic threshold-based rule is used:

- If the effect is strong enough → GO  
- If the effect is weak or unclear → NO-GO  

A simple confidence score is also calculated to reflect how strongly the two distributions differ. This is only a heuristic and not a statistical inference method.

### Output

The simulation produces:
- summary statistics for both groups
- a simple GO / NO-GO decision
- a visualization of the signal distributions

### Note

This is a simplified educational model written to explore how imaging signals might be translated into decision logic. It is not based on real PET data and does not represent a clinical or predictive tool.
