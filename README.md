# Kepler Exoplanet Prediction

This project aims to predict whether a Kepler candidate is a confirmed exoplanet or a false positive using several machine learning algorithms. The project involves Exploratory Data Analysis (EDA), data cleaning, feature engineering, and the application of some famous classification algorithms.

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Acknowledgements](#acknowledgements)

## Project Description
The Kepler Exoplanet Prediction project uses dataset provided by NASA's Kepler space telescope to classify exoplanet candidates. The dataset includes various features that describe the properties of potential exoplanets. The target field is `koi_disposition`, which indicates whether a candidate is a confirmed exoplanet (`CONFIRMED`) or a false positive (`FALSE POSITIVE`).

### Steps Involved:
1. **Data Cleaning**: Handle missing values, drop irrelevant columns, and filter rows based on the target variable.
2. **Exploratory Data Analysis (EDA)**: Perform comprehensive analysis to understand the dataset using heatmaps, curves and pairplots.
3. **Feature Engineering**: Prepare and scale the data for modeling and fine tune the prediction algorithms.
4. **Modeling**: Apply and evaluate multiple classification algorithms:
   - Logistic Regression
   - Naive Bayes Classifier
   - Random Forest Classifier
   - Support Vector Machine
5. **Evaluation**: Assess model performance using accuracy, precision, recall, F1 score, and confusion matrix.

## Dataset
The dataset used for this project is available on [Kaggle](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results/data).

## Installation
To run this project, you need to have Python installed along with the dependencies:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

```bash
git clone https://github.com/Dang3Rsm/ML-Keplers-exoplanet-prediction
cd kepler-exoplanet-prediction
```

## Acknowledgements
This project was only possible under the guidance of Senior Vaibhav Singh (School of Engineering, Jawaharlal Nehru University, New Delhi) who mentored me through this project through LSMP (LooP Summer Mentorship Program, AI/ML batch).

LooP is developers club at School of Engineering, Jawaharlal Nehru University, New Delhi.

NASA for the Kepler Space Telescope data.

Kaggle for hosting the dataset.
