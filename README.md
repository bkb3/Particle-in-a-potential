# Particle-in-a-potential
A "classical" problem in quantum mechanics which every student faces. Here we find out the energy values of a particle trapped in a potential. Only the mathematica code part is here which helps us know the problem analytically.


The specfic problem we are dealing with here is 
<p align="center">
  <img src="http://i.imgur.com/eUIYwFT.png"/>
 </p>

The potential is symmetric under y axis as shown in the graph below obtained by running the mathematica code:
<p align="center">
  <img src="http://i.imgur.com/x9XJGyt.png"/>
 </p>
So we will look for solutions that are parity eigenstates. Solving Schrodinger wave equation (SWE) for x>=x0 we get a combination of parabolic cylindrical functions (Shown in mathematica code in traditional form for textbook like looks!).

Matching appropriate boundary conditions and a bit of simplification we get some useful expressions in terms of Hermite functions. (Shown in code)
The odd and even parity hermite polynomials are 
<p align="center">
  <img src="http://i.imgur.com/CNWa09g.png"/>
 </p>

Finally, we can plot the wave functions after finding appropriate coefficients of the solution wave functions/eigen functions of SWE. the selected eigen functions (1st and 3rd) are plotted as:
<p align="center">
  <img src="http://i.imgur.com/s7jdRsd.png"/>
 </p>


# TO DO
  - calculate energies in tabular form
  
# License
  - GNU GPL v3.0 or later on your opinion.
