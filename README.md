# Force Field Parameter Optimization using Particle Swarm Optimization (PSO)
This repository contains code for optimizing molecular force field parameters using the Particle Swarm Optimization (PSO) algorithm, as part of my master's thesis project. The goal of this project is to find the best parameters that reproduce target molecular properties efficiently.

# Overview
This project implements a PSO algorithm to optimize force field parameters for molecular systems. It allows users to define initial parameter ranges and target properties, and iteratively searches for the set of parameters that minimizes the difference between predicted and reference properties.

# Project Description
Force field parameters (bonded and non-bonded interactions) are critical for accurate molecular simulations. Manual parameter fitting is time-consuming, so this project leverages Particle Swarm Optimization, a population-based stochastic optimization method inspired by social behavior of birds, to automate parameter optimization.

The main objectives are:
- Optimize force field parameters for a given molecular system.
- Minimize the error between computed molecular properties and reference data.
- Provide a flexible framework for different molecular systems and force fields.

# Usage
Run the optimization by executing run.py. This script loads all necessary settings and parameter ranges from parameters.py to perform the PSO search.

# Results
The interaction energies computed with the PSO-optimized force field closely match those from Density Functional Theory (DFT), demonstrating that these parameters can reliably simulate molecular systems with similar atomic interactions.
