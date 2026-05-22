# MA415

# Overview

This repository is meant to act on the NASA Exoplanet Archive information in order to predict the log radius, in terms of Earth radii, of exoplanets by using and applying various Machine Learning techniques.

# How to run

In order to run the code, preprocessing must first be done by running the Preprocessing_ipynb file - which also contains the baseline models and accuracy - as well as the file for regularization to generate the full datasets. Then, any .ipynb file with a relevant model (Ones starting with RANDOM_FOREST or Gradient_Boosting_trees) can be run fully to train and evaluate a model. Demo.ipynb can also be run to create the best model and evaluate its performance on data points.

# Packages



# Where the data came from

All data was sourced from https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS, and is present in ExoplanetArchiveAll.csv and ExoplanetArchiveValuesOnly.csv. All data 

# Where it must go

The data must be placed in the same folder as the scripts, as they expect all relevant csv's to share a base directory with them.