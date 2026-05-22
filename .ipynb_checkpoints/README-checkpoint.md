# MA415

# Overview

This repository is meant to act on the NASA Exoplanet Archive information in order to predict the log radius, in terms of Earth radii, of exoplanets by using and applying various Machine Learning techniques.

# How to run

In order to run the code, preprocessing must first be done by running the `Preprocessing.ipynb` file - which also contains the baseline models and accuracy - as well as the file for regularization to generate the full datasets. From here `RANDOM_FOREST.ipynb`, `PCA_Gradient_Boosting_Trees.ipynb`, and `Gradient_Boosting_Trees.ipynb` are capable of being ran to fully to train and evaluate these models. Prior to the running of the `Gradient_Boosting_Trees_Post_Lasso.ipynb` and the `RANDOM_FOREST_Feature_Engineering.ipynb`, the file `Linear_with_feature_engineering.ipynb`. The `Demo.ipynb` can also be run to create the best model and evaluate its performance on data points.

# Packages

The following packages must be installed in order for all relevant code to be fully runnable

`numpy`
`pandas`
`sklearn`
`matplotlib`
`plotly`

# Where the data came from

All data was sourced from https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView, and is present in `ExoplanetArchiveAll.csv` and `ExoplanetArchiveValuesOnly.csv`. All data resulting from this is processed internally to create multiple other .csv files that can be used in model training.

# Where it must go

The data must be placed in the same folder as the scripts, as they expect all relevant csv's to share a base directory with them.