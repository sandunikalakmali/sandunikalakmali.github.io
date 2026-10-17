---
title: "PixelFold"
date: 2024-01-01
weight: 70
summary: "Image and hybrid video compression using transform coding, entropy coding, and motion-compensated prediction."
tags: [Research, Image Compression, Video Compression, Signal Processing]
featured: false
links:
  - type: code
    url: https://github.com/sandunikalakmali/pixelfold-image-video-codec
---

## Research problem

PixelFold explores controllable image and video compression while retaining useful reconstruction quality at target bitrates.

## Contribution and methodology

The Python implementation uses block-based discrete cosine transforms, quantization, run-length and Huffman coding for images. Its hybrid video pipeline adds motion estimation and predictive frame coding, with adjustable quantization for rate–distortion experiments.

## Result

The public repository includes reconstructed images and decoded video frames. The listing figure is taken from those project assets.
