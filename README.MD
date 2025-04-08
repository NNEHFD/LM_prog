# Code to accompanying paper "A tutorial on improving RCT power using prognostic score adjustment for linear models"
Simulation code uses the R-package ['postcard'](https://github.com/NovoNordisk-OpenSource/postcard) to conduct inference using prognostic score adjustment for linear models. The code is organized with an introductory example (example.R) which can be run on its own.
The data is simulated using the data generating process in dpg_lin.R. The estimators used to generate estimates of the ATE and standard errors are mainly found using 'rctglm' from 'postcard' but for the PSM-RCT method a seperate R script (psm.R) is used. 
A function for running the experiment is produced in the experiment_lin.R file. The run_experiment_lin.R file loads the scripts individually and runs the full simulation study in different scenarios. The results_lin.R script produces figures in the paper.

This work is conducted by Emilie Højbjerre-Frandsen, Mathias Lerbech Jeppesen, Rasmus Kuhr Jensen, Claus
Dethlefsen, and Rasmus Waagepetersen. Please submit an issue for any questions or concerns.
