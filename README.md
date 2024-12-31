# Customer Churn Prediction

## Overview

This repository contains a machine learning project to predict customer churn for a telecom company. Using historical customer data, we aim to predict which customers are at risk of leaving based on factors like tenure, monthly charges, and service type.

## Problem Statement

You are a data scientist working for a telecom company, and you need to identify customers who are likely to churn. This will help the company retain these customers and improve its business.

## Dataset

The dataset used in this project is the **Customer Churn** dataset. It contains the following columns:

- `customerID`: Unique identifier for the customer
- `tenure`: Number of months the customer has been with the company
- `MonthlyCharges`: The monthly bill for the customer
- `Churn`: Whether the customer has churned (Yes) or not (No)
- `InternetService`: Type of internet service the customer has (DSL, Fiber optic, No)

## Project Tasks

### 1. Data Manipulation

- Extract and filter data based on customer features (e.g., tenure, payment method).
- Perform data cleaning (handle missing values, remove duplicates, etc.).

### 2. Data Visualization

- Build bar plots, histograms, and scatter plots to explore the relationship between features like `MonthlyCharges`, `Tenure`, and `Churn`.
- Example visualizations include the distribution of Internet services, the relationship between tenure and monthly charges, and the churn rate for different services.

### 3. Machine Learning Models

- **Linear Regression**: Predict `MonthlyCharges` based on `Tenure`.
- **Logistic Regression**: Predict customer churn (`Churn` column) based on features like `MonthlyCharges`.
- **Decision Tree & Random Forest**: Predict churn using tree-based models and evaluate their performance.

## Technologies Used

- **Python** for data manipulation, analysis, and modeling.
- **Pandas** for data manipulation.
- **Matplotlib / Seaborn** for data visualization.
- **Scikit-learn** for building machine learning models.

## Getting Started

### Prerequisites

To run the project, you will need Python 3.x and the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/AvinashAnalytics/customer-churn-prediction.git
cd PYTHON-customer-churn-prediction
