---
title: "Multispectral Soil Moisture Estimation"
date: 2024-01-01
weight: 40
summary: "Reflectance multispectral imaging for soil-moisture regression, with related work on classification under moisture-induced spectral change."
tags: [Research, Multispectral Imaging, Deep Learning, Soil Moisture Estimation]
featured: true
cover_kind: illustrative
cover_alt: "Conceptual illustration of moist soil under multiwavelength optical sensing and machine-learning analysis."
links:
  - type: code
    url: https://github.com/SenithJayakody/soil-moisture-msi
  - type: publication
    label: Paper
    url: https://doi.org/10.1109/ICATC64549.2024.11025290
---

## Overview

This collaborative project uses reflectance multispectral measurements to study how soil spectra change with water content. It includes two related but distinct research questions: continuous moisture estimation and soil classification from moisture-induced spectral dynamics.

## Research problem and motivation

Soil moisture affects agricultural decisions and also alters optical reflectance. The work investigates whether those spectral changes can support non-contact analysis without conflating a regression task with a soil-classification task.

## Approach and methodology

The 2024 study extracts features from 13 reflectance bands spanning 365–940 nm and trains a neural-network regressor for moisture content. A separate 2026 study uses moisture-induced spectral dynamics with machine learning to distinguish soils; it is not another moisture-regression experiment.

## My contribution

Sandunika is first author of the moisture-estimation paper and a co-author of the classification study. The code is hosted in collaborator Senith Jayakody's repository, so this page does not imply sole ownership.

## Key results and limitations

The 2024 publication reports R²/RMSE of 0.9987/0.5072 on test data and 0.9922/0.7517 on independent validation. These are publication-reported values for the controlled study and should not be interpreted as general field performance across unseen soils and acquisition conditions.

## Technologies and methods

- 13-band reflectance multispectral imaging
- Spectral feature extraction
- Neural-network regression
- Moisture-induced spectral analysis
- Machine-learning classification

## Related publications

- [Moisture-content regression — ICATC 2024](https://doi.org/10.1109/ICATC64549.2024.11025290)
- [Soil classification through moisture-induced spectral dynamics — ICIIS](https://doi.org/10.1109/ICIIS69028.2026.11450634)

## Code

- [Collaborator-hosted research code](https://github.com/SenithJayakody/soil-moisture-msi)

*The cover is a conceptual illustration. The original project visual is retained below.*

![Original multispectral soil-moisture project visual](research-figure-original.jpg)
