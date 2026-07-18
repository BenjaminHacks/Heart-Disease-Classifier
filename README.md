# Heart Disease Classifier
A binary classification model that predicts the presence of heart disease in patients using clinical data, built with logistic regression on the UCI Cleveland Heart Disease dataset.

## Overview
This project explores whether basic clinical measurements — such as age, cholesterol, resting blood pressure, chest pain type, and maximum heart rate — can predict the likelihood of heart disease in a patient. The model outputs a probability of disease presence, which is a common approach in early-stage clinical risk scoring tools.

## Dataset

Source: UCI Machine Learning Repository — Heart Disease Dataset

Size: 297 patients (after removing rows with missing values), 13 clinical features

Target: Binary — presence (1) or absence (0) of heart disease

Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). Heart Disease [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X.

## Methods

Data cleaning (handling missing values, encoding categorical features)

Feature scaling with StandardScaler

Logistic regression classifier (scikit-learn)

Evaluation using accuracy, precision/recall, ROC-AUC, and confusion matrix — with particular attention to recall/sensitivity, since missing a true positive case carries more clinical risk than a false alarm
