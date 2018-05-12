# Titanic-survival-rate-Data-Wrangling-Visualization-and-Feature-Engineering

I would like to use one of the Kaggle's competition, to go through the step by step workflow of solving a problem with machine learning techiniques. I studied the code from Manav Sehgal and would like to document my learnings and findings. 

Project Description


In this project, I would like to analysis what kind of people were likely to survive in Titanic with data visualization. In particular, to apply the tools of machine learning to predict which passengers survived the tragedy.


Steps taken:

1) Get the training and testing data sets

2) Meet and Greet the data :
 
   - Identify the data types: numerical, ordinal, categorical, mixed types
   - Identify missing data columns, possible data errors , empty columns etc
   - get a feel on the basic statistics information of the data columns. 

3) Data Analysis using pivoting features 

   -  analysis the data by pivoting some features
   -  make some initial assumptions based on the findings: e.g. gender, age, Pclass has strong correlations with survival rate 

4) Data Analysis using visualization 

  - further confirm and test some assumptions based on visualization 
  - use Seaborn, Matplotlib to visualize the correlation between features 
 -  Decisions made in regards to how to further engineer the features

5) Feature engineering

 - Dropped features
-  new feature created based on existing ones
-  features converted into categorical features

6) Prediction

 -Using the following ML models to predict the survival rate and chose Random Forest model due to the highest confidence score. 
 
 Random Forest	86.64
	Decision Tree	86.64
	KNN	84.06
	Support Vector Machine	83.50
	Logistic Regression	81.26
	Linear SVC	79.46
	Perceptorn	78.79
	Naive Bayes	76.88
	Stochastic Gradient Decent	

  

