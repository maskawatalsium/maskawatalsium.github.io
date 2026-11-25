---
title: Koopman-EDMD Modelling and MPC for Quadrotor Tracking
description: Learning a lifted linear model of a quadrotor from data, then using it inside model predictive control to track a 3-D trajectory.
importance: 2
period: Jan 2026
affiliation: Aircraft Guidance and Control Theory · Beijing Institute of Technology
role: Individual project — reproduced and analysed a published learning-and-control workflow
methods: [Koopman operator, EDMD with control, rotation-matrix attitude, linear MPC as a quadratic program]
tools: [MATLAB, quadprog]
figures:
  - src: /assets/img/projects/koopman-3d.png
    caption: 3-D tracking of a smooth reference trajectory with lifted-space MPC.
  - src: /assets/img/projects/koopman-edmd.png
    caption: EDMD training trajectories and short-horizon prediction against the nonlinear simulator.
  - src: /assets/img/projects/koopman-states.png
    caption: Closed-loop states — reference (solid) versus MPC response (dashed).
  - src: /assets/img/projects/koopman-inputs.png
    caption: Thrust and body-moment commands solved at each step.
---

- Generated training data from a nonlinear rigid-body quadrotor simulator and identified a lifted
  linear predictor with EDMD, using rotation matrices for attitude to avoid Euler-angle singularities.
- Formulated tracking as a quadratic program over a 15-step horizon (2 ms step, 1.5 s run) with
  input bounds, solved every step.
- The predictor matched the simulator over short horizons, and the MPC tracked the reference with
  smooth, bounded thrust and moment commands.
