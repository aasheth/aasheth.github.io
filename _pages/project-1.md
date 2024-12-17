---
layout: single
title: "Open-Source GeoFNO Implementation for Irregular Geometries in PDE Solvers"
permalink: /projects/project-1/
classes: wide
---

## Introduction

{: style="text-align: justify;"}
Multi-Agent Path Finding (MAPF) is crucial for applications like warehouse automation, traffic management, and gaming. Efficient solutions require collision-free paths for agents while optimizing costs. Enhanced ECBS (EECBS) incorporates online learning to improve heuristic accuracy, yet its handcrafted heuristic struggles with precision. This project proposes a machine learning framework for estimating the cost-to-go heuristic, improving runtime and search efficiency.

---

## Method

{: style="text-align: justify;"}
A Support Vector Regression (SVR) model was developed to predict the cost-to-go heuristic for EECBS. Data from Conflict Tree (CT) expansions was collected, including node-level features such as conflicts, costs, and agent count. The SVR model replaced the handcrafted formula, enhancing heuristic accuracy. Experiments evaluated the model on various maps and agent counts, assessing runtime, node expansions, and solution quality.

### Visualization of Geo-FNO Architecture:

![Geo-FNO Architecture](/images/geofno.png)  
*Figure 1: Geometry-aware FNO. The architecture deforms input functions from irregular physical space to a uniform latent space, applies FNO, and transforms back. \(P\) and \(Q\) are projection operators, while \(\mathcal{F}\) and \(\mathcal{F}^{-1}\) are Fourier transforms. \(K\) is a linear transform.*

---

## Results

{: style="text-align: justify;"}
The ML-enhanced EECBS (ML-EECBS) outperformed traditional EECBS on fixed maps, reducing runtime by 9.6% and node expansions by 7.4%. The SVR model generalized effectively to unseen agent configurations while maintaining accuracy. However, generalization to entirely new maps showed marginal performance improvements due to query time overheads.

![Results](/images/ml-eecbs-merged.png)  
*_Figure 1: Performance of the SVR trained on dataset (i) (Top) and dataset (ii) (Bottom). As we can see, the one trained on dataset (ii) provides much more accurate predictions of ˆh_

---

## Conclusion

{: style="text-align: justify;"}
ML-EECBS demonstrates improved heuristic accuracy and runtime efficiency for MAPF problems, particularly within known environments. Future work will focus on refining feature selection and incorporating map-specific features to enhance generalization across diverse environments.

---
