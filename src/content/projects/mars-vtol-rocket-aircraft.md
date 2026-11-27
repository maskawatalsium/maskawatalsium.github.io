---
title: Conceptual Design of a Hypersonic VTOL Mars Rocket Aircraft
description: '"Ares Kestrel" — a two-crew, LH₂/LO₂ rocket aircraft for runway-free, point-to-point travel on Mars.'
importance: 1
period: Jul 2026
affiliation: Modern Aircraft Configuration Design · Beijing Institute of Technology
methods: [Configuration trade study, mass budget from component point masses, rocket equation, thrust-to-weight analysis]
tools: [OpenVSP, MATLAB]
figures:
  - src: /assets/img/projects/mars-layout.png
    caption: Labelled configuration — cranked-delta wing, two-crew canopy, payload and tank bay, twin aft engines and VTOL allowance.
  - src: /assets/img/projects/mars-mission.png
    caption: Reference mission — vertical take-off, boost, high-speed flight, return and vertical landing.
  - src: /assets/img/projects/mars-top.png
    caption: OpenVSP top view.
  - src: /assets/img/projects/mars-side.png
    caption: OpenVSP side view.
  - src: /assets/img/projects/mars-mass.png
    caption: Mass budget reconciled to the OpenVSP MassProp total.
  - src: /assets/img/projects/mars-propulsion.png
    caption: Conceptual LH₂/LO₂ propulsion architecture.
  - src: /assets/img/projects/mars-deltav.png
    caption: Ideal Δv versus propellant fraction and specific impulse.
  - src: /assets/img/projects/mars-tw.png
    caption: Mars thrust-to-weight ratio at gross, mid-burn and burnout mass.
---

- Compared a rotorcraft, a ballistic hopper, a lifting body and a winged rocket aircraft, and chose
  the winged configuration for control and terminal energy management.
- Built the mass budget directly from the OpenVSP model: **48,096 kg** gross, **35,000 kg** of
  LH₂/LO₂ and a **500 kg** payload; wing span 17.83 m, area 48.86 m².
- With an assumed 450 s specific impulse the ideal **Δv is about 5.7 km/s**; with 240 kN installed
  thrust the gross **Mars T/W is about 1.35** — enough to lift off, with thin margins.
- Set out the open risks plainly: propellant logistics, thrust margin, unvalidated hypersonic
  aerodynamics and heating, and human-rating mass.
