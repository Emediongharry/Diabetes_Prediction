# Diabetes Prediction and Data Visualization

## Introduction 

In this project, we design a predictive model that predicts whether a patient will develop diabetes, based on certain diagnostic measures in the dataset, and explore different techniques to improve performance and accuracy. Logistic regression is the main algorithm used in this article and the analysis was performed using Python IDEs. The dataset was collected from the Pima Indians Diabetes Database and is available on Kaggle. It consists of several medical analyst variables and one target variable. 

The objective of the dataset is to predict whether the patient has diabetes. The dataset consists  of several  independent  variables   and  one  dependent  variable,  i.e.,  the  outcome. Independent variables include the number of pregnancies the patient  has  had their BMI, insulin level, age, and so on. The dataset consists of 768 rows and 9 columns. 


Below are the columns contained and their definitions:

**Pregnancies:** Number of times pregnant 

**Glucose:** Plasma glucose concentration over two hours oral glucose tolerance test

**BloodPressure:** Diastolic blood pressure (mm Hg)

**SkinThickness:** Triceps skinfold thickness (mm)

**Insulin:** 2-Hour serum insulin (mu U/ml)

**BMI:** Body mass index (weight in kg/(height in m)^2)

**DiabetesPedigreeFunction:** A function that calculates the probability of diabetes based on family history.

**Age:** Age in years

**Outcome:** Categorical variable (0 if not diabetic, 1 if diabetic). it is the target variable.


## Skills Demonstrated
1. Exploratory data analysis
2. Data cleaning
3. Data analysis and visualization
4. Machine Language
5. HTML
6. Data preprocessing


## Data Cleaning
The data-cleaning process began with:
1. Importing the required libraries which included pandas, numpy, seaborn, and matplotlib.
2. Checking for null values. I found out that there are no null values in the dataset.

After carefully confirming all quality issues, I concluded the data was clean and suitable for analysis.


## Analysis and Visualization
* I visualized a heatmap to show the relationship between the features of this dataset. Lighter colors represent higher correlation and darker colors represent
lower correlation.
+ T


## Data Pre-processing
This   phase   of   the model   handles   inconsistent   data   to   get   more accurate and precise results in this dataset ID is inconsistent so we dropped the feature. This dataset doesn’t contain missing values. So, we imputed missing values for a few selected attributes like Glucose level, Blood Pressure, Skin Thickness, BMI, and Age because these attributes cannot have values of zero. The data was then scaled using StandardScaler. Since there were a smaller number of features and important for prediction no feature selection was done.


## Scaling and Normalization: 
I performed feature scaling by normalizing the data from 0 to 1 range, which boosted the algorithm’s calculation speed. 

## Splitting of data and Training of model
After data cleaning and pre-processing, the dataset is now ready to train and test. In the train/split method, I split the dataset randomly into the training and testing set. For training, we took 80% of the sample and for testing, we took 20% of the sample.

A logistic regression algorithm is used to make predictions and check accuracy. A classification report is produced that includes precision, recall, F1 score, and support. The accuracy meter shows how many percent of predictions are correct. Recall describes what percentage of positives are correctly identified. The F1 score is the percentage of correct positive predictions. The support is the number of actual instances of the class-specified data set.

## Creating a User Interface for Accessibility
The final phase of the project involves developing a user interface for the model. This interface allows users to input new data, enabling the model to analyze it and provide predictions. The user interface is constructed utilizing the "Django" web framework, along with Hyper Text Markup Language (HTML) and Cascading Style Sheets (CSS).


## Results and Analysis:
The project predicts the likelihood of diabetes onset in an individual by analyzing pertinent medical information. Upon entering the necessary medical data on the online web portal, the information is transmitted to the trained model, which then assesses whether the individual is diabetic or non-diabetic. The model achieves a commendable accuracy of 79%, considering the limited dataset of only 768 rows, indicating its reliability and effectiveness.

Upon submitting this form, the model will provide the outcome in textual form. The result will indicate "Positive" for individuals exhibiting diabetic symptoms and "Negative" for those without diabetic symptoms.

## Conclusion
The objective of the project was to develop a model that  could identify patients with diabetes who are at high risk of hospital admission. Prediction of the risk of hospital admissions is a  fairly complex task. Many factors influence this process and  the outcome. There is presently a serious need for methods that can increase healthcare institutions' understanding of   what   is   important   in   predicting   hospital   admission   risk.   This   project   is   a   small contribution to the present existing methods of diabetes detection by proposing a system that can be used as an assistive tool in identifying the patients at greater risk of being diabetic. This project achieves this by analyzing many key factors like the patient’s blood glucose level,   body   mass   index,   etc.,   using   various   machine   learning   models   and   through retrospective analysis of patients’ medical records. The project predicts the onset of diabetes in   a   person   based   on   the   relevant   medical   details   that are   collected   using   a web application. When the user enters all the relevant medical data required in the online web application,  this  data  is  then   passed  on   to   the   trained   model   for   it   to   make  predictions about whether the person is diabetic or nondiabetic. The model is developed using an artificial neural network consisting of a total of six dense layers. Each of these layers is responsible for the efficient working of the model. The model predicts with an accuracy of 98%, which is fairly good and reliable
