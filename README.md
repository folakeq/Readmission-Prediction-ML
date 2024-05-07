# Readmission-Prediction-ML
I worked on this project a couple of years back, as a capstone to a Machine Learning training I participated in. The program is a classification model that predicts whether or not a patient is readmitted. Numerous Machine Learning algorithms were used to train the data with the Random Forest Classification performing best.
In building this model, the following steps were involved:
- Data Ingestion
- Data Visualization
- Data Cleaning
- Dummy Coding
- Model Training and Fine Tuning

The files in this repository are as follows:
1. diabetic_data.csv : a dataset containing hospital readmission data for over a hundred thousand patients
2. IDs_mapping.csv : describing the codes for the admission_type_id, discharge_disposition_id, admission_source_id columns in the dataset
3. icd9_diagnosis.csv : created to explain the International Classification of Diseases Codes
4. final_model_evaluation.csv : containing information on the Machine Learning algorithms used in prediction, their sampling methos, parameters and performnace
5. final_feature_importance_readmission_ml.csv : containing the importance level of the features used in predicting readmission
6. Hospital Readmission Predictive Model.ipynb : the Machine Learning Model used to predict readmission
