---
title: "Microcystis Cell Count and Toxicity Estimation"
date: 2025-01-01
weight: 60
summary: "Estimating Microcystis cell concentration and ELISA-equivalent microcystin concentration from transmitted multispectral images of controlled water samples."
methods_short: "12-band transmission MSI · PCA · Wasserstein distance descriptors · Regression"
status: completed
tags: [Research, Multispectral Imaging, Environmental Monitoring, Regression]
featured: true
cover_kind: illustrative
cover_alt: "Conceptual illustration of a water sample with cyanobacterial forms under multispectral illumination."
links:
  - type: publication
    label: Paper
    url: https://arxiv.org/abs/2611.16859
  - type: code
    url: https://github.com/SenithJayakody/microcystis-microcystin-msi.git
---

## Overview

This environmental-monitoring research investigates whether transmission-mode multispectral measurements from controlled *Microcystis* culture dilutions can be calibrated against cell concentration and ELISA-equivalent microcystin reference measurements.

## Research problem and motivation

Harmful cyanobacterial blooms create a need for practical monitoring tools. Compact optical sensing could complement established laboratory measurements, but any claim must remain within the limits of the calibration design.

## Approach and methodology

The approved manuscript describes a 12-band transmission-mode system. Its controlled calibration includes 11 concentration levels with 88 multispectral replicates and evaluates interpolation on six held-out intermediate levels with 48 replicates. Dimensionality reduction and distribution-based multispectral descriptors feed separate regression models for cell concentration and ELISA-equivalent total microcystin.

## My contribution

The available project and manuscript-conversion material confirm Sandunika's involvement in multispectral acquisition and modelling research, but no public contribution statement assigns individual tasks. The project is presented as collaborative.

## Current outcomes and limitations

The study supports a controlled calibration proof of concept. The optical system has no microcystin-selective recognition chemistry, and cell concentration and ELISA-equivalent microcystin co-vary in the dilution design. The toxin-related model is therefore an empirical calibration against ELISA-equivalent reference values—not direct molecular detection—and the results do not establish performance on natural blooms or complex water matrices.

## Technologies and methods

- Transmission-mode multispectral imaging
- Controlled culture-dilution experiments
- Dimensionality reduction
- Distribution-based spectral descriptors
- Regression modelling and held-out interpolation

## Paper and Code

- [Preprint — arXiv](https://arxiv.org/abs/2611.16859)
- [Collaborator-hosted code repository](https://github.com/SenithJayakody/microcystis-microcystin-msi.git)

*The cover is a conceptual illustration and does not depict an actual cell concentration, toxin measurement or microscopy result.*
