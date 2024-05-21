# Lead-Scoring-case-study


### This a project on LEAD SCORING CASE STUDY

## Project Overview
X Education, an online course provider, seeks to improve its lead conversion rate, which currently stands at 30%. The goal is to develop a model that assigns a lead score to potential customers, indicating their likelihood of conversion. This will help the sales team focus on high-potential leads, aiming to achieve a target conversion rate of 80%.

## Problem Statement
X Education receives leads through various channels including website visits, referrals, and marketing campaigns. Despite acquiring numerous leads, the conversion rate is low. The company wants to identify 'Hot Leads'—those with a higher probability of converting into paying customers. Your task is to build a model that assigns lead scores, prioritizing leads with higher conversion chances.

## Dataset
The dataset contains approximately 9000 data points with attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable is 'Converted', where 1 indicates conversion and 0 indicates no conversion.

## Steps Followed

### 1. Reading Data
Load the dataset into a pandas DataFrame for analysis and model building.

### 2. Cleaning Data
Handle missing values, remove duplicates, and address 'Select' values in categorical variables, treating them as null values.

### 3. Exploratory Data Analysis (EDA)
Analyze data distributions, relationships between features, and identify key attributes influencing lead conversion.

### 4. Creating Dummy Variables
Convert categorical variables into numerical ones using dummy variables.

### 5. Splitting Data
Split the dataset into training and testing sets (70:30 ratio) to evaluate model performance.

### 6. Building Model
Develop a logistic regression model to assign lead scores based on provided attributes.

### 7. Making Predictions
Use the trained model to predict lead conversions on the test set.

### 8. Model Evaluation
Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

### 9. ROC Curve
Plot the ROC curve to visualize model performance and determine the optimal threshold for lead scoring.

### 10. Prediction on Test Set
Apply the model to the test set to predict lead conversions and compare with actual outcomes.

### 11. Precision-Recall
Analyze the precision-recall tradeoff to ensure the model maintains a high conversion rate while identifying hot leads.

## File Details
- Lead Score Case Study Aayushi Meenu.ipynb: Jupyter notebook containing code and data analysis.
- Assignment Subjective Questions.pdf: Document answering subjective questions related to the case study.
- Lead Score Case Study.pdf: Final presentation of the case study findings.
- Leads.csv: Dataset containing lead information.
- Leads Data Dictionary.xlsx: Data dictionary detailing dataset attributes.
- Summary.pdf: Summary of the processes and findings from the Jupyter notebook.

## Summary
The logistic regression model developed predicts the probability of lead conversion, with an optimal cut-off probability set at 0.3. The model achieves an accuracy of 84.55% on the test data, with a sensitivity of 85.88% and precision of 77%. This model will help X Education focus on high-potential leads, aiming to increase the overall lead conversion rate to 80%.

For more detailed analysis and results, refer to the Jupyter notebook and accompanying PDF documents.
 
