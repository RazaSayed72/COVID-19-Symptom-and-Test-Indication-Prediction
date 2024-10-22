# COVID-19-Symptom-and-Test-Indication-Prediction
This project analyzes COVID-19 test results based on symptoms such as cough, fever, and other factors like age, gender, and test indication (e.g., travel history). It aims to predict whether an individual will test positive or negative for COVID-19 based on these features.

Overview
This project utilizes a dataset containing COVID-19 test results, symptoms, and demographic information to predict whether an individual will test positive or negative for the virus. By analyzing symptoms like cough, fever, and other factors such as age, gender, and test indication (e.g., travel history), we aim to develop a predictive model for COVID-19 outcomes.

Dataset
The dataset consists of the following features:
cough: Binary value indicating if the patient has a cough (1: Yes, 0: No)
fever: Binary value indicating if the patient has a fever (1: Yes, 0: No)
sore_throat: Binary value indicating if the patient has a sore throat (1: Yes, 0: No)
shortness_of_breath: Binary value indicating if the patient has shortness of breath (1: Yes, 0: No)
head_ache: Binary value indicating if the patient has a headache (1: Yes, 0: No)
age_60_and_above: Binary value indicating if the patient is 60 years or older (Yes/No)
gender: Patient’s gender (male/female)
test_indication: The reason for the COVID-19 test (Abroad/Other)
corona_result: The result of the COVID-19 test (positive/negative)


Goal
The main goal of this project is to:
Predict the likelihood of a positive or negative COVID-19 test result based on patient symptoms, demographics, and test indications.
Gain insights into the most significant symptoms or factors contributing to a positive test outcome.
