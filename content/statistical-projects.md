---
title: "Selected Statistical Projects"
summary: "A curated selection of my applied statistics work, highlighting modeling strategies, diagnostics, identifiability, and uncertainty quantification across real-world datasets."
tags: ["Statistics", "Modeling", "Causal Inference", "Bayesian", "High-Dimensional Data", "PCA", "Ordinal Models"]
date: 2025-01-01
---

## Multinomial & Ordinal Modeling for Cognitive Impairment Classification
I compared multinomial logistic regression with proportional-odds, partial-proportional-odds, and adjacent-category ordinal models across HRS-HCAP and Mex-Cog.  
This work emphasized **identifiability, class overlap, and sensitivity to missingness**, showing that reliable population-based classification depends more on **assumption diagnostics** than on model selection.  
*Keywords:* multinomial logit, ordinal models, identifiability, cognitive aging.

---

## High-Dimensional Behavioral Dynamics (Digital Cages)
Analyzed millions of actigraphy observations from digitally monitored mice using PCA, **Sparse PCA (NExOS)**, k-means, and hierarchical clustering.  
I focused on using **sparsity to enhance interpretability**, evaluating clustering stability, and addressing temporal autocorrelation in high-volume time-series data.  
*Keywords:* sparse PCA, clustering, high-dimensional inference, temporal structure.

---

## Causal Effect of Oral Health on Hearing (NHANES 2021–2023)
Estimated treatment effects using **AIPW** and **TMLE** while carefully diagnosing overlap and performing trimming regimes (e.g., restriction to 0.05–0.95 PS range).  
The project reinforced a core principle: **causal inference is assumptions-first**—estimation is only meaningful when diagnostics are satisfied.  
*Keywords:* AIPW, TMLE, overlap, trimming, survey data.

---

## Time-Series Modeling for Bike-Share Demand
Built a model ladder from Poisson → Quasi-Poisson → Negative Binomial → GAM with splines → mixed models.  
Focused on dispersion, zero inflation, and temporal patterns, and used **cross-validated RMSE and out-of-sample likelihood** to evaluate model adequacy and overfitting.  
*Keywords:* dispersion, GAM, mixed models, zero inflation, diagnostics.

---

## Bayesian Hierarchical Modeling of Work Hours
Developed a hierarchical model in Stan, emphasizing **prior design, MCMC diagnostics, LOO-CV, and posterior predictive checks**.  
Compared simulation-based inference with conjugate approximations and evaluated robustness across industries.  
This project strengthened my computational Bayesian workflow.  
*Keywords:* hierarchical Bayesian models, MCMC, LOO-CV, posterior predictive checks.
