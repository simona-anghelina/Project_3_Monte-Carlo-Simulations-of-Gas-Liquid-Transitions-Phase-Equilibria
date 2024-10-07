# Monte Carlo Simulations of Gas-Liquid Transitions and Phase Equilibria
This project involves the simulation of gas-liquid transitions using Monte Carlo techniques. 
We explore phase equilibria by modeling interactions between particles using the Lennard-Jones potential in the isobaric ensemble.

# Project Overview
The main goal of this project is to simulate and analyze phase transitions between gas and liquid states using Monte Carlo simulations. 
We explore the thermodynamic properties of the system and investigate phase equilibria in relation to temperature, pressure, and volume.

# Introduction
Phase transitions between gas and liquid are fundamental in thermodynamics and physical chemistry. 
This project aims to model these transitions using Monte Carlo simulations under specific thermodynamic conditions. 
We use the Lennard-Jones potential to describe particle interactions and simulate in the isobaric ensemble, allowing both particle movements and volume fluctuations.

# Libraries Used
This project utilizes the following Python libraries:

* NumPy: For efficient numerical computation.
* Matplotlib: For visualizing results and plotting.


# Results
The following distributions were analyzed as part of the simulation results:

1. Volume Distribution
  * A probability distribution of system volumes across the simulation, showing how the volume fluctuates in the isobaric ensemble.
  * This gives insights into the equilibrium state of the system at various pressures and temperatures.
2. Density Distribution
  * A density distribution over time was plotted, reflecting the transition between gas and liquid states.
  * Peaks in the distribution correspond to the presence of distinct phases (gas or liquid), while the coexistence region is represented by a broader distribution.
3. Radial Distribution Function (g(r))
  * The radial distribution function was calculated to analyze the structure of the system.
  * The g(r) function shows how particle density varies as a function of distance from a reference particle, providing insights into local ordering within gas and liquid phases.

# Key Plots
1. Volume distribution showing fluctuations in system volume during simulation.
2. Density distribution highlighting gas-liquid phase separation.
3. Radial distribution function revealing particle organization in the different phases.
