---
title: "MicroCosmos-3D: Interactive GLV Simulation"
date: 2025-12-07
summary: "A real-time 3D visualization of microbial population dynamics driven by differential equations and WebGL."
tags: ["project", "Simulation", "WebGL", "Math"]
---

## Overview
MicroCosmos-3D is a "virtual laboratory" designed to visualize the mathematical beauty of ecological stability and chaos. Unlike static charts, this web application simulates a living ecosystem of 3,000+ interactive particles. It bridges the gap between computational biology and modern web engineering by rendering complex Generalized Lotka-Volterra (GLV) dynamics in real-time.
Check out the [MicroCosmos-3D](https://microcosmos-3d.vercel.app/) for the view

## What I did
**Mathematical Modeling:** Implemented a custom Euler integration solver in TypeScript to calculate the ODEs (Ordinary Differential Equations) for predator-prey interactions frame-by-frame.
- **High-Performance Rendering:** Utilized React Three Fiber and GPU instancing (InstancedMesh) to render thousands of individual agents with minimal CPU overhead.
- **Interactive Analytics:** Built a real-time data pipeline that visualizes population fluctuations via dynamic charts (Recharts) and allows users to manipulate environmental parameters to trigger ecological events like "Mass Extinction" or "Stable Equilibrium."

## Outcome
Successfully deployed a full-stack scientific visualization tool. This project demonstrates the practical application of calculus in computer science and serves as an interactive educational platform for understanding complex system dynamics.