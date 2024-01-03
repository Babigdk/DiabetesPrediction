# Diabetes Prediction Project

## Overview

This project utilizes a dataset obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. The primary objective is to diagnostically predict whether a patient has diabetes based on specific diagnostic measurements included in the dataset. The dataset is in CSV format and contains information about females who are at least 21 years old and of Pima Indian heritage.

## Dataset Information

The dataset comprises several variables, including both independent medical predictor variables and one target dependent variable, which is labeled as "Outcome." The independent variables consist of various diagnostic measurements, while the "Outcome" variable indicates whether the patient has diabetes (1) or not (0).

### Constraints on Data Selection

Several constraints were imposed during the selection of instances for this dataset. All patients included are females, at least 21 years old, and of Pima Indian heritage.

## Files

- `diabetes_dataset.csv`: The dataset in CSV format containing all the necessary information.

## Variables

### Independent Variables (Medical Predictor Variables)

1. `Pregnancies`: Number of times pregnant
2. `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. `BloodPressure`: Diastolic blood pressure (mm Hg)
4. `SkinThickness`: Triceps skin fold thickness (mm)
5. `Insulin`: 2-Hour serum insulin (mu U/ml)
6. `BMI`: Body mass index (weight in kg/(height in m)^2)
7. `DiabetesPedigreeFunction`: Diabetes pedigree function
8. `Age`: Age in years

### Dependent Variable

1. `Outcome`: Diabetes status (0: No diabetes, 1: Diabetes)

## Usage

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
