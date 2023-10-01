---
layout: archive
title: "Research"
permalink: /research/
classes: wide
---
 
***Dynamical systems*** are encountered within nature through various conformal representations ranging from physical phenomena such as turbulence to bacteria population dynamics to financial investment dynamics to the movement of extraterrestrial planets, etc. The common denominator in all these mutually exclusive examples is the *dependence on time (either discrete or continuous)* and the evolution of their respective degrees of freedom (DOFs) with time. However, the underlying governing equations that dictate this evolution aren’t always readily accessible or are computationally expensive endeavours. This necessitates the exploration of autonomous data-driven algorithms. There have been significant strides in the development of classical computing hardware and, in recent years, quantum computing hardware, which further accelerates the development of these algorithms. This is where the core of my research lies!
{: style="text-align: justify;"}


## 1. Deep learning and Chaotic dynamical systems
Chaotic systems exhibit extreme sensitivity to the initial conditions, which makes it a challenging problem coupled with the range of spatio-temporal characteristics exhibited by the system. These complexities in the dynamics of forecasting/prediction of complex systems are often encountered in various scientific disciplines and are also in their nascent stages for the exploration of machine learning as the gateway. The universality of the deep-learning framework being able to approximate a continuous function (within a specified range) in such cases, i.e. time series problems, raises the idea of being able to formulate an autonomous dynamical system. Hence, so far I have explored the following:  
{: style="text-align: justify;"}

### (Ongoing Research Project) Quantum gated recurrent neural networks  

I am currently investigating Quantum machine learning algorithms and their ability to tackle chaotic dynamical systems in a *teacher forced setting*. The work introduces Quantum LSTMs and Quantum GRUs, architecturally similar to [[paper]](https://ieeexplore.ieee.org/abstract/document/9747369?casa_token=3-qGIJwNnaMAAAAA:VKKWd-mdhtQHMfth-cligXcg46drtoLNCighGfWmJYGxQMjsx0ZPrBSGIbolkMEyeruKmyU). So far we benchmarked these model on a simple yet tricky toy problem, i.e. sine trigonometric function, which was used as a benchmark to generalize the comparison from an interpretability standpoint. The better *expressiveness* of the quantum versions of LSTMs & GRUs was observed with faster convergence, robustness to the varying level of gaussian noise within data and way less parameter count compared to classical versions to achieve same MSE loss with the constraint on epochs.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/images/QuantumVc.png" width="42%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/images/l63_expdivLR.gif" width="38%" />
</p></center>

### Classical gated recurrent neural networks - An autonomous dynamical system

We are currently designing an active flow control counterpart of the above-mentioned passive flow control strategy for further augmenting the airfoil lift.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/images/ClassicalGRNN.png" width="40%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/images/l96_web.gif" width="55%" />
</p></center>

## 2. Deep learning and Reduced order models (ROMs)

More details about this work can be found [[here]](https://arxiv.org/pdf/1912.10553).
{: style="text-align: justify;"}

### State estimation using deep learning - Leveraging reduced order models (ROMs)  
More details about this work can be found [[here]](https://arxiv.org/pdf/1912.10553).
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/images/JCP.gif" width="60%" />
</p></center>

### Deep learning based effecient data-driven reduced-order model (ROMs) for temporal evolution
Recently, deep convolutional autoencoders have been used to construct nonlinear manifolds for model order reduction. 
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/images/SST_web.gif" width="60%" />
</p></center>


## 3. Unmanned Aerial Vehicles
Fabricated state-of-the-art, all-composite, Vertical Take Off and Landing Unmanned aerial vehicle (VTOL-UAV) with automatic tilt rotor mechanism using Vacuum Bagging process for HADR missions (Mehar Baba Prize competition). Improved the aerodynamic efficiency (Lift/Drag Ratio) of VTOL-UAV by introducing C-curve wing-lets by 10%, thereby enhancing the crashworthiness of the system. Developed the 3D CAD model of the UAV and tilt rotor mechanism on *Solidworks*. Carried out 3D CFD Simulations using *K-omega turbulence model* to evaluate the Coefficient of lift and drag of the VTOL-UAV. Numerical experiments were performed on *ANSYS Fluent* and *OpenFOAM*.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/images/UAV.png" width="80%" />
</p></center>

<br/>

## Selected Course Projects

### 1. Computational Fluid Dynamics
  * List item one 
      * List item one 
{: style="text-align: justify;"}


### 2. Computational Linear Algebra and Machine Learning
  * List item one 
      * List item one 
{: style="text-align: justify;"}





