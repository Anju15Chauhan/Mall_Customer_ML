# Mall Customer Analytics Using Machine Learning
![images (20)](https://github.com/user-attachments/assets/a9ccde96-8667-4282-a4fc-7ca92dc9d4a1)


# Overview
![images (21)](https://github.com/user-attachments/assets/3b63fa30-1616-4c5b-82e0-5dc0697913a0)

This project focuses on analyzing customer data to understand customer behavior and provide insights for targeted marketing. We use machine learning techniques like classification, clustering, and regression to extract meaningful insights from a mall customer dataset.

# Dataset
The dataset contains information about mall customers, including demographic details and spending behavior. The features are:

* **CustomerID:** Unique identifier for each customer.
* **Gender:** Gender of the customer (Male/Female).
* **Age:** Age of the customer.
* **Annual Income (k$):** Annual income of the customer in thousand dollars.
* **Spending Score (1-100):** Score assigned to the customer based on their spending behavior.

# Objectives
**1. Customer Segmentation:** Group customers based on spending patterns and income using K-Means Clustering.
**2. Spending Score Prediction:** Predict customer spending scores based on demographic data using Linear Regression.
**3. Customer Classification:** Classify customers as high, medium, or low spenders using Random Forest Classifier.

# Project Structure
- **data/:** Contains the dataset (Mall_Customers.csv).
- **customer_segmentation.py:** Script for performing customer segmentation using K-Means Clustering.
- **spending_score_regression.py:** Script for predicting spending score using Linear Regression.
- **classification.py:** Script for classifying customers into spending categories (Low, Medium, High).

# 1. Customer Segmentation
Customer segmentation is done using **K-Means Clustering.** Customers are grouped into clusters based on their age, annual income, and spending score.

# Steps:
- **Preprocess the Data:** Scale the features using StandardScaler.
- **Elbow Method:** Determine the optimal number of clusters.
- **K-Means Clustering:** Fit the model and visualize the clusters.

# 2. Spending Score Prediction
The spending score is predicted using Linear Regression. The model uses the customer's age, gender, and annual income to predict their spending score.

# Steps:
- **Feature Selection:** Select features such as age, gender, and income.
- **Train-Test Split:** Split the data into training and testing sets.
- **Model Training:** Train a linear regression model.
- **Evaluation:** Evaluate the model using metrics like Mean Squared Error and R-squared.

# 3.Customer Classification
Customers are classified into Low, Medium, or High spenders based on their spending score using a Random Forest Classifier.

# Steps:
- **Categorize Spending:** Convert the spending score into categorical labels (Low, Medium, High).
- **Train-Test Split:** Split the data into training and testing sets.
- **Model Training:** Train a Random Forest Classifier.
- **Evaluation:** Evaluate the model using accuracy and a classification report.

# Results
![download (8)](https://github.com/user-attachments/assets/ef71c1c6-9f4f-4479-a418-b882ef80d57d)

The results of each model, including accuracy scores, confusion matrices, and evaluation reports, can be viewed in the respective script output.

