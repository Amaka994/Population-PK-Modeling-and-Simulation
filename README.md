# Population-PK-Modeling-and-Simulation
# Population Pharmacokinetic Modeling and Simulation Using Python

## Project Overview

This repository demonstrates the application of Python to pharmacokinetic (PK) data exploration, visualization, and model-based simulation.

The project uses a simulated one-compartment intravenous bolus pharmacokinetic dataset to investigate concentration–time profiles, interindividual variability, and population drug exposure.

The objective is to apply quantitative pharmacology and pharmacometric principles to characterize drug disposition and demonstrate reproducible PK analyses using Python.

## Dataset Description

The dataset, `Bolus_1CPT.csv`, contains simulated pharmacokinetic observations from 120 subjects.

The dataset includes 7,920 records and 14 variables, including:

- Subject identification (ID)
- Sampling time (TIME)
- Observed drug concentration (DV)
- Dose amount (AMT)
- Clearance (CL)
- Volume of distribution (V)
- Dosing and observation event indicators (EVID, MDV)

The dataset supports the investigation of pharmacokinetic variability and concentration–time relationships.

**Data source:** Original source and license information to be added.

## Pharmacokinetic Data Exploration

Exploratory analyses were conducted using Python to examine the structure and characteristics of the dataset.

The analyses include:

- Assessment of dataset dimensions and variable structure.
- Identification of dosing and observation records.
- Visualization of individual concentration–time profiles.
- Comparison of concentration profiles across subjects.
- Examination of plasma sampling times.

## Population Pharmacokinetic Simulation

A one-compartment pharmacokinetic model with intravenous bolus administration is used to investigate drug concentration–time relationships.

The model is described by:

**C(t) = (Dose / V) × exp(−(CL / V) × t)**

where:

- C(t) represents plasma drug concentration at time t.
- Dose represents the administered dose.
- CL represents drug clearance.
- V represents the volume of distribution.
- t represents time after administration.

For repeated intravenous bolus administration, concentrations are calculated using superposition of individual dose contributions.

## Monte Carlo Simulation

A Monte Carlo simulation framework is being developed to evaluate variability in predicted drug exposure.

The simulation framework includes:

- Generation of 10,000 virtual subjects.
- Resampling of pharmacokinetic parameters from the original dataset.
- Simulation of population concentration–time profiles.
- Calculation of median concentrations and 90% population prediction intervals.
- Evaluation of hypothetical concentration target attainment.

The simulated target is intended for methodological demonstration and does not represent a validated clinical therapeutic threshold.

## Python Libraries

The project uses:

- **Pandas:** Data management and manipulation.
- **NumPy:** Numerical computation and pharmacokinetic simulation.
- **Matplotlib:** Visualization of concentration–time profiles and simulation results.
- **Google Colab:** Interactive Python notebook environment.

## R Markdown
## Featured Project: Population PK Modeling and Monte Carlo Simulation in R

This project demonstrates reproducible pharmacokinetic modeling, exploratory data analysis, and Monte Carlo simulation using **R and R Markdown**.

### View the Complete R Project Report

**[View Population PK Modeling and Monte Carlo Simulation Report](https://amaka994.github.io/Population-PK-Modeling-and-Simulation/01_PK_Modeling_and_Monte_Carlo.html)**

The report includes:

- Exploratory analysis of simulated pharmacokinetic data from 120 subjects
- Individual and population concentration–time profiles
- One-compartment repeated intravenous bolus pharmacokinetic modeling
- Monte Carlo simulation of 10,000 virtual subjects
- Population variability and 90% prediction intervals
- Observed versus simulated concentration–time visualization
- Reproducible R code, figures, and simulation results

**Tools:** R, RStudio, R Markdown, ggplot2, dplyr, and Monte Carlo simulation.


## Repository Contents

`01_PK_Data_Exploration.ipynb` — Exploratory analysis and visualization of simulated pharmacokinetic data.

Additional notebooks will be added as modeling and simulation analyses are completed.

## Scientific Applications

This project demonstrates computational approaches relevant to:

- Population pharmacokinetics.
- Pharmacokinetic variability.
- Model-informed drug development.
- Monte Carlo simulation.
- Exposure analysis.
- Pharmacodynamic target attainment.

## Reproducibility

The analyses are implemented in Python using Jupyter notebooks.

The original dataset source and applicable usage permissions will be documented to support reproducibility.

## Disclaimer

This project uses simulated pharmacokinetic data for methodological demonstration and educational purposes. The results are not intended to support clinical dosing recommendations.

## Author

Pharmacometrics | Clinical Pharmacology | Quantitative Pharmacology | Model-Informed Drug Development
