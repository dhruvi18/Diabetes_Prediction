# Diabetes_Prediction


The objective of the dataset is to diagnostically predict whether a patient has diabetes or not based on certain parameters such as :
1.Pregnancies:To express the Number of pregnancies
2.Glucose:To express the Glucose level in blood
3.Blood Pressure:To express the Blood pressure measurement
4.Skin thickness:To express the thickness of the skin
5.Insulin:To express the Insulin level in blood
6.BMI:To express the Body Mass Index
7.Diabetes Pedigree Function:To express the Diabetes percentage
8.Age:To express the age

# Workflow for the project:
1.Downloaded the dataset from kaggle 

2.Data-preprocessing:The data is not suitable for directly feeding into Machine Learning model so have to standardize and analyze the data because inside the data there are lot of attributes so have to scale them in the same range in order to feed into the model

3.Comparision of the models using both Train-test-split and GridSearch CV:
Train-test split: split the data into training and testing data for finding the accuracy score to see how well are model is working.And even the comparision on the performance of the models(SVM,Logistic Regression,KNN,Random Forest) based on train test split. Using it the conclusion was that SVM is the best model for this data with an accuracy score of 77%

Grid Search CV:Did hyperparameter tuning on different models using Grid Search CV and still found SVM with highest accuracy

4.Making a predictive system: With the trained SVM Classifier made a predictive system using input data 

5.Deployment on localhost:After making the predictive system deployed the model on my localhost using streamlit.

![image](https://user-images.githubusercontent.com/66545820/205431792-73de30e5-0185-4d76-81a7-40348719fa96.png)


![image](https://user-images.githubusercontent.com/66545820/205431810-21837223-5861-4464-bcea-5ba79d5a98ea.png)

