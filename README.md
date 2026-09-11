# CASTLE: An L-shell Specific Radiation Belt Forecasting Suite

CASTLE (**C**OVEN **A**pplied to a **S**pecific **T**errestrial **L**-shell **E**nvironment) is a suite of VAMPIRE, predicting if the maximum daily 1.8MeV Electron Flux for a given L-shell (or GEO) will exceed a threshold set at their respective 60th, 70th, 80th, 90th and 95th Percentiles.

Each model uses a random forest methodology and uses selected inputs from the OMNI dataset, with the flux measurements from Van Allen Probe,

Within the 'Example Notebooks' folder is a python notebook that takes the input data (found in the data file) and trains and shows the performance of 20 Models, 5 different thresholds accross 3 L-shells and GEO

