---
title: "Simulation of turbulent shallow water flows by solving 2D depth-averaged Reynolds-Averaged Navier-Stokes (RANS) equations using DG method"
redirect_from: 
  - /Turbulent_flooding.html
---

During my job at the **University of Sheffield**, I extended the **LISFLOOD-FP**, which is an **open-source** flood modelling tool, to enable it simulating **turbulent** shallow flows. 
For this aim, the [2D depth-averaged Reynolds-Averaged Navier-Stokes (RANS) equations based on the k-$$\varepsilon$$ formulation](https://ascelibrary.org/doi/10.1061/%28ASCE%29HY.1943-7900.0001639) are solved using the [second-order discontinuous
Galerkin (DG2) method](https://www.sciencedirect.com/science/article/pii/S004578251830389X) which needs many new developments within DG2 framework and LISFLOOD-FP as well. This new flood tool with excelent capabilities to accurately capture the mean and turbulent flow features have
been extensively examined through different practical flood related applications which shows promising results. 


## Results
![Many_cavities](/files/turbulent_flooding/Many_cavities.png)
[![conical_island](/files/turbulent_flooding/conical_island.png)](https://www.youtube.com/watch?v=PByxld06gU4)
[![array_of_cylinder3d_Dt_2D](/files/turbulent_flooding/array_of_cylinder3d_Dt_2D.png)](https://www.youtube.com/watch?v=JMv3jLEjzp4)
[![T_junction](/files/turbulent_flooding/T_junction.png)](https://www.youtube.com/shorts/G43xtVfk_iU)
