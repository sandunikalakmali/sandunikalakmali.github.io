---
title: "Trace Energy Regularization for Diffusion Models"
date: 2025-01-01
weight: 20
summary: "Predicted-noise energy regularization for studying fidelity in denoising diffusion probabilistic models."
tags: [Research, Diffusion Models, Generative Modelling, Energy Regularization, Homepage Featured]
featured: true
cover_kind: illustrative
cover_alt: "Conceptual illustration of noisy point distributions following denoising trajectories through a diffusion process."
links:
  - type: code
    url: https://github.com/sandunikalakmali/2DEnDiff-Diffusion
  - type: manuscript
    label: Manuscript
    url: https://sandunikalakmali.github.io/publications/trace-energy-regularization/
---

## Overview

This research investigates whether regularizing the energy of a diffusion model's predicted noise can improve fidelity during denoising diffusion probabilistic model training.

## Research problem and motivation

The manuscript examines predicted-noise energy behaviour in standard DDPM training. The central motivation is to reduce energy mismatch without replacing the underlying denoising objective.

## Approach and methodology

The method augments the DDPM loss with a trace-energy regularization term. The public companion repository provides a lightweight PyTorch testbed for related two-dimensional experiments on moon, Swiss-roll, banana and concentric-moon distributions. It supports multiple noise schedules, optional exponential moving average sampling and PRDC evaluation.

The repository is supporting evidence for the research direction, not the complete implementation of every manuscript experiment.

## My contribution

Sandunika is the lead-listed author on the manuscript and maintains the related 2D experiment repository. Detailed individual responsibility for every manuscript experiment is not publicly documented, so broader work is described collaboratively.

## Current outcome

The manuscript is **under review for ICLR 2027**. It is not an accepted or published ICLR paper. The public repository enables controlled comparison between unregularized DDPM and energy-regularized variants on synthetic 2D distributions.

## Technologies and methods

- Denoising diffusion probabilistic models
- Predicted-noise energy regularization
- PyTorch and time-conditioned MLPs
- Cosine, linear and quadratic schedules
- Precision, recall, density and coverage evaluation

## Code and manuscript

- [Related 2D experiments](https://github.com/sandunikalakmali/2DEnDiff-Diffusion)
- [Research manuscript — under review](https://sandunikalakmali.github.io/publications/trace-energy-regularization/)

*The cover is a conceptual illustration, not an experimental distribution or result plot.*
