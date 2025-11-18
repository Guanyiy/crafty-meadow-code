---
title: "Causal Effect of Oral Health on Hearing"
summary: "TMLE, AIPW, overlap diagnostics, and trimming strategies for NHANES 2021–2023."
tags:
  - Causal inference
  - TMLE
  - Semiparametric models
date: 2025-01-01
---

Using NHANES 2021–2023, I estimated the causal effect of poor oral health on poor hearing through:

- **AIPW**
- **TMLE**
- Propensity score overlap diagnostics
- Weight truncation (1st–99th percentiles)
- Kernel density overlap checks

One important finding was the presence of **partial-positivity violations**, where estimates changed sign under trimming.

This project taught me that causal inference is essentially a discipline of skepticism:  
diagnostics are not an afterthought—they *define* the estimand that can be trusted.
