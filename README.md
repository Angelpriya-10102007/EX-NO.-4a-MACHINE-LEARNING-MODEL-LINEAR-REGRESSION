# EX-NO.-4a-MACHINE-LEARNING-MODEL-LINEAR-REGRESSION
## AIM
To predict house prices using regression models and compare the performance of different machine learning regression models based on RMSE, MAE, and R².
1.Machine Learning:Machine Learning is used to learn patterns from existing data and make predictions. 
•	Regression is a supervised learning technique used to predict continuous numerical values. 
•	In this experiment, regression models are used to predict the price of a house. 
•	The dataset contains house-related features such as: 
o	square_feet 
o	num_rooms 
o	age 
o	distance_to_city(km) 
•	The target variable is: 
o	price 
## DATASET DESCRIPTION
•	Dataset: House Price Dataset 
•	Problem: Predict house price. 
•	Features (X): 
o	square_feet – size of the house. 
o	num_rooms – number of rooms. 
o	age – age of the house in years. 
o	distance_to_city(km) – distance from the city centre. 
•	Target (y): 
o	price – continuous house price. 
## PROBLEM STATEMENT
•	Develop a machine learning model to predict house prices. 
•	Use house characteristics as input. 
•	Train different regression models. 
•	Compare their prediction performance. 
•	Select the better-performing model based on evaluation metrics. 
## REGRESSION MODELS USED
The uploaded notebook compares the following models:
1.	Linear Regression 
2.	Ridge Regression 
3.	Lasso Regression 
4.	ElasticNet Regression 
5.	Polynomial Regression 
6.	Decision Tree Regressor 
7.	Random Forest Regressor 
8.	Gradient Boosting Regressor 
9.	Support Vector Regressor (SVR) 
10.	K-Nearest Neighbors (KNN) Regressor 
## PROCEDURE
    1.Import the required Python libraries for data processing, visualization, machine learning models, and model evaluation.
    2.Load the house price dataset from the specified CSV file using Pandas.
    3.Display the first five records of the dataset.
    4.Display the dataset information, shape, summary statistics, and check for missing values.
    5.Perform Exploratory Data Analysis (EDA) by studying the distribution of numerical features using histograms.
    6.Perform correlation analysis using a correlation heatmap to understand the relationship between the features and house price.
    7.Use scatter plots to study the relationship between individual features and house price.
    8.Detect outliers using boxplots.
    9.Remove extremely low and extremely high house prices using the 1st and 99th percentiles.
    10.Define the independent variables as square_feet, num_rooms, age, and distance_to_city(km), and define price as the target variable.
    11.Split the dataset into training and testing sets using an 80:20 ratio.
    12.Apply StandardScaler to scale the training and testing features.
    13.Create a baseline model that predicts the mean house price.
    14.Train different regression models including Linear Regression, Ridge, Lasso, ElasticNet, Polynomial Regression, Decision Tree, Random Forest,Gradient Boosting, SVR, and KNN.
    15.Evaluate all models using RMSE, MAE, and R² metrics.
    16.Compare the performance of the regression models based on their evaluation metrics.
    17.Plot actual versus predicted house prices.
    18.Perform residual analysis to study prediction errors.
    19.Calculate Random Forest and Gradient Boosting feature importance.
    20.Plot the RMSE comparison graph for all regression models.
## PROGRAM
<img width="747" height="707" alt="image" src="https://github.com/user-attachments/assets/099698b2-4419-4b1f-8dfa-95bca4f80b9f" />
<img width="330" height="736" alt="image" src="https://github.com/user-attachments/assets/5c8c9c98-a926-4bbc-ac64-d698c7ba7b5c" />
	


## CONCLUSION
Thus, Linear Regression and other regression models were successfully applied for house price prediction, and their performance was compared using standard regression evaluation metrics.

