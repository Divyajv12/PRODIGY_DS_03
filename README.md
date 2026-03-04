# PRODIGY_DS_03
Internship task 3
# Decision Tree Classifier for Customer Purchase Prediction

## Project Overview

This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on demographic and behavioral data. The analysis is performed using the Bank Marketing dataset from the UCI Machine Learning Repository. The goal of the project is to analyze customer attributes and develop a machine learning model that can help organizations identify potential customers who are more likely to subscribe to their services.

## Dataset

The dataset used in this project is the Bank Marketing Dataset, which contains information related to direct marketing campaigns conducted by a banking institution. The dataset includes demographic information such as age, job, and education, along with campaign-related features such as contact duration, number of contacts, and previous campaign outcomes. The target variable indicates whether the customer subscribed to a term deposit.

## Objectives

The main objectives of this project are:

* To perform data preprocessing and exploratory data analysis (EDA).
* To build a Decision Tree Classifier model to predict customer subscription.
* To evaluate the performance of the model using classification metrics.
* To visualize the decision tree and interpret its decision rules.

## Tools and Technologies

The following tools and technologies were used in this project:

* Python
* Google Colab / Jupyter Notebook
* Pandas for data manipulation
* NumPy for numerical computations
* Matplotlib for visualization
* Scikit-learn for machine learning model development

## Methodology

### 1. Data Loading

The dataset was loaded into the environment using the Pandas library. Initial inspection was performed to understand the structure, number of features, and presence of categorical variables.

### 2. Data Preprocessing

Since the dataset contains categorical variables, label encoding was applied to convert them into numerical values so that they could be used by the machine learning model.

### 3. Exploratory Data Analysis

Basic analysis was conducted to understand the distribution of variables and the relationship between different customer attributes and the target variable.

### 4. Train-Test Split

The dataset was divided into training and testing sets using an 80:20 ratio. The training data was used to train the model, while the testing data was used to evaluate its performance.

### 5. Model Building

A Decision Tree Classifier was implemented using the Scikit-learn library. The model learns decision rules from the data to classify whether a customer is likely to subscribe to the service.

### 6. Model Evaluation

The model performance was evaluated using metrics such as:

* Accuracy Score
* Confusion Matrix
* Classification Report

These metrics help determine how well the model predicts customer subscription.

### 7. Decision Tree Visualization

The trained decision tree was visualized using the plot_tree function. This visualization helps in understanding the decision rules used by the model to classify customers.

## Results and Insights

The model successfully identifies patterns in customer behavior that influence subscription decisions. Features such as contact duration, previous campaign results, and demographic attributes significantly impact the prediction outcome. The decision tree structure helps interpret how different factors influence customer decisions.

## Conclusion

This project demonstrates how machine learning can be applied to marketing data to predict customer behavior. By using a Decision Tree Classifier, organizations can gain valuable insights into customer patterns and design more effective marketing strategies.

## Future Improvements

Possible improvements for this project include:

* Using advanced models such as Random Forest or Gradient Boosting.
* Performing feature selection to improve model accuracy.
* Applying cross-validation for better model generalization.


