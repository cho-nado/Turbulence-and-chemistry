# Course Project: Turbulence and Combustion Modeling
##  Project Overview

This repository contains code and calculations conducted as part of the course project for "Turbulence and Combustion Modeling." The project explores theoretical and numerical methods for analyzing boundary layers and simulating chemical reactions in gas mixtures.

## Key Topics Covered
### 1. Turbulent Boundary Layer Analysis
- Definition and distinction between laminar and turbulent boundary layers
- Conservation laws for mass and momentum in boundary layers
- Prandtl’s similarity laws and logarithmic velocity profiles
- Calculation of boundary layer thickness, displacement thickness, and momentum thickness
- Reynolds number and flow transition criteria

### 2. Numerical Calculations and Data Analysis
- Conversion of sensor readings from millivolts to velocity using interpolation
- Determination of boundary layer thickness using experimental data
- Approximation of velocity profiles with power functions
- Calculation of friction stress on the wall using Clauser’s method
- Computation of the local friction coefficient and Reynolds number

### 3. Combustion Modeling and Thermodynamic Equilibrium
- Homogeneous system equilibrium conditions
- Application of the law of mass action for chemical reaction equilibrium
- Calculation of equilibrium constants as a function of temperature
- Determination of enthalpy, entropy, and Gibbs free energy changes
- Evaluation of molar and mass fractions of reacting components
- Calculation of specific heat capacities at constant pressure and volume
- Density and specific volume analysis of the reacting mixture

## Implemented Methods
- **Numerical integration** (trapezoidal rule) for calculating boundary layer parameters
- **Interpolation techniques** for experimental data conversion
- **Curve fitting** for velocity profile approximation
- **Root-finding methods** (bisection method) for equilibrium calculations
- **Matplotlib visualizations** for boundary layer profiles, reaction equilibrium, and thermodynamic properties

## Results & Visualizations
- Graphical representations of velocity profiles in turbulent boundary layers
- Comparison of experimental and theoretical boundary layer models
- Plots of reaction equilibrium constants as a function of temperature
- Graphs of species concentration, heat capacity, density, and specific volume variations

## How to Use
1. Clone the repository

        git clone https://github.com/your-repo-name
   
3. Install dependencies:

        pip install numpy scipy matplotlib pandas

Run the analysis scripts to reproduce calculations and visualizations.

## References
- L.D. Landau, E.M. Lifshitz, Fluid Mechanics, Vol. 6, 1986.
- H. Schlichting, Boundary-Layer Theory, 1974.
- A.N. Kolmogorov, Turbulence, 1941.
- Course lectures on Turbulence and Combustion Modeling, Moscow Aviation Institute, 2024.

For detailed code and calculations, check the corresponding Python scripts in this repository.
