# Heart-Disease-Story-Telling

# Heart disease: What is my status? 

![image](https://user-images.githubusercontent.com/90922607/157613434-4ce53667-e4e7-45cc-b099-e57ee2c94cbd.png)

Heart disease is the top killer in the United States, with heart failure being a frequent consequence of Cardiovascular Diseases (CVDs), which are responsible for 31% of all global fatalities. The majority, 80%, of CVD deaths are caused by heart attacks and strokes, and a significant portion, one-third, of these deaths happen prematurely among individuals under the age of 70. 

### Context  
A mother recently learned about the possibility of having a heart attack from her doctor, who informed her that her blood pressure, cholesterol, and blood sugar levels were not in good range. She then asked me, as someone who studies data, if I could use my models to determine if she is at risk for heart disease and what factors contribute to a high cardiovascular risk.

In reality, early detection and management of cardiovascular disease and those at high risk for it is crucial, and machine learning models can play a vital role in this process. This is especially true for individuals who have risk factors such as hypertension, diabetes, hyperlipidemia, or a pre-existing heart condition..

The following presentation aims to address my mother's inquiry using the Heart Failure Prediction Dataset obtained from Kaggle.

Scope of Solution: The model creation should consider all the features, with a focus on sex, blood pressure, blood sugar, and cholesterol.

Limitations: The dataset lacks information about weight, race, and family history, which could be critical factors in the model.

Characterizing Factors of High Cardiovascular Risk: The presentation will highlight the key factors that increase the likelihood of developing heart disease

## Goal 
Is "to develop a model that accurately predicts the presence of heart disease in patients, given their demographic, medical, and lifestyle data" By leveraging patterns in the data to identify patients who are most likely to have heart disease. 


## results
Person with heart disease is more likely to be:
•Male more than female
•be person with normal resting electrocardiogram
•person who exercise-induced angina
•person with Asymptomatic chest pain type
•be person with fasting blood sugar  > 120 mg/dl (1)
•Female with heart disease tend to have Hight cholesterol than male
•
Ømean value of aged person with heart disease is 55.58
Ømean value of resting blood pressure of person with heart disease is 134.18
Ømean value of Max heart rate of person with heart disease is 127.65

# Model choice 
3 models developed
•KNN
•Random Forest
•XGBOOST

The results of the models, based on my mother's lab exams, indicate that she is not at risk for heart disease.

We placed a high importance on accurate predictions and faced the challenge of working with an unbalanced dataset. To determine the best model, we used the F1 Score metric.

After evaluating various models, we found that the best performing one was the Random Forest model.

### The benefits of this model are:

Improved patient outcomes: By accurately diagnosing heart disease at an early stage, the model can help to improve patient outcomes and prevent serious health problems.

Better risk stratification: By identifying patients who are at high risk of heart disease, the model can help healthcare providers to better stratify patients based on their risk, allowing them to prioritize care and allocate resources more effectively.

Reduced costs: By reducing the need for expensive and time-consuming diagnostic procedures, the model can help to reduce healthcare costs, making it more accessible and affordable for patients.

Improved decision-making: By providing healthcare providers with more accurate and comprehensive information about patients' health status, the model can help to inform and improve decision-making, leading to better outcomes for patients.

Increased understanding of heart disease: By analyzing the data used to build the model, researchers and healthcare providers can gain valuable insights into the underlying causes of heart disease and the factors that influence its development, helping to advance the field and improve treatments.
