# heart-disease-classification
## 1. Problem Definition

In a statement,
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original data came from the CLeavland data from the UCI Machine Learning Repository https://archive.ics.uci.edu/ml/datasets/Heart+Disease

There is also a version of it available on Kaggle. https://www.kaggle.com/ronitf/heart-disease-uci

## 3. Evaluation

> If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

## 4. Features

This is where you'll get different information about wach of the features in your data

** Create data dictionary**

* 3 age: age in years
* 4 sex: sex (1 = male; 0 = female)
* 9 cp: chest pain type
* -- Value 0: typical angina
* -- Value 1: atypical angina
* -- Value 2: non-anginal pain
* -- Value 3: asymptomatic
* 10 trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* 12 chol: serum cholestoral in mg/dl
* 16 fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* 19 restecg: resting electrocardiographic results
* -- Value 0: normal
* -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
* -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
* 32 thalach: maximum heart rate achieved
* 38 exang: exercise induced angina (1 = yes; 0 = no)
* 40 oldpeak = ST depression induced by exercise relative to rest
* 41 slope: the slope of the peak exercise ST segment
* -- Value 0: upsloping
* -- Value 1: flat
* -- Value 2: downsloping
* 51 thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* 58 num: diagnosis of heart disease (angiographic disease status)
* -- Value 0: < 50% diameter narrowing
* -- Value 1: > 50% diameter narrowing
