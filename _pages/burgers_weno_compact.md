---
title: "Hybrid WENO-Compact method for solving Burgers' turbulence problem (fortran)"
redirect_from: 
  - /burgers_weno_compact.html
---

In this project, a high-order hybrid **Weighted Essentially Non-Oscillatory (WENO)**-**Compact** method is used to accurately discretize derivative terms in **Burgers' equation**.
Here, **convection terms** are discretized using fifth-order WENO to sharply capture likely discontinuoities in the solution domain and **diffusion term** is also discretized by employing sixth-order Compact finite difference method. This solver is writen in **Fortran**.
Applying this high order method leads to a **Direct Numerical Solution (DNS)** meaning we can study turbulent flow features without needing turbulence models. Here, energy spectrums are studied.
For more details, please refere to this [document](/files/burger_weno_compact/burger_weno_compact.pdf).


## Results
![Validation](/files/burger_weno_compact/1.png)
![energy_spectrum_time](/files/burger_weno_compact/2.png)
![velocity_time](/files/burger_weno_compact/3.png)
![energy_spectrum](/files/burger_weno_compact/4.png)


