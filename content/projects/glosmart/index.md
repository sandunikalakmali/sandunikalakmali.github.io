---
title: "GloSmart"
date: 2024-01-01
summary: "A collaborative wearable cyclist-safety prototype for gesture-controlled signalling, wireless lighting and location-aware alerts."
tags:
  - Engineering
  - Embedded Systems
  - Microcontrollers
  - Assembly
featured: false
cover_kind: illustrative
cover_alt: "Conceptual illustration of a cyclist using a gesture-sensing safety glove with wireless turn signals."
links:
  - type: code
    url: https://github.com/SenithJayakody/GloSmart-Cycling-Safety-Glove
---

## Overview

GloSmart is a collaborative undergraduate embedded-system prototype intended to improve cyclist visibility through a wearable sensing glove and bicycle-mounted signalling.

## Engineering problem

Cyclists need to communicate turns while maintaining control of the bicycle. The project explores gesture sensing and wireless signalling as an engineering prototype, not as a certified road-safety product.

## Approach and implementation

An ATmega328P programmed in assembly language interprets accelerometer-based hand gestures. nRF24L01 modules connect the glove to the bicycle lighting system, while GPS and GSM modules support location-aware collision alerts.

## My contribution

The public documentation identifies GloSmart as a group undergraduate project at the University of Peradeniya. It does not assign the hardware and firmware tasks to individual team members, so Sandunika's work is described as collaborative.

## Outcome and limitations

The hardware project was completed in 2024. The collaborator-hosted repository currently documents the design but does not yet contain a complete reproducible code and hardware release.

## Technologies and methods

- ATmega328P and assembly-language firmware
- Accelerometer-based gesture sensing
- nRF24L01 wireless communication
- GPS and GSM integration
- Embedded wearable prototyping

## Project documentation

- [Collaborator-hosted repository](https://github.com/SenithJayakody/GloSmart-Cycling-Safety-Glove)

*The cover is a conceptual illustration, not a photograph or circuit diagram of the prototype.*
