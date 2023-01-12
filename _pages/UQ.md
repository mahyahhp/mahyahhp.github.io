---
title: "Efficient uncertainty quantification methods for flood modelling with multiple uncertain inputs (C++, Matlab)"
redirect_from: 
  - /UQ.html
---

In reality, the inputs of a flood model might be uncertain. These multiple probabilistic uncertain inputs propagate from a model (it is **LISFLOOD** here) into outputs and make them probabilistic as well. 

Different **uncertainty quantification** methods are available to study this propagation and the classical one is the **standard Monte-Carlo (SMC)** method.
Unfortunately, the standard Monte-Carlo is too **costly** as we will need a **large sample size** to perform the quantification. 
In this project, alternative uncertainty quantification methods are employed and compared for flood modelling aplication.
These alternatives to the standard Monte-Carlo methods are: **Latin Hypercube Sampling (LHS)**, **Adaptive Stratified Sampling (ASS)**, **Quasi Monte-Carlo (QMC)**, **Haar-Wavelet Expansion (HWE)**

Findings (based on more than **4,800,000** simulation runs) indicate these alternative methods can be much more **accurate** and **efficient** than the standard Monte-Carlo method. 


[Presentation talk at the UK Fluids Conference 2022, within the session “Comp. & data-driven methods II” (Septemper 2022)](/files/UQ/UQ_UK_fluid_conference.pdf).

[Presentation in annual steering commitee (July 2022)](/files/UQ/UQ_advisory_meeting.pdf).

[Oral presentation in Water Group at University of Sheffield (February 2022)](/files/UQ/UQ_Oral_presentation_in_water_group_at_UoS.pdf).

A paper is already ready. The publication to be updated soon.

## Results
![UQ_framework](/files/UQ/UQ_framework.png)
![Convergence_study](/files/UQ/Convergence_study.jpg)
![flood_risk_state_map](/files/UQ/flood_risk_state_map.png)
![Probability_flood_map](/files/UQ/Probability_flood_map.png)
[![movie](/files/UQ/Average_water_depth.png)](https://www.youtube.com/watch?v=stwTmOMFoak)
[![movie](/files/UQ/EA5.png)](https://www.youtube.com/watch?v=snX5O7XTlls)
[![movie](/files/UQ/EA3.jpg)](https://www.youtube.com/watch?v=pd_x8wpb6nY)
