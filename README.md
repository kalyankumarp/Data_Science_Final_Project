# CS 418 Data Science Final Project
Regression and Classification with HyperParameter Optimization (Grid Search, Random Search, and Bayesian Optimization)

For more details, check the Report

• The objective of the project is to predict the unemployment rates of counties in 2017 using linear regression and to classify them into three categories: highest, moderate and lowest, based on the unemployment rates of 2015.
• Performed Data Preparation using Pandas to find missing values and correlated attributes using scatterplots. 
• Explored the data using the Matplotlib and the Seaborn libraries to find the important attributes for regression and classification. Split the dataset into training (80%) and test (20%) datasets using the holdout method with the sklearn library.
• Used the statsmodels library to build a best regression model with an adjusted R2 value of 0.839, RMSE of 2.2, and MAE of 1
• Obtained the best classifier using Naïve Bayes from the sklearn library with F1 Scores of 0.76, 0.87 and 0.74 
