# Heart-Disease-Story-Telling

# Heart disease: What is my status? 

![image](https://user-images.githubusercontent.com/90922607/157613434-4ce53667-e4e7-45cc-b099-e57ee2c94cbd.png)

●Heart disease is the leading cause of death in the United States. In fact, Heart failure is a common event caused by Cardiovascular diseases (CVDs)  which account for 31% of all deaths worldwide.  Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. 

### Context  
●My mom came to hear more about heart diseases. Her doctor said that she has a high risk of getting a heart attack because the exam showed that some values of the factors such as blood pressure, cholesterol, blood sugar are not good. 
●Then she said: I thought you were studying data, this is my lab exam result (.........), can you tell me what your models say?  Do I potentially subject to heart risk?  What are the factors that characterize people with high cardiovascular risk? 
•In fact, People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

The next presentation tries to answer Mom's question based on the Heart Failure Prediction Dataset taken from kaggle
Scope of solution space: The model development should take into account all the features with special attention on sex , blood pressure, blood sugar and cholesterol.
Constraints: the dataset miss information about weight, race , family history that I think could be important to the model.
Factors that characterize people with high cardiovascular risk

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
-All the model predict from lab exam that  mom have no risk to heart disease
-we cared about correct prediction, and we have unbalanced dataset
- we considered F1_score to select the best model
-The best Model is Random Forest
