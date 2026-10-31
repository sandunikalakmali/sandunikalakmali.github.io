---
title: "Multispectral Soil Texture Classification and Composition Prediction"
date: 2026-01-01
weight: 50
summary: "Reflectance multispectral imaging for clay, silt and sand estimation, direct USDA texture classification, and composition-based indirect classification."
tags: [Research, Multispectral Imaging, Machine Learning, Soil Texture Classification, Homepage Featured]
featured: true
cover_kind: illustrative
cover_alt: "Conceptual illustration of a soil sample under multispectral illumination feeding a computational analysis system."
links:
  - type: code
    url: https://github.com/sandunikalakmali/soil-texture-msi
  - type: publication
    label: Paper
    url: https://doi.org/10.1109/ACCESS.2026.3721276
---

## Overview

This project combines reflectance multispectral imaging with machine learning to characterize soil texture without relying solely on conventional laboratory particle-size analysis.

## Research problem and motivation

Clay, silt and sand proportions influence agricultural water availability and erosion as well as geotechnical load-bearing and shrink–swell behaviour. The study asks whether controlled spectral measurements can support both continuous composition estimation and categorical USDA texture classification.

## Approach and methodology

A custom 13-band system records reflectance from 365–940 nm. The reproducible pipeline applies dark-current correction, a fixed region of interest, bounded normalization and block-level spectral feature extraction. Grouped evaluation keeps all blocks from one physical specimen in the same fold.

Three related tasks are kept distinct:

1. **Direct classification** predicts one of the twelve USDA texture classes.
2. **Composition regression** estimates clay, silt and sand percentages.
3. **Indirect classification** maps the regressed composition through the USDA texture triangle.

## My contribution

Sandunika is first author and shares equal contribution with Senith Jayakody on the associated IEEE Access article. The public sources establish shared leadership but do not assign every acquisition, software and analysis task to an individual author.

## Key results and limitations

For the documented KNN model, grouped cross-validation reports approximately 92.86% direct specimen-level accuracy and 89.41% indirect accuracy. Clay, silt and sand regression R² values are approximately 0.9869, 0.9892 and 0.9860. These results describe controlled mixtures made from three source soils; geographically independent field validation is still required.

## Technologies and methods

- 13-band reflectance multispectral imaging
- Dark-current correction and spectral feature extraction
- Grouped cross-validation and training-only preprocessing
- KNN, ensemble models and composition regression
- USDA texture-triangle mapping

## Code and publication

- [Code](https://github.com/sandunikalakmali/soil-texture-msi)
- [Paper — IEEE Access, 2026](https://doi.org/10.1109/ACCESS.2026.3721276)

*The cover is a conceptual illustration. The research figure below is retained from the original project page.*

![Original project figure for the multispectral soil-texture study](research-figure-original.jpg)
