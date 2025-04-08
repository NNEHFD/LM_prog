# Code to accompanying paper "A tutorial on improving RCT power using prognostic score adjustment for linear models"

This repository contains simulation code that utilizes the R package [postcard](https://github.com/NovoNordisk-OpenSource/postcard) to perform inference via prognostic score adjustment for linear models.

## Structure

- **Example**: The code includes an introductory example file (`example.R`) that can be executed independently.
- **Data Simulation**: Data is generated using the process defined in `dpg_lin.R`.
- **Estimators**: The estimators for calculating Average Treatment Effect (ATE) and standard errors are primarily derived using the `rctglm` function from the `postcard` package. For the PSM-RCT method, a dedicated script (`psm.R`) is provided.

## Experiment Workflow

- The function to execute the experiment is implemented in `experiment_lin.R`.
- The `run_experiment_lin.R` file loads the necessary scripts and runs the complete simulation study across various scenarios.
- Results are visualized through figures generated in the `results_lin.R` script.

## Acknowledgments

This work is authored by Emilie Højbjerre-Frandsen, Mathias Lerbech Jeppesen, Rasmus Kuhr Jensen, Claus Dethlefsen, and Rasmus Waagepetersen. 

For any questions or concerns, please feel free to submit an issue.
