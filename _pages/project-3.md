---
layout: single
title: "Fine-tuning LLaVA for Scientific and Chart-Based Visual Question Answering"
permalink: /projects/project-3/
classes: wide
---

## Introduction

{: style="text-align: justify;"}
In ASML's lithography machines, the In-Vacuum Robot (IVR) plays a critical role in transferring reticles between radially aligned stations. During operations, deviations from predefined logical positions can occur due to driver failures, power outages, or mechanical malfunctions. Recovery from such lost positions is typically manual, resulting in significant downtime and risks of collision. This project aimed to develop an automated recovery algorithm to reduce recovery time, enhance operational efficiency, and mitigate human error.

---

## Method

{: style="text-align: justify;"}
The IVR, modeled as a 4-link, 3-DoF system operating in cylindrical coordinates, required a systematic recovery solution for two classifications of lost positions: unentangled and entangled scenarios. The approach involved:  

**1. Algorithm Development:**  
- For unentangled recovery, moves were executed sequentially in 𝑅, 𝜙, and 𝑍 directions based on proximity to the nearest station.
- For entangled recovery, station-specific algorithms ensured collision-free moves considering reticle presence on the gripper and stations.

**2. GUI tool:** A MATLAB-based interactive GUI was developed to input lost positions, select reticle status, and visualize recovery trajectories.  

**3. Trajectory Simulation:** A Simulink model simulated the IVR's environment, including links, joints, and reticle presence using Variant Subsystems. Waypoints were generated, and inverse kinematics ensured smooth motion.

**4. Testing:** The recovery algorithm was rigorously tested through 3D simulations and compared against expected outcomes for accuracy.

![ASML project workflow](/images/asml-internship-photo.png)

### Results  

{: style="text-align: justify;"}
The automated recovery algorithm successfully reduced manual intervention, enabling the IVR to return to logical positions safely and efficiently. The MATLAB GUI and 3D simulations provided intuitive visualization and validated the algorithm's performance. Key outcomes included:

- Accurate identification of recovery trajectories.
- Smooth transitions between lost positions and logical waypoints.
- Reduced recovery times compared to manual processes.

---

### Conclusion

{: style="text-align: justify;"}
The project delivered an effective and automated solution for IVR recovery, minimizing downtime and enhancing operational reliability. Future steps include a design review, software team implementation, and real-world validation on test rigs before deployment to customers.

![LLaVA Architecture](/images/llava_pipeline.png)  
*Figure 2: The LLaVA architecture.*
