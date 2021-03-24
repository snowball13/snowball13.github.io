## About Me

I am a PhD student with the Mathematics of Planet Earth Centre for Doctoral Training (MPE CDT) at Imperial College London, with a background in mathematics. My research focus is on the development of computational tools for PDEs, in particular looking at the development of sparse spectral methods on spherical caps, with applications in atmosphere modelling.

## Projects

### Sparse Spectral Methods on Disk-Slices, Trapeziums and Spherical Caps

The goal of this project is to investigate sparse spectral methods on subdomains of the sphere that could serve as an alternative to the spherical harmonics approach currently in use at the European Centre for Medium-range Weather Forecasts (ECMWF) in their weather and climate model. The aim would be to preserve the predictive skill of the current approach whilst avoiding the parallel scalability bottleneck from the global spectral transform, which is expected to inhibit the future performance of the ECMWF model. To build to this, we have worked on developing such methods on disk-slices and trapeziums in 2D and spherical caps as a surface in 3D.

 - B. Snowball & S. Olver (2020). [Sparse spectral and p-finite element methods for partial differential equations on disk slices and trapeziums](https://doi.org/10.1111/sapm.12303). Studies in Applied Mathematics

 - B. Snowball & S. Olver (2020). [Sparse spectral methods for partial differential equations on spherical caps](https://arxiv.org/pdf/2012.11493.pdf). arXiv preprint arXiv:2012.11493.

### Lagrangian Particle Methods for Incompressible Flows

Visram et al. (2014) compared the semi-geostrophic numerics with the standard Eady-Boussinesq numerics when looking at a frontal formation example, and found that the standard Boussinesq solution does not go to the semi-geostrophic solution as the Rossby number tends to 0. They hypothesised that the standard numerics are going to the wrong solution due to numerical dissipation. This work looked at constructing a new Lagrangian based approach for this frontal problem in weather forecasting, utilising the work of Gallou ̈et and M ́erigot (2016), that removes the need for artificial compressibility, and instead implements a timestepping algorithm that incorporates an incompressibility constraint. We set out a potential new timestepping method for the incompressible Euler equations that involves optimal transport and a constrained symplectic algorithm, and conclude that our method performs favourably compared with the method of Gallou ̈et and M ́erigot (2016). Future work would involve implementing our method on the full Eady model problem, to see how our method compares to the Eulerian solution.

## Education

### Imperial College London
##### PhD Student in Mathematics with MPE CDT
2017-

### Imperial College London
##### MRes in Mathematics with MPE CDT
2016-2017

### University of Bath
##### MMath(Hons) Mathematics with year long work placement
2011-2016
