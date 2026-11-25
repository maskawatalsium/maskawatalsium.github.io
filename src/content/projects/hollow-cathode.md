---
title: Thermal and Discharge Characterisation of a 50 A LaB₆ Hollow Cathode
description: Designing, building and instrumenting a high-current hollow cathode to measure how its emitter temperature and discharge change with current and xenon flow.
category: research
importance: 2
period: Jan 2024 – Jun 2025
affiliation: BSc thesis · North China Electric Power University · experiments at Beijing Institute of Technology
role: Designed and fabricated the cathode, ran the experiments and built the model (supervisor Dr. Zhang Hui)
methods: [Type-C (W-Re) thermocouples in the emitter, voltage–current and power sweeps, 0-D plasma-thermal model]
tools: [SolidWorks, AutoCAD, MATLAB, CNC and EDM machining]
status: Undergraduate thesis, June 2025
figures:
  - src: /assets/video/hc-discharge.mp4
    type: video
    poster: /assets/img/research/hc-discharge-poster.jpg
    caption: The cathode running in xenon inside the vacuum chamber.
  - src: /assets/img/research/hc-mode-map.jpg
    caption: Discharge appearance across 20–50 A and 5–20 sccm. The plume-to-spot transition happens at about 30–35 A.
  - src: /assets/img/research/hc-20A.jpg
    caption: 20 A, 10 sccm — diffuse plume mode.
  - src: /assets/img/research/hc-40A.jpg
    caption: 40 A, 10 sccm — bright, concentrated spot mode.
  - src: /assets/img/research/hc-cad.jpg
    caption: SolidWorks model of the cathode assembly.
  - src: /assets/img/research/hc-cad-section.png
    caption: Section view showing the LaB₆ emitter inside the graphite tube and keeper.
  - src: /assets/img/research/hc-thermocouples.jpg
    caption: Type-C thermocouples routed through ports in the keeper to the emitter, orifice plate and tube.
  - src: /assets/img/research/hc-stand.jpg
    caption: The cathode on its mounting stand before installation.
---

Every Hall and ion thruster needs a hollow cathode, and its emitter temperature decides both
electron emission and lifetime. I designed a 50 A-class, heater-less cathode with a LaB₆ emitter
(Ø 6.3 × 25.4 mm) in a graphite tube and keeper, machined the parts by CNC and EDM, and fed Type-C
thermocouples through the keeper so the emitter could be measured while running.

Over 10–50 A and 5–20 sccm xenon the emitter ran at about **920–1,470 K** with a gradient of roughly
**400 K**. The discharge showed negative-resistance behaviour — voltage fell as current rose — and
switched from plume to spot mode at about **30–35 A**. A 0-D MATLAB plasma-thermal model followed the
measured trends but over-predicted temperature by about **18 % at 50 A**, pointing to radiative and
conductive losses that a 0-D model leaves out.
