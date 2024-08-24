# Soil Spectral Data Analysis and Machine Learning

This repository contains workflows, data, and code for soil spectral data analysis using machine learning techniques. The work involves importing and processing soil spectral data from various open libraries, developing machine learning models to predict soil properties, and performing literature reviews on recent deep learning methods in soil and sediment spectroscopy.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Data](#data)
4. [Methods](#methods)
   - [Modeling Approaches](#modeling-approaches)
5. [Results](#results)


## Introduction
The goal of this project is to explore the application of machine learning methods, including linear and deep learning models, to predict soil properties based on spectral data. The project focuses on datasets like the Open Soil Spectral Library (OSSL) and applies various signal processing techniques and modeling approaches to enhance prediction accuracy.

## Project Structure
- **data/**: Contains data files used or generated in the project.
- **notebooks/**: Jupyter notebooks with code for data exploration, preprocessing, and modeling.
- **scripts/**: Python scripts for processing data and training models.
- **results/**: Results from model runs, including performance metrics and visualizations.
- **references/**: Documentation and research papers relevant to the project.

## Data
The primary dataset used is the Open Soil Spectral Library (OSSL), which includes reflectance data in various spectral ranges (VisNIR, NIR, MIR). The data is processed using R and Python scripts to prepare it for machine learning models.

### Links to Data Sources:
- [Open Soil Spectral Library (OSSL)](https://soilspectroscopy.org/)
- [LUCAS Data](https://esdac.jrc.ec.europa.eu/projects/lucas)
- [Zenodo Records for OSSL](https://zenodo.org/records/7599269)

## Methods
The project applies both traditional and advanced machine learning methods to predict soil properties such as soil organic carbon (SOC). Key steps include:

1. **Data Preprocessing**:
   - Signal processing (e.g., smoothing, normalization).
   - Feature extraction using methods like PCA.
   
2. **Modeling Approaches**:
   - Baseline models: PLS regression.
   - Deep learning models: 1D Convolutional Neural Networks (1D-CNN), LSTM, etc.
   - Experimentation with different data resolutions and transformations (e.g., first derivative with Savitzky-Golay filter).

## Results
- The project has yielded models with varying performance. For example:
  - Best RMSE: 2.2199
  - Correlation coefficient: 0.9043
- Further improvements include experimenting with CNNs and refining data preprocessing techniques.

