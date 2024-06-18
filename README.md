# Comparative Analysis between Spatial, Spectral, and Temporal Domain Features in Simple and Complex Motor Imagery

This repository contains the code and data for the paper "Comparative Analysis between Spatial, Spectral, and Temporal Domain Features in Simple and Complex Motor Imagery."

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Feature Extraction Methods](#feature-extraction-methods)
- [Classification Pipeline](#classification-pipeline)
- [Usage](#usage)

## Introduction
This project investigates how features extracted from different domains (spatial, spectral, and temporal) affect the performance of quaternary motor imagery classification problems. The classification performance is compared between simple and complex motor imagery tasks.

## Datasets
The following publicly available motor imagery datasets are used in this study:
- **Dataset A**: Data Set IIa from BCI Competition IV
- **Dataset B**: Data Set IIIa from BCI Competition III
- **Dataset C**: Ofner et al. 2017
- **Dataset D**: Ofner et al. 2019

## Feature Extraction Methods
### Spatial Domain
- Common Spatial Patterns (CSP)
- Sparse CSP (SCSP)
- Source Power Comodulation (SPoC)

### Spectral Domain
- Welch's method for Power Spectral Density (PSD)
- Periodogram PSD estimation
- Yule-Walker method for PSD estimation

### Temporal Domain
- Hjorth Parameters
- Time Domain Parameters (TDP)
- Hurst Exponent

## Classification Pipeline
The EEG data is preprocessed and features are extracted using the methods described above. Four machine learning classifiers are used:
- Shrinkage-regularized Linear Discriminant Analysis (SRLDA)
- Support Vector Machine (SVM)
- Random Forest (RF)
- Logistic Regression (LR)

## Usage
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries: numpy, scipy, scikit-learn, mne
