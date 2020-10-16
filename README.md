# NCAR-NEON
Repository for developing code related to NCAR-NEON workshop

Fork this repository to your github account

Bring the fork into your local Rstudio (or other) environment.

## To generate monthly forcing files from tower met data
modify and run `/TowerTools_ForcingData/flow.api.clm.R`  This code does the following:
- Collates NEON data from API, 
- Gap-filling with ReddyProc, and 
- Packages output in NCAR CLM netcdf format
- Makes simple plots to highlight missing data fields
