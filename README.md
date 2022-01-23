# Medical-Premium-Insurance-Prediction
## <b>Problem Statement</b>
A medical Insurance company has released date for almost 1000 customers. A model needs to be created which can predict the yearly medical cover costs for the insurance. 

## <b>Dataset Description </b>

The dataset is available on Kaggle and the data has been voluntarily given by the customers. The file name is “MedicalPremium.csv”. There are 11 attributes in the dataset, they are:

1.	Age
2.	Diabetes
3.	BloodPressureProblems
4.	AnyTransplants
5.	AnyChronicDiseases
6.	Height
7.	Weight
8.	KnownAllergies
9.	HistoryOfCancerInFamily
10.	NumberOfMajorSurgeries
11.	PremiumPrice

## <b>Analysis after EDA and Pre-processing</b>
After plotting the histogram, It was observed that Premium Price variable is not evenly distributed.

So, Premium Price variable has been divided into 5 different labels as it was not properly distributed.

The division of the label is done as follows
1. Low
2. Basic
3. Average
4. High
5. SuperHigh

## <b>Models Used</b>
### <b>1.	Linear Regression: </b>

It is used to find a Linear Relationship between the target variable and the explanatory variables.

### <b>2.	LASSO Regression (Least Absolute Shrinkage and Selection Operator): </b>

It is a type of Linear Regression which uses Shrinkage. Shrinkage is basically where data values are shrunk towards a central point.

It performs both Regularization and Variable Selection.

It helps in reducing model complexity and prevent overfitting which is found in simple Linear Regression.

### <b>3.	XGBRF Regression (Random Forest with XGBoost):</b>

Random Forest is an ensemble of decision tree algorithms.
XGBoost helps in efficient implementation of the gradient boosting ensemble algorithm.


### <b>4.	Random Forest Regression:</b>

A Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging.

## <b>Accuracy Parameters Used:</b>
### <b>1. Accuracy Score: </b>
Accuracy is the most intuitive performance measure and it is simply the ratio of correctly predicted observations to the total observations. 

It is a great measure, but only for symmetric datasets (where Fales Positives = False Negatives). 

### <b>2. R - Squared: </b>
The coefficient of discrimination, denoted R2 is a commonly used performance metric for regression. 

It provides a measure of the proportion of the variance of a dependent variable that is explained by a regression model and defined by 

### <b>3. Mean Absolute Error: </b>
The Mean Absolute Error(MAE) is the average of all absolute errors. 
