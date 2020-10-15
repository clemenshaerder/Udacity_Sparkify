# Udacity_Sparkify
Capstone Project of Udacity Data Science Nano Degree

Predicting churn rates is a challenging and common problem that data scientists and analysts regularly encounter in any customer-facing business. Additionally, the ability to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.
This is what we are trying to achieve in this project for the music streaming service Sparkify. Sparkify is a fictitious company, created by Udacity, which resembles real-world music streaming services like Spotify. And there are so many more?
So what if we could figure out what the key factors are that make people stay in our streaming service Sparkify?

## Steps
- Load & Clean JSON DATA
- EDA
- Feature Engineering
- Pre-Processing
- Modelling
- Evaluation

## Installation
- Python 3.6
- PySpark ML
- Jupyter

## Results

The best performing model is Logistic Regression with elastic net regularization with a test F1-score of 0.75,
outperforming Linear SVM, Classification Tree and Random Forest, while having a reasonable time to fit.

The most influencial predictors are the average number of downvotes and upvotes per song.
Hence, if an increase of downvotes is observed, it might be reasonable to increase customer management activities to keep them in the service.
