# Customer-Churn-Prediction-Using-Perceptron-and-Logistic-Regression
Overview
This project aims to classify customers of a telecommunications company based on their likelihood to churn. The classification is achieved through the implementation of a Perceptron algorithm and Logistic Regression using customer features like tenure, monthly charge, and age.

Dataset
The dataset comprises 3,757 customers from a telecommunications company in California for Q2 2022. It contains the following features:

Tenure in Months: The number of months the customer has stayed with the company.
Monthly Charge: The monthly charge for the customer.
Age: The age of the customer.
Customer Status: A binary label indicating whether the customer has churned (1) or stayed (0).
Sample Data
Tenure in Months	Monthly Charge	Age	Customer Status

9	65.6	37	0

9	-4.0	46	0

4	73.9	50	1

...	...	...	...
Prerequisites
To run the project, ensure you have the following libraries installed:

pandas
numpy
matplotlib
scikit-learn
You can install these packages using pip:

pip install pandas numpy matplotlib scikit-learn
Setup
Download the dataset CSV file and save it in a directory named data within your project folder.
Update the IDnumber variable in the script with your identification number.
Usage
Run the Python script to execute the following tasks:

Data Loading: Loads the dataset and preprocesses it by shuffling, splitting into training and test sets, and standardizing the input features.
Perceptron Implementation:
The script implements both a non-randomized and randomized version of the Perceptron algorithm for classification.
Training and test errors are computed after training for a specified number of iterations.
The loss is plotted against the number of iterations to observe the training error reduction.
Logistic Regression:
Implements a logistic regression model to compare performance against the Perceptron model.
Error rates for both training and test datasets are calculated and displayed.
Results
After running the script, you will see:

Training and test error rates for the Perceptron algorithm after 30 and 3000 iterations.
Training and test error rates for the Logistic Regression model.
A plot illustrating the training error reduction with an increasing number of iterations for the Perceptron.
