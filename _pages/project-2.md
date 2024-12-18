---
layout: single
title: "Optimal control strategies for a two-link trapeze-jumping Acrobot"
permalink: /projects/project-2/
classes: wide
---

## Introduction

{: style="text-align: justify;"}
Trapeze-jumping acrobots present unique challenges in robotics due to their under-actuated and nonlinear nature. This project aimed to develop an optimal control strategy that allows an acrobot to transition seamlessly between trapeze bars. The study focused on minimizing energy consumption while maintaining trajectory precision and stability.

---

## Method

{: style="text-align: justify;"}
The acrobot was modeled as a two-link system with a revolute joint. Direct Collocation (DIRCOL) optimization was employed to discretize the continuous control trajectory into collocation points. The approach incorporated free-time optimization to improve phase transitions dynamically. Constraints were applied to manage the dynamics of the swinging and flying phases, with a quadratic cost function prioritizing efficiency and precision.

![Acrobot dynamics phases](/images/flying-acrobot-placeholder.png)  
*Figure 1: The diagram shows the different dynamics phases of acrobot - swing up, flying, and catching.*

---

## Results

{: style="text-align: justify;"}
Simulation results showed the acrobot successfully transitioning between trapeze bars. The free-time implementation proved critical in achieving smooth transitions, optimizing momentum during the swinging phase, and ensuring precise landings during the flying phase. Key performance metrics, such as input torque and state transitions, were validated, demonstrating robust control.

![Acrobot state vs time plots](/images/acrobot-results.png)  
*Figure 2: timeseries plot of state (left) and state derivative (right)*

---

## Conclusion

{: style="text-align: justify;"}
This study highlights the potential of DIRCOL in solving complex control problems for under-actuated systems. By optimizing timing and control inputs, the acrobot achieved stable and energy-efficient motion. Future work will focus on trajectory tracking and real-time adjustments using advanced control techniques like time-varying LQR.

---
