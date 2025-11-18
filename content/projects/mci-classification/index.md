---
title: "Multinomial & Ordinal Modeling for Cognitive Impairment Classification"
summary: "Comparing multinomial, PO, PPO, and adjacent-category models for classifying MCI subtypes with diagnostics-first workflows."
tags:
  - Statistics
  - Multinomial modeling
  - Cognitive aging
date: 2025-01-01
---

This project investigates the statistical structure of three-category cognitive-status outcomes in HRS-HCAP and Mex-Cog: **Normal**, **MCI with memory impairment**, and **MCI without memory impairment**.

I learned that model performance is driven primarily by:

- **covariate overlap**
- **class-conditional density separation**
- **identifiability under sparse categories**

I compared:

- Multinomial logistic regression  
- Proportional odds model  
- Partial proportional odds  
- Adjacent-category models  

My key insight:  
> Classification in aging datasets is mostly an issue of **overlap and latent structure**, not algorithm choice.

This project shaped my modeling philosophy of *diagnostics-first* rule: model choice follows from data structure, not the opposite.
