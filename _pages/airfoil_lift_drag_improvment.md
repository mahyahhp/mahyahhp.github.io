---
title: "Airfoil Modification in Sub-Sonic Flows for Thrust Enhancement and Drag Reduction (Ansys Fluent)"
redirect_from: 
  - /airfoil_lift_drag_improvment.html
---

NACA0012 airfoil is widely used in aeronautical applications due to its performance. In this study, I have tried to enhance its performance by employing injections through slots located on the pressure and suction sides. The location of these slots are selected carefully and the amount of injected air is tuned well to attach the boundary layer to increase the lift especially about the stall angle and to reduce the pressure drag caused by the separation. The efficiency of this configuration that significantly increases the lift over drag ratio has been checked in **Ansys Fluent** where a grid generation has been done excellently to capture different flow features including the boundary layers as the inception source of the transition and separation. Different turbulence modellings including **k-epsilon**, **k-omega** and **Spalart-Allmaras** with different wall treatments have been checked to understand the effects of the turbulence models on the predictions, and k-omega SST has been used in the final simulations due to its proven ability in the drag prediction. 



![geometry](/files/airfoil_lift_drag_improvment/Picture1.png)

![grid](/files/airfoil_lift_drag_improvment/Picture2.png)

![streamline](/files/airfoil_lift_drag_improvment/Picture3.png)

![lift](/files/airfoil_lift_drag_improvment/Picture4.png)


