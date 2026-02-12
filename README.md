# Iperbit-HTC3

Continuity-based streaming codec (proof of concept).

## Overview

Iperbit-HTC3 introduces a continuity-based approach to UTF-8 text compression.

Instead of relying on global redundancy or entropy-driven models, the codec operates through strictly local, deterministic transformations. Each symbol depends only on its immediate predecessor, enabling:

- True streaming operation
- Constant decoding state
- Symbol-by-symbol reversibility
- No look-ahead buffering

This repository mirrors the Zenodo release (v1.0).

## Zenodo DOI

Official archived version (v1.0):

https://doi.org/10.5281/zenodo.18552483

## Status

Proof of concept.
Research exploration of continuity-constrained encoding models.

Not intended as a replacement for existing compression standards.
