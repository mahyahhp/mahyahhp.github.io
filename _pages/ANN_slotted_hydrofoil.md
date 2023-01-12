---
title: "A deep artificial neural network-assisted genetic-algorithm method to optimize a slotted hydrofoil (Python, Matlab, C++)"
redirect_from: 
  - /ANN_slotted_hydrofoil.html
---
This project is the continuation of the [Study on the optimization of a slotted hydrofoil using Genetic algorithm](/files/Study on the optimization of a slotted hydrofoil using Genetic algorithm.pdf) project.
In that [project](/files/Study on the optimization of a slotted hydrofoil using Genetic algorithm.pdf), the **Gaussian Process Regression** method (called **Kriging**) as a **surrogate model** is used alongside a **genetic algorithm** method to **optimize** a slotted hydrofoil. 
Here, a [deep Artificial Neural Network (ANN)](/files/A deep artificial neural network-assisted genetic-algorithm method to optimize a slotted hydrofoil.pdf) is used to be served as a surrogate model in the process of the optimization. For this aim, a **deep ANN** is developed to accurately emulate a **physical solver** based on the **finite volume** discretization of the governing equations. 
The physical solver is written in **C++** and the **deep machine learning** and the connection between the CFD solver and the optimizer are established in **Matlab** and **python**. Both the versions of Matlab and python are available upon request.
It is recommended to read this [document](/files/Study on the optimization of a slotted hydrofoil using Genetic algorithm.pdf) before going to the details of this [project](/files/A deep artificial neural network-assisted genetic-algorithm method to optimize a slotted hydrofoil.pdf).

## Results
![ANN_architecture](/files/ANN_slotted_hydrofoil/Presentation2.jpg)
![ANN_validation](/files/ANN_slotted_hydrofoil/ANN_validation.png)
![ANN_results](/files/ANN_slotted_hydrofoil/ANN_slotted_Pareto.png)
