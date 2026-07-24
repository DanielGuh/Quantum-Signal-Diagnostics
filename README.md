# Quantum Signal Diagnostics & Parameter Estimation Simulation

## Project Overview
This repository contains the end-to-end data analysis pipeline, statistical modeling scripts, and experimental findings for an Electron Spin Resonance (ESR) signal framework. The project focuses on processing raw instrumentation voltage data, executing linear regressions to calculate quantum magnetic g-factors, and evaluating overall system tolerances.

## Repository Architecture & Assets
* **`Electron Spin Data - Sheet1.csv`**: The raw instrumentation dataset capturing high-frequency voltage changes across varying magnetic field frequencies.
* **`ESR_Analysis.ipynb`**: The functional execution script handling data ingestion, automated linear regression modeling, parameter calculation, and data visualization.
* **`Electron Spin Resonance Report.pdf`**: The formal engineering and technical physics report detailing the comprehensive theoretical background, error propagation analysis, and final system validations.

## Core Methodologies & Technical Execution
* **Signal Diagnostics:** Ingested and parsed noisy time-series voltage data from laboratory hardware to successfully isolate key resonance peaks.
* **Parameter Estimation:** Implemented automated curve-fitting and linear regression workflows in Python to determine precise resonance frequencies and calculate the system's quantum magnetic constants.
* **Error Analysis:** Evaluated uncertainty propagation and regression diagnostics (R² optimization) to validate physical instrumentation constraints against theoretical quantum mechanics limits.

## Key Outcomes
* Successfully extracted the system's linear slope mapping frequency against the magnetic field.
* Documented experimental tolerances and data variances within the comprehensive PDF technical report.
