---
title: "Software"
permalink: /software/
author_profile: true
---

# Research software

Software is the bridge between mathematical work and reproducible scientific use. My current emphasis is on research implementations that expose algorithmic structure clearly enough to study mathematical behavior, hardware effects, and learning-assisted solver design.

## Active public development

### LearnToOptimizeGlobalvLocal — Julia

A learning-to-optimize research package for **learning how to allocate a fixed computational budget between global exploration and local exploitation** across families of optimization problems. The current scaffold represents problem instances and budgets explicitly, supports global sampling and local optimization, evaluates candidate allocations empirically, and includes a Pareto filter for competing performance criteria.

The present implementation includes uniform and Latin-hypercube sampling, gradient descent and coordinate search, configurable particle counts and local-iteration budgets, and a Rastrigin example. It is intentionally an active research scaffold rather than a finished general-purpose solver.

[Repository →](https://github.com/slavakung/LearntoOptimizeGlobalvLocal)

### FortranMultiParallelIterativeLA — Modern Fortran

A work-in-progress laboratory for **iterative linear algebra across serial CPU, OpenMP, CUDA Fortran, and coarray execution models**. The project asks how a common mathematical solver interface can span matrix formats and parallel backends while retaining persistent memory, explicit setup costs, reproducible correctness tests, and meaningful performance instrumentation.

Current capabilities include CSR/CSC/COO/dense matrix representations, structured matrix generators, conjugate gradient and preconditioned-CG interfaces, point and block relaxation schemes, OpenMP kernels, persistent CUDA matrix/vector storage, coarray distributed matvecs with compact halo exchange, and hybrid-capable builds. It is explicitly research software under active development rather than a production replacement for mature sparse-LA libraries.

[Repository →](https://github.com/slavakung/FortranMultiParallelIterativeLA)

## Collaborator and student software

**FlexCFD.** A C++23 library, developed with Anshu Kumar, for modular solution of computational-fluid-dynamics PDEs using multiple numerical methods. [Repository →](https://github.com/Anshu8879065/FlexCFD)

**Hospital robot system.** Planning–control–RL simulation for robotic health care, supervised with Monicah Cheronoi. [Repository →](https://github.com/cheropnai/hospital-robot-system)

**Prospect-theoretic human–AI games.** Repeated noncooperative games with expected-utility AI agents and prospect-theoretic human agents, supervised with Dylan Waldner and Mitchelle Luciana. [Repository →](https://github.com/rxymitchy/prospect-theory/)

## Development direction

These repositories are part of a broader software program around optimization solvers, real-time iteration / SQP, decentralized optimization, scientific computing, and hardware-aware numerical methods. Public projects will be added here as they reach a useful research-release state.

[All GitHub repositories →](https://github.com/slavakung?tab=repositories)
