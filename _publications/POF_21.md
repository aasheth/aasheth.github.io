---
title: "Deep learning for reduced order modelling and efficient temporal evolution of fluid simulations"
collection: publications
permalink: /publication/POF_Y2021
excerpt: ''
date: 2021-10-01
venue: 'Physics of Fluids'
paperurl: 'https://doi.org/10.1063/5.0062546' 
citation: 
---

<center><p float="center">
  <img src="/images/LabelCylinder_f.gif" width="80%" />
</p></center>

**Abstract** : Reduced order modeling (ROM) has been widely used to create lower order, computationally inexpensive representations of higher-order dynamical systems. Using these representations, ROMs can efficiently model flow fields while using significantly lesser parameters. Conventional ROMs accomplish this by linearly projecting higher-order manifolds to lower-dimensional space using dimensionality reduction techniques such as proper orthogonal decomposition (POD). In this work, we develop a novel deep learning framework DL-ROM (deep learning—reduced order modeling) to create a neural network capable of non-linear projections to reduced order states. We then use the learned reduced state to efficiently predict future time steps of the simulation using 3D Autoencoder and 3D U-Net-based architectures. Our model DL-ROM can create highly accurate reconstructions from the learned ROM and is thus able to efficiently predict future time steps by temporally traversing in the learned reduced state. All of this is achieved without ground truth supervision or needing to iteratively solve the expensive Navier–Stokes (NS) equations thereby resulting in massive computational savings. To test the effectiveness and performance of our approach, we evaluate our implementation on five different computational fluid dynamics (CFD) datasets using reconstruction performance and computational runtime metrics. DL-ROM can reduce the computational run times of iterative solvers by nearly two orders of magnitude while maintaining an acceptable error threshold.
{: style="text-align: justify;"}

**Citation** : 'Pant, Pranshu, Ruchit Doshi, Pranav Bahl, and Amir Barati Farimani. "Deep learning for reduced order modelling and efficient temporal evolution of fluid simulations." Physics of Fluids 33, no. 10 (2021).'
{: style="text-align: justify;"}
