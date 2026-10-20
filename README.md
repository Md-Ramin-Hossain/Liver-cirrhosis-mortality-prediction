# Liver-cirrhosis-mortality-prediction
Machine learning-based liver cirrhosis mortality prediction using class-imbalance handling and SHAP explainability.
# Liver Cirrhosis Mortality Prediction Using Machine Learning

## Overview

This repository contains the research materials for an undergraduate CSE thesis on predicting mortality outcomes in patients with liver cirrhosis using machine learning and explainable artificial intelligence (XAI).

The research investigates class imbalance, compares sampling techniques and machine learning models, and uses SHAP to interpret model predictions.

## Research Objectives

- Predict patient mortality outcomes using clinical data.
- Investigate the impact of class imbalance on model performance.
- Compare sampling techniques and model combinations.
- Evaluate classification performance using appropriate metrics.
- Interpret model predictions using SHAP.

## Dataset

The study uses the Mayo Clinic Primary Biliary Cirrhosis (PBC) dataset.

Refer to the original dataset source and its terms of use before reproducing the experiments. The dataset itself is not included unless redistribution is explicitly permitted.

## Methods

The research investigates sampling approaches including:

- Tomek Links
- TVAE (Tabular Variational Autoencoder)
- ADASYN
- SMOTENC
- The original, unsampled data as a baseline

Multiple machine learning models are evaluated using the experimental setup documented in the notebooks.

## Explainable AI

SHAP (SHapley Additive exPlanations) is used to investigate the contribution of clinical features to model predictions.

## Repository Structure

- `notebooks/`: Research notebooks and experiments
- `results/`: Model evaluation figures and SHAP visualizations
- `docs/`: Approved thesis documentation

## Experimental Results

Add the verified results from the final thesis, including the selected model and sampling combination, accuracy, recall, and other reported evaluation metrics.

Do not interpret these metrics as evidence of clinical effectiveness without appropriate external validation.

## Reproducibility

Python version: [Add the version used in the experiments]

Install the required dependencies listed in `requirements.txt`, then open the notebooks in Jupyter Notebook or JupyterLab.

Additional dataset preparation and execution instructions should be documented in the notebooks.

## Disclaimer

This repository is intended for academic research and educational purposes. The models are not intended to replace professional medical judgment or clinical decision-making.

## Academic Context

Undergraduate thesis project, Department of Computer Science and Engineering, Northern University Bangladesh.
