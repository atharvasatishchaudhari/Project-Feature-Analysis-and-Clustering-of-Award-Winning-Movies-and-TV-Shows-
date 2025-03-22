# Project-Feature-Analysis-and-Clustering-of-Award-Winning-Movies-and-TV-Shows

# IS525 Final Project - Award Prediction and Analysis

This project analyzes the key factors that contribute to the success of movies and TV shows in winning prestigious awards (Oscars and Emmys) and provides actionable insights for industry stakeholders.

## Aim

- **Objective:**  
  Predict the likelihood of movies winning Oscars and analyze trends in Emmy-winning TV shows.

- **Focus Areas:**  
  - Identify key determinants of success such as critic scores, audience scores, genres, and release year.  
  - Address challenges like class imbalance and misclassification errors.  
  - Provide actionable insights to guide content production and marketing strategies.

## Process

- **Data Acquisition & Preparation:**  
  - Collected datasets from sources like Rotten Tomatoes and Oscar award records.  
  - Merged and cleaned data using Tableau Prep Builder with operations including left outer joins and feature engineering (e.g., creating a unique identifier for movies).

- **Exploratory Data Analysis (EDA):**  
  - Performed detailed EDA to uncover genre trends, score correlations, and temporal patterns.  
  - Developed interactive visualizations in Tableau and PowerBI to highlight insights and anomalies.

- **Model Development & Evaluation:**  
  - Initiated model development with a Random Forest Classifier, then transitioned to XGBoost to reduce false negatives and better handle class imbalance.  
  - Evaluated performance using metrics such as AUC-ROC scores, confusion matrices, and classification reports.  
  - Enhanced model interpretability with SHAP values, providing stakeholders with insights into feature importance.

- **Visualization & Reporting:**  
  - Created interactive dashboards to compare model predictions with actual outcomes, and to analyze award category trends over time.  
  - Documented the full project lifecycle, including methodology, challenges, client feedback, and iterative improvements.

## Results

- **Predictive Insights:**  
  - The refined XGBoost model delivered competitive accuracy with a significant reduction in false negatives.  
  - Key predictors such as critic and audience scores, genre, and release year were identified as critical for predicting Oscar wins.

- **Key Findings:**  
  - Certain genres, particularly Drama, exhibit a higher likelihood of award success.  
  - A strong correlation exists between high critic scores and winning outcomes.  
  - Interactive visualizations enabled granular insights into trends across award categories and over time.
 
  ![image](https://github.com/user-attachments/assets/0257ef87-9fa9-4ac9-864d-9a5df79bbc6c)
  ![image](https://github.com/user-attachments/assets/9c8f6098-ea8e-4c16-98ce-8c48c970e838)
  ![image](https://github.com/user-attachments/assets/943c11f4-4c2f-4d02-b2cd-760ef4f02e7a)
  ![image](https://github.com/user-attachments/assets/15b8c08a-07ce-43cb-a23b-69e9d7687d86)
  ![image](https://github.com/user-attachments/assets/4e462562-ae47-4a5f-a1b1-11290a7fdf65)





