---
layout: splash
title: "Research"
permalink: /research/
classes: wide
---

# Research
Computational Fluid Dynamics (CFD) has become an indispensable tool for many engineering applications. Unfortunately, high-fidelity CFD simulations are often so computationally prohibitive that they cannot be used as often as needed or used only in special circumstances rather than routinely. Model order reduction (MOR) is a family of techniques for reducing the computational complexity of such large-scale computational models. This is where the core of my research lies!
{: style="text-align: justify;"}

**Keywords**: Computational fluid dynamics (CFD); Deep learning / Machine learning; Reduced-order modeling (ROMs)  

## 1. Deep learning and Chaotic dynamical systems
Pranav control is a process of manipulating the flow to achieve desirable aerodynamic performance.
{: style="text-align: justify;"}

### (Ongoing Research Project) Quantum gated recurrent neural networks  

We numerically investigated a model system in which a passively deployable, torsionally hinged flap is mounted on the suction surface of a stationary airfoil via high-fidelity nonlinear simulations as shown in the figure below.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/assets/images/passivefc.png" width="30%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/assets/images/maps.png" width="60%" />
</p></center>

### Classical gated recurrent neural networks - An autonomous dynamical system

We are currently designing an active flow control counterpart of the above-mentioned passive flow control strategy for further augmenting the airfoil lift.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/assets/images/rl.png" width="60%" /> &nbsp; &nbsp; &nbsp; &nbsp;
</p></center>

## 2. Deep learning and Reduced order models (ROMs)

More details about this work can be found [[here]](https://arxiv.org/pdf/1912.10553).
{: style="text-align: justify;"}

## State estimation using deep learning - Leveraging Reduced order models (ROMs)  
More details about this work can be found [[here]](https://arxiv.org/pdf/1912.10553).
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/assets/images/se.png" width="60%" />
</p></center>

## Deep learning based effecient data-driven reduced-order model (ROM) for temporal evolution
Recently, deep convolutional autoencoders have been used to construct nonlinear manifolds for model order reduction. 
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/assets/images/hadap.png" width="40%" />
</p></center>


## 3. Unmanned Aerial Vehicles
Traditional ROM approaches cannot be expected to efficiently provide good approximations.
{: style="text-align: justify;"}

<center><p float="center">
  <img src="/assets/images/step.png" width="50%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/assets/images/combustion.png" width="33%" />
</p></center>

<br/>

# Selected Course Projects

## 1. Pattern recognition in fluid dynamics using deep convolutional autoencoders
We developed a nonlinear modal decomposition framework for accurately representing transient fluid flows where traditional techniques perform poorly. In this approach, the flow patterns identified by the manifold were analyzed by evaluating the principle directions of the low-dimensional latent space. The nonlinear manifold was constructed using a deep convolutional autoencoder. The proposed framework was demonstrated to reconstruct and identify dominant and meaningful flow patterns in a transient flow ensuing from an impulsive motion of a flat plate at a large angle of attack.
{: style="text-align: justify;"}
<center><p float="center">
  <img src="/assets/images/cae.png" width="60%" />
</p></center>

## 2. Aeroacoustics of vortex shedding about a stalled airfoil
The Ffowcs Williams-Hawkings (FWH) equation for predicting acoustic pressure was numerically solved using the Farassat Formulation 1A. This formulation has been historically used for predicting helicoptor rotor and propeller noise. First, the code was validated against analytical solutions consisting of stationary and moving monopoles. The validated code was then used to predict vortex shedding noise about a stalled airfoil.
{: style="text-align: justify;"}
<center><p float="center">
  <img src="/assets/images/caevs.png" width="30%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/assets/images/directivity.png" width="30%" />
</p></center>

## 3. Shock induced flow separation control using vortex generators
Shock induced flow separation during transonic flow conditions decreases the aerodynamic performance of the wing. In this work, passive flow control of transonic flow past an Onera M6 wing using vortex generators was studied. The CFD simulations were performed on Ansys Fluent. Velocity contours at various spanwise locations revealed the delay of shock occurrence downstream and reduced flow separation. The resulting improvements in the lift to drag ratio, implied that the vortex generators improved the aerodynamic performance of the wing.
{: style="text-align: justify;"}
<center><p float="center">
  <img src="/assets/images/mesh.png" width="30%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/assets/images/cpfluent.png" width="30%" /> &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="/assets/images/ansys.png" width="70%" />
</p></center>



