---
title: Matrix Analysis for ExB Probe IVDF Reconstruction
description: A linear-algebra view of what an ExB probe actually measures, and how to recover the true ion velocity distribution from it.
importance: 3
img: /assets/img/projects/matrix-preview.png
period: Dec 2025
affiliation: Graduate analytical project · Beijing Institute of Technology
methods: [Response-matrix model, SVD and conditioning, Tikhonov regularisation, non-negative least squares]
links:
  - label: The ExB probe this supports
    href: /research/#exb-probe
---

An ExB spectrum is not the ion velocity distribution: finite pass-band, collimator geometry and
non-uniform fields broaden peaks, merge charge states and bias the velocity scale. I wrote the
measurement as a linear model

$$
\mathbf{g} = \mathbf{T}\,\mathbf{f}, \qquad \mathbf{f} \ge 0,
$$

with **f** the true distribution, **g** the measured spectrum and **T** the probe's response matrix.

- The singular-value decay of **T** sets how much fine structure can be recovered and how noise is
  amplified.
- Plain least squares oscillates; Tikhonov smoothing with a non-negativity constraint gives stable,
  physical reconstructions.
- Shortening the collimator and drift sections can merge two charge-state peaks and sharply worsen
  conditioning, so measured peak widths cannot be read as velocity spread without deconvolution.
