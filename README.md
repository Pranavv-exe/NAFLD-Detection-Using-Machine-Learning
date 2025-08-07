# NAFLD-Detection-Using-Machine-Learning

## Overview
This project implements a machine learning model to predict Non-Alcoholic Fatty Liver Disease (NAFLD) using the NHANES dataset (2017-2020 pre-pandemic data). The model leverages advanced techniques such as hyperparameter optimization with Optuna and cross-validation to ensure robust performance.

## Features
- End-to-end ML pipeline: data preprocessing, feature engineering, model training, and evaluation.
- Uses XGBoost model optimized through Optuna for better prediction accuracy.
- Achieved performance metrics:
  - Accuracy: 77.8%
  - AUC-ROC: 0.84
- Focus on healthcare AI, a high-impact and growing field.

## Dataset
The NHANES (National Health and Nutrition Examination Survey) data from 2017-2020 is used. This public health dataset includes approximately 8,000 participants, providing a rich source of medical and health-related information.

## Installation
To run this project locally, clone the repository and install the required dependencies:

```bash
git clone <repository-url>
cd nafld-detection
pip install -r requirements.txt
```

## Usage
- Run the Jupyter Notebook `nafld_detection.ipynb` to execute the full pipeline.
- The notebook includes detailed steps from data loading and preprocessing to model training and evaluation.

## Repository Structure
```text
nafld-detection/
├── README.md
├── requirements.txt
├── nafld_detection.ipynb
├── src/
│   └── utils.py
├── models/
└── results/
```
