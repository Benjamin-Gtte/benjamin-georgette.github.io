---
title: "Explicit multi-symplectic variable time step integrator for non-linear dynamics: application to viscoelastic materials"
authors: "Georgette, B., Dureisseix, D., Gravouil, A."
journal: "HAL-DUMAS"
year: 2023
selected: false
pdf: "/articles/georgette-2025a_HAL.pdf"

cite: "Georgette, B. (2023) Intégrateur temporel explicite multi-symplectique à pas de temps variable pour la dynamique non-linéaire : application aux matériaux viscoélastiques. Mécanique des structures [physics.class-ph]. Available at: https://dumas.ccsd.cnrs.fr/dumas-04936580."

bibtex: |
  @mastersthesis{georgette:dumas-04936580,
    title = {{Int{\'e}grateur temporel explicite multi-symplectique {\`a} pas de temps variable pour la dynamique non-lin{\'e}aire : application aux mat{\'e}riaux visco{\'e}lastiques}},
    author = {Georgette, Benjamin},
    url = {https://dumas.ccsd.cnrs.fr/dumas-04936580},
    pages = {73},
    school = {{LAMCOS, Insa de Lyon, 27 bis avenue Jean Capelle, 69100 Villeurbanne}},
    year = {2023},
    hal_id = {dumas-04936580},
        }

---

The aim of this master's thesis report is to develop an explicit multi-symplectic time integrator with variable time steps for non-linear dynamics, applied to viscoelastic materials. The problems considered (tension-compression beam, simple pendulum) are integrated using an explicit time integrator, whose properties of stability, consistency, energy conservation and convergence are studied. The behavior of the problems, first elastic, then stiff, then viscous, is taken into account in the development of the integrator. A new constant-time integration method for structural dynamics is proposed in the viscous case, generalizing the Belytschko approximation. The properties of the integrator are then studied in the case of a non-uniform time grid. This final study will show that, in the case of a non-dissipative problem, the time step can only decrease in a simulation, whereas the introduction of mechanical dissipation allows the time step within a simulation to increase.