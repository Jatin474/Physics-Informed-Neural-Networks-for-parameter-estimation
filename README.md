# Physics Informed Neural Networks for Parameter Estimation

## Overview

This project focuses on implementing Physics Informed Neural Networks (PINNs) to solve various problems in fluid dynamics and heat transfer. The aim is to leverage the capabilities of neural networks to estimate parameters and solve both direct and inverse problems related to different physical equations. This work was a part of Undergraduate Project under the guidance of Prof. Malay Kumar Das at IIT Kanpur.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Key Components](#key-components)
   - [Blasius Equation](#blasius-equation)
   - [Flow Over Flat Plate](#flow-over-flat-plate)
   - [Navier-Stokes Equations](#navier-stokes-equations)
   - [Heat Equations](#heat-equations)
3. [Documentation](#documentation)
4. [Installation and Usage](#installation-and-usage)
5. [Acknowledgments](#acknowledgments)

## 1. Project Structure

The project consists of several Jupyter notebooks that address different problems using PINNs. The files included are:

- `Blasius Equation - Direct problem.ipynb`
- `Blasius Equation - inverse solution.ipynb`
- `Convection_problem.ipynb`
- `Flow over the flat plate - Direct Problem.ipynb`
- `Flow over the flat plate - inverse solution.ipynb`
- `Full Navier Stokes with Energy Consideration- Direct and inverse.ipynb`
- `PINN_documentation.pdf`
- `README.md`
- `Steady 1D heat equation - Direct and Inverse.ipynb`
- `Steady 2D Heat Equation.ipynb`
- `Unsteady 1D Heat Equation - Inverse Problem.ipynb`
- `Unsteady 1D Heat Equation.ipynb`

## 2. Key Components

### Blasius Equation

- **Direct Problem**: The notebook `Blasius Equation - Direct problem.ipynb` solves the Blasius equation, a fundamental problem in boundary layer theory.
- **Inverse Solution**: The notebook `Blasius Equation - inverse solution.ipynb` employs a PINN to estimate parameters from given boundary conditions.

### Flow Over Flat Plate

- **Direct Problem**: The notebook `Flow over the flat plate - Direct Problem.ipynb` simulates the flow over a flat plate using PINNs.
- **Inverse Solution**: The notebook `Flow over the flat plate - inverse solution.ipynb` estimates flow parameters based on observed data.

### Navier-Stokes Equations

- **Full Navier-Stokes with Energy Consideration**: The notebook `Full Navier Stokes with Energy Consideration- Direct and inverse.ipynb` addresses both direct and inverse problems related to the Navier-Stokes equations with energy considerations.

### Heat Equations

- **Steady and Unsteady Heat Equations**: Multiple notebooks, including `Steady 1D heat equation - Direct and Inverse.ipynb`, `Steady 2D Heat Equation.ipynb`, and `Unsteady 1D Heat Equation.ipynb`, focus on solving heat equations using PINNs for various conditions and configurations.

## 3. Documentation

The project includes a comprehensive PDF document (`PINN_documentation.pdf`) detailing the methodology, equations, and results for each of the implemented problems. It serves as a guide for understanding the theoretical background and practical applications of the methods used.

## 4. Installation and Usage

To run the notebooks, you will need:

- Python (version 3.6 or higher)
- Jupyter Notebook or Jupyter Lab
- Required libraries (e.g., TensorFlow, NumPy, SciPy)

### Steps to Execute

1. Clone the repository:
   ```bash
   git clone <https://github.com/Jatin474/Physics-Informed-Neural-Networks-for-parameter-estimation>
   cd Physics-Informed-Neural-Networks

2. Install required packages (if not already installed): Create a requirements.txt file with the necessary libraries, or manually install them using:

    ```bash
    pip install tensorflow numpy scipy matplotlib

3. Launch Jupyter Notebook:

    ```bash

    jupyter notebook

4. Open the relevant notebook: Navigate to the directory containing the notebooks and select the one you want to run.

5. Run the cells: Execute the cells in the notebook to perform the analysis and view the results.

## 5. Acknowledgments

Special thanks to the developers and contributors of the TensorFlow library for providing essential tools for building and training neural networks.
Acknowledgment to the authors of the PINN literature for their foundational research, which guided the implementation of these models.
Thanks to the open-source community for providing valuable resources and libraries that made this project possible.
Appreciation to the contributors of scientific literature on fluid dynamics and heat transfer for the theoretical frameworks used in this project
