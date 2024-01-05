# Diabetes_Prediction

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
I visualized a heatmap to show the relationship between the features of this dataset. Lighter colors represent higher correlation and darker colors represent
lower correlation. 


## Data Pre-processing
This   phase   of   the model   handles   inconsistent   data   to   get   more accurate and precise results in this dataset ID is inconsistent so we dropped the feature. This dataset doesn’t contain missing values. So, we imputed missing values for a few selected attributes like Glucose level, Blood Pressure, Skin Thickness, BMI, and Age because these attributes cannot have values of zero. The data was then scaled using StandardScaler. Since there were a smaller number of features and important for prediction no feature selection was done.


## Scaling and Normalization: 
I performed feature scaling by normalizing the data from 0 to 1 range, which boosted the algorithm’s calculation speed. 

## Splitting of data: 
After data cleaning and pre-processing, the dataset is now ready to train and test. In the train/split method, I split the dataset randomly into the training and testing set. For training, we took 80% of the sample and for testing, we took 20% of the sample.


