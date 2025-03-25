---
title: "A new stability analysis of the central difference method for transient dynamics viscoelastic problems" 
Category: Research papers
date: 2024-07-22
lastmod: 2024-07-22
tags: ["Central difference method","Stability analysis","Variable time step","Viscoelasticity","Transient dynamics"]
author: ["Benjamin Georgette","David Dureisseix", "Anthony Gravouil"]
description: "This paper, submitted to the Journal of Scientific Computing" 
summary: "This submitted paper presents a general framework for studying the stability properties of the central difference scheme for transient dynamics viscoelastic problems using both constant and variable time step " 
cover:
    # image: "fig_VariableTimeStep_ElasticAnalysisRho.png"
    alt: "Stability analysis central difference scheme"
    relative: false
password: ""
---

---

 Download the [preprint paper](./GEORGETTE_DUREISSEIX_GRAVOUIL_manuscript.pdf).

##### Abstract

In this paper, we propose a general framework for studying the stability properties of the central difference scheme for transient dynamics viscoelastic problems using both constant and variable time step. First, we introduce a new explicit constant time step integration method for viscoelastic materials. This new method surpasses the stability limits of Belytschko’s half-lagged velocity approximation. Second, we provide a new stability analysis of the variable time step central difference method. The proposed analysis shows that central difference’s stability can be ensured only thanks to the zero-stability criteria, based on the multistep formulation of the method. Without viscous damping, ensuring stability requires to decrease, or at least to maintain constant time step during the time integration. However, with viscous damping, there is a slight possibility of increasing the time step during the time integration process.

##### Citation

Georgette, B., Dureisseix, D., & Gravouil, A. A new stability analysis of variable time step central difference method for transient dynamics viscoelastic problems.

```BibTeX
@inproceedings{georgette2024,
  title={A new stability analysis of variable time step central difference method for transient dynamics viscoelastic problems},
  author={Georgette, Benjamin and Dureisseix, David and Gravouil, Anthony}
}
```
--- 
##### Link to related communication at ENOC24 
[ENOC24 communication]({{< relref "communications/2024-ENOC/index.md" >}})

---