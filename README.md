# NovaShop: Predicting Late Deliveries

## Project Overview

This project explores how machine learning can help an online retailer identify orders at risk of late delivery.

Using a synthetic order-level dataset, I developed a supervised classification workflow to estimate late-delivery risk and support operational prioritization.

## Business Problem

Late deliveries can reduce customer satisfaction and increase operational costs. Reviewing every order manually is expensive.

The objective is to predict whether an order will arrive later than promised, using information available when the order is accepted.

## Objectives

* Audit data quality and remove duplicate orders.
* Handle missing numerical and categorical values.
* Prepare features using a preprocessing pipeline.
* Train a logistic regression classifier.
* Evaluate the model using a chronological train/test split.
* Compare the model against a majority-class baseline.
* Demonstrate target leakage and explain why it makes a model unsuitable for deployment.
* Translate predicted probabilities into a review-prioritization strategy.

## Tools and Technologies

* Python
* Pandas and NumPy
* Scikit-learn
* Jupyter Notebook / Google Colab
* GitHub

## Methodology

1. Data loading and quality checks.
2. Duplicate removal and missing-value handling.
3. Chronological 80/20 training and testing split.
4. Numerical scaling and categorical one-hot encoding.
5. Logistic regression model training.
6. Evaluation using accuracy, precision, recall, and a confusion matrix.
7. Target leakage experiment using post-delivery information.
8. Operational recommendations based on predicted risk.

## Key Learning Outcomes

This project demonstrates the importance of data quality, leakage prevention, realistic model evaluation, and connecting machine learning outputs to business decisions.

## Limitations

The dataset is synthetic and educational. The results do not establish how well the model would perform in a real retail company. Further validation using real historical orders would be required before deployment.

## Project Files

* `NovaShop_Analysis.ipynb`: notebook containing the analysis and machine learning workflow.
* `FI510E_Session4_NovaShop_Orders.csv`: source dataset, if redistribution is permitted.

## Author

Business Analytics & Data Science student
