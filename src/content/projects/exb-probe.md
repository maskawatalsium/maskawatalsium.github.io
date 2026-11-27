---
title: ExB Probe for Ion-Velocity Diagnostics of Electric-Propulsion Plasmas
description: A modular Wien-filter probe that separates the ion charge states in a Hall-thruster plume by their velocity.
category: research
importance: 1
period: Sep 2025 – present
affiliation: High-Power Electric Propulsion Lab, Beijing Institute of Technology · Supervisor Prof. Zhang Zhe
methods: [Wien-filter (E×B) velocity selection, electrostatic and magnetostatic field modelling, ion trajectory tracing]
tools: [SolidWorks, COMSOL Multiphysics]
status: Ongoing — measured spectra are unpublished
figures:
  - src: /assets/img/research/exb-assembly-labelled.png
    caption: Probe assembly with the housing shown transparent — entrance collimator, magnet pair and filter electrodes, drift tube and cone collector.
  - src: /assets/img/research/exb-assembly.png
    caption: Closed housing with the collector flange, as prepared for manufacture.
  - src: /assets/img/research/exb-bfield.png
    caption: Simulated magnetic flux density and field lines across the filter section.
  - src: /assets/img/research/exb-efield.png
    caption: Simulated electric field between the deflection plates at the top of the voltage sweep.
  - src: /assets/img/research/exb-sim-model.png
    caption: Simplified probe geometry used for the field simulation.
links:
  - label: Related analysis — matrix model of the probe response
    href: /projects/exb-matrix-analysis/
---

A Hall thruster plume contains Xe⁺, Xe²⁺ and Xe³⁺ ions. An ExB probe crosses an electric and a
magnetic field so that only ions with velocity _v = E/B_ reach the collector; sweeping the plate
voltage at a fixed magnetic field turns the beam into a velocity spectrum, one peak per charge state.

I designed the probe with interchangeable entrance collimators, drift tubes, filter electrodes and a
cone collector, so resolution and signal can be traded in the experiment, and prepared the full
drawing set for fabrication. COMSOL models of the fields and of a mixed xenon beam were used to tune
the geometry. The planned test sweeps the plate voltage from 40 V to 220 V in front of a Hall
thruster, with magnetic-field mapping and sensitive collector-current measurement.
