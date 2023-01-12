---
title: "A comparative study of earthquake source models in high-order accurate tsunami simulations (Fortran)"
redirect_from: 
  - /tsunami.html
---

I was at **EPFL** university for six months in **Prof. Hesthaven** laboratory. 
My duty was to add different **seabed deformation methods** to a big code with about 40000 lines in **Fortran**. 
Their code hadn’t any user guide and thus that was difficult to add my codes to this big code. 
Before adding my codes to that big code, my ideas are tested in simple cases. 
Actually, I wrote a **DG** solver to solve **shallow water equations** and to check the effects of different seabed deformation methods. 
After developing basic ideas, it is implemented to that big code. 
An **Okada** method is used for calculating the **seabed deformation** due to an **earthquake** with both the static and dynamic approaches.

For more details, please refer to the following paper:
[A comparative study of earthquake source models in high-order accurate tsunami simulations](https://doi.org/10.1016/j.ocemod.2019.101429)


## Results
![basic_idea_Non_linear_breaking](/files/tsunami/Picture0.png)
![displacement](/files/tsunami/Picture5.png)
![grid](/files/tsunami/Picture1.png)
![water_waves](/files/tsunami/Picture2.png)
![comparison](/files/tsunami/Picture3.png)
[![movie](/files/tsunami/Picture4.png)](https://www.youtube.com/watch?v=yV7exuqRzGk)
