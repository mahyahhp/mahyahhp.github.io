---
title: "Classical finite difference methods to solve elliptic, parabolic, hyperbolic, Euler or Navier-Stokes equations"
redirect_from: 
  - /FD_Classical.html
---
I have written different **classical finite difference methods** based codes in **Fortran** and **C++** to solve different classes of equations. Those are

* **Elliptic** equation (**Jacobi**, **PGS**, **LGS**, **PSOR**, and **LSOR**)
* **Parabolic** equation (**FTCS**, **ADI**, **Crank-Nicolson** (**Gauss-Jordan**, **Fractional step methods**))
* **Hyperbolic** equation (**Beam and Warming** with **artificial dissipation term** and **Flux corrected transport method**)
* **Euler**/**Navier-Stokes** equations (**central differencing** with a **Jameson artificial viscosity method** to control **artificial oscillations** and to capture **shocks**)

## Elliptic
![elliptic](/files/FD_classic/1_elliptic_Laplace.png)


## Parabolic
![Parabolic](/files/FD_classic/2_parabolic_Heat.png)



## Hyperbolic
![Hyperbolic](/files/FD_classic/3_Hyperbolic_wave.png)



## Euler
![Euler](/files/FD_classic/4_Euler.png)



## Incompressible Navier-Stokes
![NS](/files/FD_classic/5_NS.png)

