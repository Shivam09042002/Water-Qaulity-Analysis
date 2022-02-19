# Water-Qaulity-Analysis
Project Title: Water Quality Analysis
Name: Shivam Vilas Gaikwad
College: K. K. Wagh Institute Of Engineering Education And Research.
Branch: Computer Engineering (Majors in Data Science)
Year of completion: 2023
Team Members: 
1)	Shivam Gaikwad (Team - Leader)
2)	Sumat Jain
3)	Dev Panjwani
Aim: The aim of this project is to predict the potability using classification machine learning model.
Explanation: This project has been divided into various steps.
a)	The first basic step of any machine learning models is to import the basic libraries that are required. Which include pandas, numpy, matplotlib and seaborn.
 

b)	The second step is importing the dataset which will contain the values from which the machine will learn and take the decision.
 
c)	Exploratory Data Analysis: Finding if the dataset contains any null values
 
Filling the missing values with the mean value of that respective columns so that there are not any errors while machine learns from the model.
 
Getting the information and no of columns in the dataset.
 
Calculating the statistical values of each column in the dataset.
 
d)	Visualizing the count of potability column using countplot of seaborn library.
 
e)	Splitting the dataset into dependent and independent variable.
 
f)	Now splitting the dataset into training and testing using model selector from sklearn library.
 
g)	Applying feature scaling to the model to bring the values in the range on 0 to 1. So that there is no big difference in the values in various columns. 
 
h)	Training the Kernel Support vector Machine Learning model on the training dataset using rbf kernel and random state as 0.
 
i)	Now calculating the accuracy of the model and making the confusion matrix. 
 
j)	Now the model is ready to predict the new values.
 
The support vector machine learning model have been developed to predict the potability of water with an 67% accuracy. 

