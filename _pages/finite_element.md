---
title: "Simulation of incompressible fluid flows using Galerkin weighted residual finite element method (C++)"
redirect_from: 
  - /finite_element.html
---

To solve **incompressible Navier-Stokes equation**s using **Finite Element (FE)** method, the **simple lagging** method is used to reform non-linear terms into linear ones. 
The **pressure-velocity coupling problem** has been also solved using **inequal order** method wherein velocities are approximated using second-degree polynomials, however, it would be first-degree for the pressure. This solver is written in **C++**. **Matlab** is also used to derive symbolic formulations needed in the FE discretization method.
Then, **Galerkin weighted residual** method would be used in the context of the FE method. After applying boundary conditions, the system of linear equations has been solved using **GMRES** solver. 


## Incompressible potential fluid flow
![hummingbirds_grid_zoom_out](/files/finite_element/1.png)
![hummingbirds_grid_zoom_in](/files/finite_element/2.png)
![hummingbirds_contour_streamline_zoom_out](/files/finite_element/3.png)
![hummingbirds_contour_streamline_zoom_out](/files/finite_element/4.png)
![river_grid](/files/finite_element/6.png)
![river_contour_streamline](/files/finite_element/7.png)



## Incompressible flow in a cavity
![triangular_cavity_grid](/files/finite_element/8.png)
![triangular_cavity_streamline](/files/finite_element/9.png)
![triangular_cavity_validation](/files/finite_element/10.png)

![trapezoidal_cavity_grid](/files/finite_element/11.png)
![trapezoidal_cavity_streamline](/files/finite_element/12.png)
![trapezoidal_cavity_validation](/files/finite_element/13.png)
