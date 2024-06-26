[![DOI](https://zenodo.org/badge/758835468.svg)](https://zenodo.org/badge/latestdoi/758835468)

# Predicting postoperative visual acuity in ERM patients and analyzing variables using machine learning

Code for our PLOS ONE paper:

**"Predicting postoperative visual acuity in epiretinal membrane patients and visualization of the contribution of explanatory variables in a machine learning model"**

Full paper link: https://doi.org/10.1371/journal.pone.0304281

**Abstract**
The purpose of this study was to develop a model that can predict the postoperative visual acuity in eyes that had undergone vitrectomy for an epiretinal membrane (ERM). The Light Gradient Boosting Machine (LightGBM) was used to evaluate the accuracy of the prediction and the contribution of the explanatory variables. Two models were designed to predict the postoperative visual acuity in 67 ERM patients. Model 1 used the age, sex, affected eye, axial length, preoperative visual acuity, Govetto's classification stage, and OCT-derived vector information as features to predict the visual acuity at 1, 3, and 6 months postoperatively. Model 2 incorporated the early postoperative visual acuity as an additional variable to predict the visual acuity at 3, and 6 months postoperatively. LightGBM with 100 iterations of 5-fold cross-validation was used to tune the hyperparameters and train the model. This involved addressing multicollinearity and selecting the explanatory variables. The generalized performance of these models was evaluated using the root mean squared error (RMSE) in a 5-fold cross-validation, and the contributions of the explanatory variables were visualized using the average Shapley Additive exPlanations (SHAP) values.

## Description
This code is for experimental clarification. Unfortunately, we cannot share the dataset or original OCT images as they contain personal information.

## Tasks
* Predict Postoperative Visual Acuity(1,3,6 months) of ERM patients

* Provide a patient-specific interpretation of predicted result

## Algorithms:
* LightGBM

* optuna

* SHAP

## Info
Language: Python3

Platform: Linux

by Koki Imai, February 2024

## Requirement
```
numpy==1.25.2
pandas==1.5.3
seaborn==0.12.2
shap==0.43.0
lightgbm==3.3.5
optuna==3.1.0
matplotlib==3.7.2
scikit-learn==1.3.0
statsmodels==0.14.0
```

## Citation
```
@article{
doi = {10.1371/journal.pone.0304281},
author = {Irie-Ota, Akiko and Matsui, Yoshitsugu and Imai, Koki and Mase, Yoko and Konno, Keiichiro and Sasaki, Taku and Chujo, Shinichiro and Matsubara, Hisashi and Kawanaka, Hiroharu and Kondo, Mineo},
journal = {PLOS ONE},
title = {Predicting postoperative visual acuity in epiretinal membrane patients and visualization of the contribution of explanatory variables in a machine learning model},
year = {2024},
month = {05},
url = {https://doi.org/10.1371/journal.pone.0304281},
}
```
