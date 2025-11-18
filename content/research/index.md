---
title: "Research"
---

## Overview

My research focuses on **statistical modeling and diagnostics for real-world data**—settings where classical assumptions fail due to **floor effects, zero inflation, structural missingness, measurement heterogeneity, or imperfect covariate overlap**. I aim to build methods and workflows that make assumptions explicit, provide practical checks, and yield interpretable quantities with auditable limits.

Across cognitive aging, behavioral data, and causal inference problems, I work with the principle that rigorous statistical analysis begins with:

1. **Clarifying the scientific estimand**  
2. **Identifying the assumptions required to estimate it**  
3. **Using diagnostics to test these assumptions**  
4. **Selecting methods that remain stable when assumptions only partially hold**

This identification-first and diagnostics-first mindset guides my approach to modeling, computation, and inference.

---

## Current Research Areas

### **1. Cognitive Aging & Measurement Challenges**
Working with the Harmonized Cognitive Assessment Protocol (HCAP) in Nepal, Mexico, and the United States, I study how heterogeneity in **literacy, cultural context, and task properties** affects the validity of cognitive measures.

Key challenges:
- Floor and ceiling effects  
- Ability-linked missingness  
- Non-normal score distributions  
- Measurement heterogeneity across educational groups  

I use **CFA, distributional diagnostics, nonparametric comparisons**, and principled recoding strategies to evaluate domain validity and improve task design.

### **2. Modeling with Zero-Heavy, Non-Gaussian, and Irregular Data**
HCAP and behavioral data often violate assumptions required for classical GLM-based inference.  
My work focuses on:
- Count data with **zero inflation**  
- Heavy-tailed or skewed continuous variables  
- Temporally autocorrelated processes  
- Limited-overlap covariates in causal comparisons  

I use and develop approaches rooted in:
- **Semiparametric estimation**  
- **Shape-constrained smoothing**  
- **Graph-based diagnostics**  
- **Misspecification-robust inference**  

### **3. High-Dimensional Behavioral Time Series**
With Prof. Ivo Dinov, I analyzed high-frequency digital-cage data from 48 mice—millions of observations with strong temporal structure.

The goal was **discovering structure before modeling**, using:
- Autocorrelation and noise diagnostics  
- PCA and sparse PCA (NExOS)  
- K-means and hierarchical clustering  
- Latent behavioral mode extraction  

This work emphasized that modeling without understanding the latent structure can produce unstable or misleading results.

### **4. Causal Inference with Imperfect Overlap**
I am interested in robust causal comparisons when:
- Propensity scores cluster near 0 or 1  
- Subpopulations have limited covariate overlap  
- Outcome or treatment distributions depart from parametric assumptions  

My work uses:
- Overlap diagnostics  
- Weight truncation and stabilized weights  
- Semiparametric influence-function estimators  
- Practical checks for where inference is and is not trustworthy  

---

## Research Philosophy

Across projects, the same pattern emerges: real-world data rarely satisfy model assumptions.  
My goal is to develop methods that:

- Treat **identification** as the first step  
- Use **diagnostics** to reveal assumption failures  
- Provide **robust inference** under misspecification  
- Produce **interpretable, transparent outputs**  
- Make the limits of statistical conclusions visible rather than hidden  

I aim to integrate these ideas into open-source workflows and collaborate with domain scientists so that methods reflect real data constraints.

---

## Long-Term Goals

I hope to build a research program centered on:
- Misspecification-robust inference  
- Diagnostics as shared infrastructure  
- Shape-constrained and semiparametric modeling  
- Tools that bridge theory, computation, and applied science  

Ultimately, I aim to develop principled statistical workflows that remain useful in the imperfect but deeply important empirical settings found in social science, cognitive aging, and global health research.
