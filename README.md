# Heart_Disease_Prediction_model

Classification model to predict heart disease


**Predicting heart disease using machine learning**:

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not some has heart disease based on their medical attrubutes.

This notbook will use the following approach/steps:

* Problem definition
* Data
* Evaluation
* Features
* Modeling
* Experimentation

### 1. Problem Definition

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

### 2. Data

The original data came from Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/45/heart+disease

There is also a version this dataset on Kaggle. https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data/data

### 3. Evaluation

If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

### 4. Features

This is where you'll get different information about each of the features in your data.

Data Dictionary (heart-disese.csv)

**Attribues used**:

`age` (Age of the patient in years)
`sex` (Male/Female)
`cp` chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
`trestbps` resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
`chol` (serum cholesterol in mg/dl)
`fbs` (if fasting blood sugar > 120 mg/dl)
`restecg` (resting electrocardiographic results) -- Values: [normal, stt abnormality, lv hypertrophy]
`thalach`: maximum heart rate achieved
`exang`: exercise-induced angina (True/ False)
`oldpeak`: ST depression induced by exercise relative to rest
`slope`: the slope of the peak exercise ST segment
`ca`: number of major vessels (0-3) colored by fluoroscopy
`thal`: [normal; fixed defect; reversible defect]
`target`: the predicted attribute
