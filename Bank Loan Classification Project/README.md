# Bank Loan Classification
## Table of Contents

- Background
- Findings
  - Feature correlations
  - Target class distribution
- Scoring Metric
- Business Value 

## Background

Having previously worked in a bank which specialized in loans, I was curious to know how loans could be better classified. I saw how bad loans had cost the bank a lot, so when I decided to go into data science, I knew that this would be my first project.
In this project I worked on a binary classification problem, where I built several models to determine the model that best classifies the target variable based on the available independent features.
- **Data Source**: Kaggle (https://www.kaggle.com/sriharipramod/bank-loan-classification)
- **Problem Statement**: To best classify the target varible - Personal loan, with much attention given to correctly classify the minority class

## Findings

### Feature correlations
![Feature correlation](https://user-images.githubusercontent.com/78446940/133309697-c9cb23ce-3cc8-4d40-b4aa-f83ee161138f.PNG)

### Target class distribution
![Feature correlation](https://user-images.githubusercontent.com/78446940/133309571-8251eae6-c7ab-47f3-aa61-dafd23f62a28.PNG)

## Scoring Metric

The scoring metrics I used for this project was chosen in order to pay more attention to the minority class, as a misclassification in the minority class would be more costly. The scoring metrics I used include:
- Recall
- F2 Score
- Matthew's Correlation Coefficient (MCC) Score
Paying more attention to the first two

## Business Value

Bank loans play a crucial role in the development of banks investment business. ML algorithms can help predict the customers who are at risk for defaulting on their loans to help companies rethink or adjust terms for each customer, thereby saving cost.