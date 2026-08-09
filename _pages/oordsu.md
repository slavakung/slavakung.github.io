---
title: "OORDSU"
permalink: /oordsu/
author_profile: true
---

<p class="eyebrow">OFFLINE-HPC → ONLINE-EMBEDDED</p>
# Real-time data-driven sequential decision making under uncertainty

![OORDSU research architecture](/images/oordsu.png){: .oordsu-figure }

**OORDSU** is an organizing research program for moving from computationally intensive **offline** analysis to safe, adaptive **online** decisions on embedded systems. The problem is not merely to train a model on a supercomputer and deploy it. The central question is how models, policies, data, uncertainty representations, and safety information should be **transferred, compressed, adapted, and updated** as the deployed system senses and acts in a stochastic environment.

## The research loop

1. **Offline / HPC:** build models, policies, uncertainty descriptions, reference trajectories, reduced representations, and simulation-derived data.
2. **Transfer & adapt:** identify what can be carried to embedded hardware while preserving decision-relevant information.
3. **Online / embedded:** sense, act, and adapt under latency, memory, power, and communication constraints.
4. **Feedback:** use deployment data, residuals, failures, rare events, and changing conditions to improve offline models and policies.

## Mathematical themes

OORDSU draws on stochastic and nonlinear optimization, model predictive control, reinforcement learning, Bayesian and distributional uncertainty, rare-event risk, numerical PDEs, reduced-order modeling, and parallel/distributed computation. A particular interest is **safe and robust autonomy**: algorithms should know what they do not know, expose meaningful failure modes, and exploit expensive computation before deployment without assuming the world remains static afterward.

## Representative work

- *Mission-Aligned Learning-Informed Control of Autonomous Systems: Formulation and Foundations* (2025).
- *A Three-Tier Time-Scale Architecture for Controlling Complex Nonlinear Systems* (2026).
- *Multistage Stochastic Programming for Rare Event Risk Mitigation in Power Systems Management* (2026).
- *Towards Real Time Control of Water Engineering with Nonlinear Hyperbolic Partial Differential Equations* (2025).

See the [publications page](/publications/) for the broader research program.
