---
title: "A high-order Discontinuous Galerkin (DG) method to simulate incompressible/compressible single-/two-phase fluid flows with/without cavitation"
redirect_from: 
  - /DG_solver.html
---
As a part of my PhD thesis, A **Nodal Discontinuous Galerkin Method (NDGM)** was developed to solve different kinds of problems. The simulations can be done by selecting different options listed below:
* **Incompressible** or **compressible** fluid flow
* **Viscous** or **inviscid**
* **1D**, **2D** (**quadrilateral** or **triangular** grids), **3D** (**hexahedral** or **tetrahedral** grids)
* **Immiscible multiphase** or **multicomponent** fluid flows
* Cavitation modelling: **One-fluid model** (**table look-up** approach), **transport equation-based** model (**Merkle et al., Kunz et al. and Senocak and Shyy**)
* Numerical fluxes: **Lax**, **Roe**, **Rusanov**, **Harten–Lax–van Leer (HLL)**, **Harten–Lax–van Leer- Contact (HLLC)**, **Low-Diffusion-Flux-Splitting (LDFS)**, **AUSM+-up**
* Shock/discontinuity capturing methods: **generalized MUSCL limiter**, **generalized exponential filter**, **artificial viscosity method**
* Temporal discretization method: **Explicit Runge Kutta methods**, **Implicit dual-time method**
* Diffusion terms discretization approaches: **central**, **local DG (LDG)**, **internal penalty (IP)**

The NDGM solver is written from **scratch** in the **C++** programming language. It is **object-oriented** and has been **paralleled** using **OpenMP**. 
The grids were taken in from **Gambit** in **neutral** file formats. 
In the incompressible form of governing equations, the **artificial compressibility method** is used to overcome the **velocity-pressure coupling problem**. 
So, the governing equations are **preconditioned** to accelerate to convergence rate in pseudo times. Caution is needed for solving this class of equations because the eigenvalues and eigenvectors of the system of equations will change so an amendment is needed in the calculation of the numerical fluxes. 
These **eigenvalues and eigenvectors** were derived analytically using **Maple** and were used in the process of the numerical flux evaluation. 
The results are exported in a .dat or .plt format files to be read in **Tecplot** for postprocessing purposes. 
Although some of the results are not presented in my articles, main information are available in these papers:
* [A high-order nodal discontinuous Galerkin method for solution of compressible non-cavitating and cavitating flows](https://doi.org/10.1016/j.compfluid.2017.07.002)
* [An implicit dual-time stepping high-order nodal discontinuous Galerkin method for solving incompressible flows on triangle elements](https://doi.org/10.1016/j.matcom.2019.08.011)
* [A high-order nodal discontinuous Galerkin method to solve preconditioned multiphase Euler/Navier-Stokes equations for inviscid/viscous cavitating flows](https://doi.org/10.1002/fld.4792)
* [A high-order nodal discontinuous Galerkin method for simulation of three-dimensional non-cavitating/cavitating flows](https://doi.org/10.1016/j.finel.2021.103681)

A series of simulations done are shown hereunder:

## 1D/2D/3D two-phase cavitating fluid flows
![1D_Comp_cavitating](/files/DG_solver/cavitating/Comp_cavitating_1.png)
![2D_incom_cavitating_hydrofoil](/files/DG_solver/cavitating/incom_cavitating_1.png)
![3D_incom_cavitating_wavy_cylinder](/files/DG_solver/cavitating/incom_cavitating_4.png)
![3D_incom_cavitating_twisted_wing](/files/DG_solver/cavitating/incom_cavitating_3.png)
[![2D_incom_cavitating_side_by_side_cylinder](/files/DG_solver/cavitating/incom_cavitating_2.png)](https://youtu.be/8BYEIBEskcs)



## 2D/3D single-phase incompressible fluid flows
![2D_Side_by_side_cylinder](/files/DG_solver/incompressible/incom_noncavitating_2.png)
![2D_cylinder](/files/DG_solver/incompressible/incom_noncavitating_3.png)
![3D_cavity](/files/DG_solver/incompressible/incom_noncavitating_2.png)
![3D_Cylinder_in_a_channel](/files/DG_solver/incompressible/incom_noncavitating_2.png)



## 1D/2D single-phase compressible fluid flows
![1D_shock_density_interaction](/files/DG_solver/compressible/comp_noncavitating_1.png)
![2D_forward_step](/files/DG_solver/compressible/comp_noncavitating_2.png)



## Multicomponent chemically reacting flow
![2D_forward_step](/files/DG_solver/multicomponent/chemical_reacting_flow.png)
