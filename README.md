# Data_recovery_fraction_dwarf_galaxy_PAndAS
This directory contains the recovery of dwarf galaxies presented in Doliva-Dolinsky et al, 2022 and the algorithm used to fit a linear model. 
The directory "recovery_per_field" contains, for each non-masked field, the a table of recovered dwarf galaxies with 5 galaxies place per field per mv per log(rh). Each column are a magnitude bin, from -8.5 to -4.5 with a step of 0.25. Each line is a log(rh) bin, from 1.8 to 2.9 with a step of 0.1. 
The file model.py is the code used to obtain a linear fitting of the detection limits. 
