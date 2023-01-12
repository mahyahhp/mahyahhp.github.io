---
title: "An improvement of thermal performance of wavy microtubes with aluminum oxide nanofluid based on ethylene glycol"
redirect_from: 
  - /nanofluid_wavy_microtubes.html
---


Wavy tubes with circular cross-sections can improve heat transfer. Besides, nanofluids can be beneficial to improving thermal performance. Here, a suitable nanofluid flows inside a wavy microtube to improve the heat transfer dramatically. The base fluid is **water** and nanoparticles investigated are **Aluminum oxide Al<sub>2</sub>O<sub>3</sub>** and **ethylene glycol C<sub>2</sub>H<sub>6</sub>O<sub>2</sub>**. The performance has been studied at different Reynolds numbers Re=10, 100, and 1000 and different diameters of nanoparticles _d_=20, 50, and 80 nm. Moreover, the volume fraction of nanoparticles is considered to be <FONT FACE="Symbol">a</FONT>=0, 2, and 4. 

A structured grid has been generated using [ICEM](https://en.wikibooks.org/wiki/ICEM_CFD) to discretize the solution domain. [Ansys Fluent](https://www.ansys.com/en-gb/products/fluids/ansys-fluent) is also used to simulate this problem. 

Here, The Mach number is always lower than 0.3, so the fluid flow regime is always incompressible and the solver is pressure based. A **mixture multiphase model** is used in [Ansys Fluent](https://www.ansys.com/en-gb/products/fluids/ansys-fluent) to simulate this two-phase fluid flow problem. The drag force of the nanoparticles are taken into account and it is modelled using Schiller-Naumann. However, the lift force is neglected due to the small length scale of nanoparticles in comparison with the characteristic length of the microtube. The slip velocity is also modelled using Manninen-et-al. Moreover, the assumption of the laminar fluid flow is valid here due to the Reynolds numbers considered. So, the governing equations would be continuity, momentum, volume fraction and energy equations. The pressure-velocity coupling problem is addressed using SIMPLE. Pressure gradients are discretized using the least squared method. Pressure is updated using the PRESTO method and finally, the remaining governing equations are discretized using second-order finite volume methods. 


## Al<sub>2</sub>O<sub>3</sub>-based nanofluid in a circular cross-section tube

![grid_geometry](/files/nanofluid_wavy_microtube/Picture1.png)

![temperature_contour](/files/nanofluid_wavy_microtube/Picture2.png)

![validation](/files/nanofluid_wavy_microtube/Picture3.png)


## C<sub>2</sub>H<sub>6</sub>O<sub>2</sub>-based nanofluid in a wavy microtube

![boundary_geometry](/files/nanofluid_wavy_microtube/Picture4.png)

![grid](/files/nanofluid_wavy_microtube/Picture5.png)

![convergency](/files/nanofluid_wavy_microtube/Picture6.png)

![temperature_surface_contour](/files/nanofluid_wavy_microtube/Picture7.png)




