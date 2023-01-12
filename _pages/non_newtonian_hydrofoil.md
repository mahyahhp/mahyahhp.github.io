---
title: "Injection of non-Newtonian fluids to improve the hydrofoil performance"
redirect_from: 
  - /non_newtonian_hydrofoil.html
---

In this project, a new approach has been introduced to improve the efficiency of a hydrofoil by increasing its lift and reducing its drag. 
Here, **non-Newtonian fluids** including the **Power-law**, **Carreau**, **Cross**, **Ellis**, and **Prandtl-Eyring** are employed to control the boundary layer by adding additional momentum to the sublayers to postpone the separation. 
Increasing the **stall angle** and consequently changing the behaviour of the hydrofoil in the **deep stall** is the main features of this **active flow control method**.
[Ansys Fluent](https://www.ansys.com/en-gb/products/fluids/ansys-fluent) is used to study different kinds of non-Newtonian fluids wherein the hybrid quadrilateral-triangular grid is generated using [ICEM](https://en.wikibooks.org/wiki/ICEM_CFD). The **Volume of Fluid (VOF)** is used to capture the interface of two fluids.
New non-Newtonian fluids that are not available in [Ansys Fluent](https://www.ansys.com/en-gb/products/fluids/ansys-fluent) is also formulated and entered to the software through [User-Defined Function (UDF)](https://www.afs.enea.it/project/neptunius/docs/fluent/html/udf/node4.htm#:~:text=Function%20(UDF)%3F-,1.1%20What%20is%20a%20User%2DDefined%20Function%20(UDF)%3F,standard%20features%20of%20the%20code.) written in **C**. 
After identifying the best non-Newtonian fluid, numerical simulations have been performed. 
The effects of injecting non-Newtonian fluids are also compared against injected **water**. 
Indications are that this idea introduced works well and is an alternative for active flow control methods. 
Results obtained are also analysed using postprocessing tools in [Ansys Fluent](https://www.ansys.com/en-gb/products/fluids/ansys-fluent) and [Tecplot](https://www.tecplot.com/) as well. Details of the conducted project is given in this [document](/files/Injection of non-Newtonian fluids to improve the hydrofoil performace.pdf). 


## Numerical resuls
![different_non_newtonian_fluids](/files/non_newtonian_hydrofoil/Picture1.png)
![grid](/files/non_newtonian_hydrofoil/Picture2.png)
![pressure_contour_streamlines_c_mue=6.5_AOA=26](/files/non_newtonian_hydrofoil/Picture3.png)
![volume_fraction_contour_c_mue=6.5_AOA=26](/files/non_newtonian_hydrofoil/Picture4.png)
![effect_of_injection_lift_coef](/files/non_newtonian_hydrofoil/Picture5.png)
![effect_of_injection_drag_coef](/files/non_newtonian_hydrofoil/Picture6.png)
