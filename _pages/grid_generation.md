---
title: "Structured and unstructured grid generation techniques (Fortran)"
redirect_from: 
  - /grid_generation.html
---

## structured grid
Different **algebraic** grid generation methods are written in **Fortran** as follow:
* Lagrange
![lagrange](/files/grid_generation/Picture1.png)
* Hermit
![lagrange](/files/grid_generation/Picture2.png)
* Tow-Sided Hyperbolic Tangent (Vinkour Streaching Function)
![lagrange](/files/grid_generation/Picture3.png)
* Transfinite (TFI)
![lagrange](/files/grid_generation/Picture4.png)


Moreover, **Poisson equation** is solved using **finite difference** methods to generate smooth grids with **orthogonality** on the surface of arbitrary 4-digit airfoils. This method is called the elliptic grid generation and its code is written in **Fortran**.
* Elliptic grid generation

![elliptic_thin](/files/grid_generation/Picture6.png)
![elliptic_thick](/files/grid_generation/Picture5.png)

## Unstructed grid generation
* Advancing front using point and line sources

Advancing front grid generation can be used to generate **unstructured triangular meshes** with the ability to control the mesh length locally. 
The control can be done using background mesh with **point and line sources** with their associate strength to refine mesh around them locally.
The role of the background mesh is to locally control the length of triangles. The **background mesh** is obtained by solving **Poisson equation** using finite difference method.
The code is written in **Fortran**.
![advancing_front_zoon_out](/files/grid_generation/Picture7.png)
![advancing_front_zoon_in](/files/grid_generation/Picture8.png)




