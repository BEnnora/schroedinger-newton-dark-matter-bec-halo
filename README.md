# Numerical Solution of the Schrödinger–Newton Equation for BEC-CDM Halos

This repository contains a Python-based numerical simulation of the Schrödinger–Newton equation, modeling the dispersion of wave functions in a self-gravitating Bose–Einstein Condensate (BEC) dark matter halo. The simulation applies the Thomas algorithm to solve the resulting tridiagonal system efficiently.

## 🧠 Project Overview

- **Objective**: Investigate the dynamics of a BEC-CDM halo by solving the Schrödinger–Newton equation numerically.
- **Methodology**: Finite difference discretization combined with the Thomas algorithm to solve the tridiagonal matrix system.
- **Outcome**: Due to computational limitations, the simulation does not yield observable dispersion. Instead, it explores numerical behavior under coarse discretization and discusses why the key observables \( r_{99} \) remains unchanged.

## 📁 Repository Contents

- `numerical-solution-SN-BEC-halo-thomas-algorithm.ipynb`: Jupyter Notebook with implementation.
- `Dispersion_von_Wellenfunktionen_im_Rahmen_der_Schr_dinger_Newton_Gleichung_am_Beispiel_eines_galaktischen_BEC_CDM_Halos.pdf`: Full thesis describing the theoretical background and implementation details of the simulation (in German).
- `README.md`: This file.

## 🔧 Requirements

- Python 3.x
- NumPy
- Jupyter Notebook

