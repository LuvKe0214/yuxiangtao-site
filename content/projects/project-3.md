---
title: "MicrobeViz: Microbiome Data CLI"
date: 2026-02-08
summary: "A lightweight Python CLI tool that automates the normalization and visualization of microbiome sequencing data into publication-ready heatmaps and bar charts."
tags: ["project", "Python", "Bioinformatics", "Data Visualization"]
---

## Overview
MicrobeViz is a command-line interface (CLI) tool designed to streamline the workflow for microbiology researchers. Instead of manually normalizing OTU counts in Excel, this tool automates the process of converting raw sequencing data into relative abundance and generates high-quality visualizations instantly. The focus was on building a "zero-friction" tool that turns raw CSVs into publication-grade figures in seconds.
Check out the [MicrobeViz](https://github.com/LuvKe0214/MicrobeViz) for the source code.

## What I did
**Automated Data Pipeline:** Implemented the core logic to automatically parse raw CSV datasets and perform normalization ($x_i / \sum x$) to calculate relative abundance across samples.
- **Visualization Engine:** Developed plotting functions to generate **Relative Abundance Heatmaps** for species distribution and **Stacked Bar Charts** for composition analysis, eliminating the need for complex plotting scripts.
- **CLI Architecture:** Built a user-friendly command-line interface allowing users to process datasets and export figures directly from the terminal without needing a GUI.

## Outcome
Created an open-source utility that significantly reduces the time required for initial data exploration. It provides a reproducible way to visualize microbiome community structures, suitable for quick analysis or including in research papers.