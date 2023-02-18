---
title: "The solution of 2D depth-averaged Reynolds-Averaged Navier-Stokes (RANS) equations using Discontinuous Galerking for simulating turbulent shallow water flows"
redirect_from: 
  - /Turbulent_flooding.html
---

During my job at the **University of Sheffield**, I extended the **LISFLOOD-FP**, which is an **open-source** flood modelling tool, to enable it simulating **turbulent** shallow flows. 
For this aim, the [2D depth-averaged Reynolds-Averaged Navier-Stokes (RANS) equations based on the k-$$\varepsilon$$ formulation](https://ascelibrary.org/doi/10.1061/%28ASCE%29HY.1943-7900.0001639) are solved using the [second-order discontinuous
Galerkin (DG2) method](https://www.sciencedirect.com/science/article/pii/S004578251830389X) which needs many new developments. This new flood tool with excelent capabilities to accurately capture the mean and turbulent flow features have
been extensively examined through different practical flood related applications which shows promising results. 


## Results
![basic_idea_Non_linear_breaking](/files/tsunami/Picture0.png)
![displacement](/files/tsunami/Picture5.png)
![grid](/files/tsunami/Picture1.png)
![water_waves](/files/tsunami/Picture2.png)
![comparison](/files/tsunami/Picture3.png)
[![movie](/files/tsunami/Picture4.png)](https://www.youtube.com/watch?v=yV7exuqRzGk)
