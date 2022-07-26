# May 2022

This repository contains my final files for the May 2022 tabular playground series competition.

The competition goal was to predict whether a machine is in state 0 or 1 based on manufacturing control data.

The files in this repository are :

- plot_interactions.Rmd: plot all combination of variables to find interactions for feature engineering
- feature_engineering.Rmd: add new features to the original data
- NN_kfold.Rmd: kfold cross validation with Keras to find the best model
- NN_train_on_full.Rmd: first model trained on the full data
- NN_train_full_cat_as_dummy: second model trained on the full data
- LightGBM_kold_hyperparam_tuning.Rmd: parameter tuning for LightGBM, not used in the submission.

The final solution is an average of the two NN models and was ranked 8 on 1152 competitors (top 1%).

More detail on the process on my site:

[https://www.christophenicault.com/predict_machine_state/](https://www.christophenicault.com/predict_machine_state/)

