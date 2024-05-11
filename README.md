# Heart-Disease-Prediction
![654eb5b80e73ac9da953cf4a_shutterstock_2136963483](https://github.com/nayana142/Heart-Disease-Analysis-/assets/120770261/b2989d7b-7eb4-444f-8291-ed29c3e1940d)
## About Dataset
This heart disease dataset is curated by combining 5 popular heart disease datasets already available independently but not combined before. In this dataset,
5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes.
The five datasets used for its curation are:

    Cleveland
    Hungarian
    Switzerland
    Long Beach VA
Statlog (Heart) Data Set.
This dataset consists of 1190 instances with 11 features. These datasets were collected and combined at one place to help advance research on CAD-related machine learning and data mining algorithms, and hopefully to ultimately advance clinical diagnosis and early treatment.
## Dataset
    https://www.kaggle.com/datasets/mexwell/heart-disease-dataset
## Column descriptions
| S.No. | Attribute Code              | Description                           | Unit             | Data Type |
|-------|-----------------------------|---------------------------------------|------------------|-----------|
| 1     | age                         | Age in years                          | -                | Numeric   |
| 2     | sex                         | Sex                                   | 1, 0             | Binary    |
| 3     | chest pain type             | Chest pain type                       | 1, 2, 3, 4       | Nominal   |
| 4     | resting blood pressure      | Resting blood pressure                | mm Hg            | Numeric   |
| 5     | serum cholesterol           | Serum cholesterol                     | mg/dl            | Numeric   |
| 6     | fasting blood sugar         | Fasting blood sugar                   | 1, 0 (> 120 mg/dl) | Binary  |
| 7     | resting electrocardiogram results | Resting electrocardiogram results | 0, 1, 2          | Nominal   |
| 8     | maximum heart rate achieved | Maximum heart rate achieved           | bpm (71–202)     | Numeric   |
| 9     | exercise induced angina     | Exercise induced angina               | 0, 1             | Binary    |
| 10    | oldpeak                     | ST depression induced by exercise     | -                | Numeric   |
| 11    | ST slope                    | The slope of the peak exercise ST segment | 0, 1, 2       | Nominal   |
| 12    | class                       | Target                                | 0, 1             | Binary    |

## Nominal attributes

| Attribute                     | Description                                                                                                                                                                    |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sex                           | 1 = male, 0 = female                                                                                                                                                           |
| Chest Pain Type               | - Value 1: typical angina <br>- Value 2: atypical angina <br>- Value 3: non-anginal pain <br>- Value 4: asymptomatic                                                           |
| Fasting Blood Sugar           | (fasting blood sugar > 120 mg/dl) <br> (1 = true; 0 = false)                                                                                                                   |
| Resting Electrocardiogram Results | - Value 0: normal <br>- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) <br>- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria |
| Exercise Induced Angina       | 1 = yes; 0 = no                                                                                                                                                                |
| The Slope of the Peak Exercise ST Segment | - Value 1: upsloping <br>- Value 2: flat <br>- Value 3: downsloping                                                                                                           |
| Class                         | 1 = heart disease, 0 = Normal                                                                                                                                                 |


# Heart-Disease-Analysis

![982a4cde-09b6-411b-959a-adb9cc2dec36_1680x1210](https://github.com/nayana142/Heart-Disease-Analysis-/assets/120770261/c36e3f52-0ca0-4c73-b07c-088d2073cf97)

## Context
This is a multivariate type of dataset which means providing or involving a variety of separate mathematical or statistical variables,
multivariate numerical data analysis. It is composed of 14 attributes which are age, sex, chest pain type, resting blood pressure, serum 
cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, oldpeak — ST
depression induced by exercise relative to rest, the slope of the peak exercise ST segment, number of major vessels and Thalassemia. This 
database includes 76 attributes, but all published studies relate to the use of a subset of 14 of them. The Cleveland database is the only
one used by ML researchers to date. One of the major tasks on this dataset is to predict based on the given attributes of a patient that 
whether that particular person has heart disease or not and other is the experimental task to diagnose and find out various insights from this
dataset which could help in understanding the problem more.

## Dataset
     https://www.kaggle.com/datasets/abdmental01/heart-disease-dataset
## Column descriptions
| Column    | Description                                                                       |
|-----------|-----------------------------------------------------------------------------------|
| id        | Unique id for each patient                                                       |
| age       | Age of the patient in years                                                      |
| origin    | Place of study                                                                    |
| sex       | Male/Female                                                                       |
| cp        | Chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])   |
| trestbps  | Resting blood pressure (in mm Hg on admission to the hospital)                   |
| chol      | Serum cholesterol in mg/dl                                                        |
| fbs       | Fasting blood sugar (if fasting blood sugar > 120 mg/dl)                          |
| restecg   | Resting electrocardiographic results (Values: [normal, stt abnormality, lv hypertrophy]) |
| thalach   | Maximum heart rate achieved                                                      |
| exang     | Exercise-induced angina (True/ False)                                            |
| oldpeak   | ST depression induced by exercise relative to rest                                |
| slope     | The slope of the peak exercise ST segment                                         |
| ca        | Number of major vessels (0-3) colored by fluoroscopy                              |
| thal      | Thalassemia type ([normal; fixed defect; reversible defect])                      |
| num       | The predicted attribute
