# Surface-Integral-Equation
Calculating optical cross sections from an arbitrary scatterer using surface integral equation.

Run the code through ``runner.m``.

How to build geometrical mesh by COMSOL:
1. Create the 3D object on COMSOL
2. Create the free triangular mesh at the object`s surface
3. Export the mesh in .mphtxt format
4. Import the created mesh in MATLAB. First chunk of columns consists of three row are ``p`` (triangle vertex points) and the second of the three row columns are ``t`` (triangle connection between the vertex points)
5. Substract variable ``t``by 1


