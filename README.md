# E114 Paper

Sanitized sharing package for:

**A Single-Expert Readout of a Reflective Worldview Register in a Mixture-of-Experts Language Model**

Author: Anonymous

## Overview

This preprint studies a routed expert in a mixture-of-experts language model:
Expert 114 at layer 14 of Qwen3.5-35B-A3B. The project asks whether a single
expert's router signal can serve as a readable marker for a broader generated
language register: text that sustains an interpretive stance toward meaning,
belief, value, existence, or the interiority of a target.

The experiments compare reflective-worldview-register generations against
matched controls, inspect the router direction and residual readouts, test a
blind auto-interpreter label, and run targeted prompts over rocks, rivers, trees,
thermostats, cats, people, all-holding, God, and an AI hidden-state follow-up.
The package is anonymized for sharing and keeps identifying author metadata out
of the source and PDF.

## Main Findings

- The recovered E114 router direction separates reflective-worldview-register
  generations from lexically matched controls with Cohen's d = 3.88.
- A blind, prompt-independent auto-interpreter recovers the broader register at
  AUC 0.937, extending the label beyond self-reference into abstract examination
  and philosophical-worldview language.
- In the target-directed prompt ladder, the strongest E114 signal appears for
  unity-style and theological/all-holding prompts; inanimate rock and thermostat
  prompts also activate the readout above the animate cat prompt.
- The AI-hidden-state follow-up remains E114-active at low intensity, landing
  between cat and river in the coherent-window ladder.
- The paper treats E114 as a model-local readout/correlate of the register, with
  controller status left open for stronger causal tests.

## Scope

This repository is a compact sharing copy of the paper and figures. It includes
the compiled preprint, LaTeX source, and figure PDFs. Large raw activation/router
tensors, model weights, environment captures, and author-identifying publication
metadata are excluded from this sanitized package.

## Contents

- `paper/e114_acl_style.pdf` - compiled preprint
- `paper/e114_acl_style.tex` - LaTeX source
- `paper/figs/` - figure PDFs used by the source
- `CITATION.cff` - sanitized citation metadata
- `LICENSE` - MIT license
