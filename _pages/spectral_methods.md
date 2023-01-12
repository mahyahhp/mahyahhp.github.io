---
title: "Solving incompressible or compressible Navier-Stokes equations using Chebyshev or Fourier collocation spectral methods (Fortran)"
redirect_from: 
  - /spectral_methods.html
---
In this project, a **chebyshev collocation spectral** method is applied to the **incompressible Navier-Stokes (NS)** equations based on the **artificial compressibility** to simulate incompressible fluid flows.
Temporal terms are also discretized using high-order explicit **Runge-Kutta** methods. 
For compressible fluid flows, a **fourier collocation spectral** method is used. The **quadrature points** and **basis functions** are different in these two methods. 
Some of the results are presented in following.

## Results

### Chebyshev to simulate incompressible visocus fluid flows
![geometry](/files/spectral_methods/chebyshev/Picture1.png)

![grid](/files/spectral_methods/chebyshev/Picture2.png)

![streamline](/files/spectral_methods/chebyshev/Picture3.png)

![error](/files/spectral_methods/chebyshev/Picture4.png)

![validation](/files/spectral_methods/chebyshev/Picture5.png)


### Fourier to simulate compressible inviscid fluid flows
![geometry](/files/spectral_methods/fourier/Picture1.png)

![grid](/files/spectral_methods/fourier/Picture2.png)

![validation](/files/spectral_methods/fourier/Picture3.png)

![contour](/files/spectral_methods/fourier/Picture4.png)
