---
title: "Survey Buddy"
date: 2024-01-01
summary: "A portable terrain-mapping system supporting GPS/sensor data capture, real-time transmission and offline visualization."
tags:
  - Engineering
  - Sensor Fusion
  - Kalman Filtering
  - Signal Processing
  - Terrain Mapping
featured: false
cover_kind: illustrative
cover_alt: "Conceptual illustration of a portable field device combining positioning data with a three-dimensional terrain map."
links:
  - type: code
    url: https://github.com/sandunikalakmali/SurveyBuddy
---

## Overview

Survey Buddy is a portable terrain-mapping system for collecting coordinates and sensor observations in the field, storing them locally and visualizing a survey in real time or after data collection.

## Engineering problem

Field surveying benefits from portable acquisition and immediate feedback. The project explores a lower-cost workflow that connects a mobile sensing device with desktop mapping software.

## Approach and implementation

The documented system gathers GPS and sensor data, stores observations on an SD card and can transmit live coordinates through an nRF24L01 receiver. The companion software plots a map during collection or imports saved measurements for offline visualization. Project records also identify sensor fusion and Kalman filtering as part of the positioning workflow.

## My contribution

The repository credits Survey Tech as the developer and does not publish an individual task breakdown. Sandunika's role is therefore described as part of the collaborative engineering work.

## Outcome and limitations

The public repository documents real-time and offline mapping workflows, but it does not provide verified accuracy measurements or enough hardware detail to reproduce every component. No unsupported accuracy claim is made here.

## Technologies and methods

- GPS and field-sensor acquisition
- Sensor fusion and Kalman filtering
- nRF24L01 data transmission
- SD-card logging
- Real-time and offline terrain visualization

## Code and documentation

- [Survey Buddy repository](https://github.com/sandunikalakmali/SurveyBuddy)

*The cover is a conceptual illustration and deliberately avoids inventing undocumented device hardware.*
