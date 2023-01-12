---
title: "Study on the optimization f a slotted hydrofoil using Genetic algorithm (C++ and Matlab)"
redirect_from: 
  - /optimization_slotted_hydrofoil.html
---


In this project, first **sampling** in the optimization space is done using **Latin Hypercube Sampling (LHS)** method. Then a set of simulations are done by calling a **FV-based fluid flow solver** in **Matlab** to train a **surrogate based model** which is **Gaussian regression** (**Kriging metamodel**).
Then a **genetic algotithm** is used to do a **multi objective optimization** ,and finally a design point is selected in the **Pareto front**. 
In the part of the solver, I wrote a **finite volume method** to discretize Euler or Navier-Stokes equations. It can uses different methods including **Jameson**, **MUSCL** and **Frink**. 
There are also different options for numerical fluxes: **Roe**, **AUSM family**, **Lax**, **HLL**, **HHLC**, **LDFS**
It can accurately and quickly simulate different **incompressible/compressible single-/two-phase** fluid flows with/without **cavitation**.
More details can be found [here](/files/Study on the optimization of a slotted hydrofoil using Genetic algorithm.pdf)

![validation_bump](/files/optimization_slotted_hydrofoil/Picture1.png)
![validation_cavitation](/files/optimization_slotted_hydrofoil/Picture2.png)
![hptimization_geometry](/files/optimization_slotted_hydrofoil/Picture3.png)
![hptimization_samples](/files/optimization_slotted_hydrofoil/Picture4.png)
![hptimization_some_results](/files/optimization_slotted_hydrofoil/Picture5.png)

