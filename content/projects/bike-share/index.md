---
title: "Time-Series Modeling of Bike-Share Demand"
summary: "Poisson → Quasi-Poisson → NB → GAM → mixed models: understanding dispersion, zero inflation, and temporal structure."
tags:
  - Time-series
  - GAM
  - Count models
date: 2025-09-01
---

This project applied a model ladder to Washington, DC bike-share data:

1. Poisson  
2. Quasi-Poisson  
3. Negative Binomial  
4. GAM with time splines  
5. Mixed effects (weekday/month)  

Instead of focusing on predictive accuracy alone, I examined:

- Dispersion  
- Zero inflation  
- Temporal dependence  
- Residual patterns  
- Influence diagnostics  

The key lesson:  
**the shortcomings of Poisson tell you more about the data-generating process than the final model does.**
