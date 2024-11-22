---
layout: single
title: "Open-Source GeoFNO Implementation for Irregular Geometries in PDE Solvers"
permalink: /projects/project-1/
classes: wide
---

# Open-Source GeoFNO Implementation for Irregular Geometries in PDE Solvers

Partial differential equations (PDEs) are essential for simulating physical phenomena across various fields, including engineering, environmental science, and healthcare. This project overcomes limitations in handling irregular geometries by implementing Geo-FNO, a neural operator designed for irregular domains, within the Unified PDE Solver (UPS) framework.

---

## Introduction

PDEs enable modeling of complex processes like fluid flow in engines, pollutant dispersion, and blood circulation in arteries. Traditional solvers struggle with irregular geometries, constraining their real-world application. By implementing Geo-FNO within OpenFOAM, this project aims to provide accessible, scalable simulation capabilities that enhance safety, sustainability, and healthcare outcomes.

---

## Methodology

This project integrates Geo-FNO with OpenFOAM to enable accurate simulations on irregular geometries. Key steps included:

- **Literature Review**: Identified models like Geo-FNO for irregular geometries and compared them with Poseidon, which supports regular geometries only.
- **Data Generation Pipeline**: Developed a Python-OpenFOAM-based pipeline to generate datasets with complex boundary conditions and geometries. Over 2,500 irregular pipe deformation cases were generated.
- **Geo-FNO Implementation**: Tested Geo-FNO on Navier-Stokes and Euler’s equations for airfoil and pipe flows, comparing performance against traditional interpolation methods.
- **Experimentation with OpenFOAM**: Ensured reproducibility by leveraging open-source tools for dataset generation and benchmarking.

### Geo-FNO Architecture

![Geo-FNO Architecture](images/geofno.png)  
*Figure 1: Geometry-aware FNO. The architecture deforms input functions from irregular physical space to a uniform latent space, applies FNO, and transforms back.*

---

## Results

Geo-FNO demonstrated significant performance improvements across various PDEs:

| **PDE Problem**           | **Train Loss** | **Test Loss** |
|----------------------------|----------------|---------------|
| Pipe Flow (with Holes)     | 0.06           | 0.09          |
| Pipe Flow (without Holes)  | 0.11           | 0.15          |
| Elasticity Problem         | 0.026          | 0.031         |
| Airfoil Geometry           | 0.31           | 0.13          |

These results validate Geo-FNO's capability to handle irregular geometries effectively, outperforming traditional methods.

---

## Discussion and Future Work

This project provides an open-source implementation of Geo-FNO, advancing the state of PDE solvers for real-world applications. Future directions include:

1. Integrating Geo-FNO with foundational models like Poseidon.
2. Testing scalability on larger datasets, such as AirfoilMNIST.
3. Exploring out-of-distribution performance on complex geometries.

By pushing the boundaries of neural operators, this work paves the way for more accessible and accurate PDE solutions in various fields.

---

