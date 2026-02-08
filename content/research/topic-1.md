---
title: "Bioinformatics and Machine Learning"
date: 2025-07-25
summary: "Investigated microbial community stability using cNODE to predict temporal interactions and species composition."
weight: 1
---

## Context
Microbial ecosystems are highly dynamic and non-linear, making traditional statistical models insufficient for long term forecasting. The challenge lies in accurately predicting species interactions and community shifts under external perturbations, such as antibiotic pressure or environmental changes.

## What I did
- Implemented cNODE (Compositional Neural Ordinary Differential Equation) to model the continuous-time evolution of microbial abundances.
- Benchmarked the performance of neural ODEs against all methods for microbiome deep learning framework
- Simulated ecological "collateral damage" scenarios to evaluate how specific perturbations affect overall community diversity and keystone species

## Takeaways
Using compositional constraints with neural ODEs works better for microbial data than standard black-box models. This method improves accuracy on time series data and makes the results easier to interpret by modeling the actual continuous changes within the ecosystem rather than just predicting isolated data points.