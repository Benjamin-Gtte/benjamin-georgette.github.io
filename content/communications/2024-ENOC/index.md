---
title: "A new stability analysis of the central difference method for transient dynamics viscoelastic problems" 
category: Communications
date: 2024-07-22
lastmod: 2024-07-22
tags: ["Central difference method","Stability analysis","Variable time step","Viscoelasticity","Transient dynamics"]
author: ["Benjamin Georgette","David Dureisseix", "Anthony Gravouil"]
description: "This paper is a presentation made for the ENOC2024 scientific conference." 
summary: "This communication presents a new stability analysis of the variable time step central difference method for transient dynamics viscoelastic problems." 
editPost:
    URL: "https://enoc24.dryfta.com/"
    Text: "ENOC2024"

---
Download the [submitted abstract](./enoc2024_GEORGETTE_DUREISSEIX_GRAVOUIL.pdf), or the [presentation slides](enoc2024_GEORGETTE_DUREISSEIX_GRAVOUIL_presentation.pdf).


##### Abstract

We develop a new explicit integration method for transient dynamics computation of viscoelastic materials, surpassing
the stability limits of Belytschko’s widely used half-lagged velocity approximation. Based on the central difference (CD) scheme, our
method integrates the viscous stress strain law, while keeping an explicit scheme. Moreover, we provide a new stability analysis of
the variable time step central difference method. We prove that CD’s stability can be ensured only thanks to the zero-stability criteria,
based on the multistep formulation of the method. We perform analytical developments on a single degree of freedom problem. Thus,
we show that, without viscous damping, ensuring stability requires to decrease, or at least to maintain constant the time step during the
time integration. Furthermore, we prove that, with viscous damping, there exists a slight possibility of increasing the time step during
the time integration.

---

##### Main results
***Constant time step***
- New integration method for the viscous stress-strain relationship with great stability properties.

$$(1-\alpha)\mathbf{\sigma}^{\text{v}}{n} + \alpha^{\text{v}}_{n+1} = \eta\mathbb{I}:\mathbf{\varepsilon}(\mathbf{v}_{n+1/2}),\qquad\alpha\in\mathbb{R}^+$$

***Variable time step***

- Apparition of instability areas below the critical time step
- Impossibility to augment the time step within the simulation for a non dissipative system.
- Only the strong stability analysis based on the formulation of the scheme as a multistep scheme is relevant.

*Stability conditions for the stiff problem*

$$
\begin{aligned} 
    &\Delta t_{n+2}\leq\Delta t_{n+1}\\
    &\Delta t_{n+2}\Delta t_{n+1}\leq(\Delta t_{\text{cr}}^{\text{e}})^2\\
    &(\Delta t_{n+2}+\Delta t_{n+1})^2(1 - \tfrac{1}{2}\Delta t_{n+2}\Delta t_{n+1}\frac{k}{m})^2 - 4\Delta t_{n+1}\Delta t_n<0
\end{aligned}
$$

---

##### Citation

Georgette, B., Dureisseix, D., & Gravouil, A. (2024, July). A new stability analysis of variable time step central difference method for transient dynamics viscoelastic problems. In 11th European Nonlinear Dynamics Conference (ENOC 2024).

```BibTeX
@inproceedings{georgette2024new,
  title={A new stability analysis of variable time step central difference method for transient dynamics viscoelastic problems},
  author={Georgette, Benjamin and Dureisseix, David and Gravouil, Anthony},
  booktitle={11th European Nonlinear Dynamics Conference (ENOC 2024)},
  year={2024}
}
```

--- 

[Research paper's page !]({{< relref "papers/JSC/index.md" >}})

--- 
