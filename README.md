# Portuguese Bank Marketing – Machine Learning Project

## Project Overview
This project aims to predict whether a customer will subscribe to a term deposit based on bank marketing campaign data. The objective is to support data-driven customer targeting and improve marketing efficiency.

## Dataset
The dataset contains customer demographic details, campaign-related attributes, and macroeconomic indicators collected during direct marketing campaigns.

## Approach
- Exploratory Data Analysis (EDA) to understand customer behavior and campaign patterns
- Feature engineering and preprocessing, including handling class imbalance and preventing data leakage
- Model building using multiple classification algorithms
- Model evaluation using recall, precision, and F1-score
- Business-oriented interpretation of results

## Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (Linear)

## Evaluation Metrics
Due to class imbalance, model performance was evaluated using:
- Recall
- Precision
- F1-score  
Accuracy was not used as the primary metric.

## Final Model
Random Forest was selected as the final model due to its balanced performance, robustness, and suitability for bank marketing applications.

## Key Insights
- Previous campaign outcome is the strongest predictor of subscription
- Customers who subscribe typically do so within fewer contact attempts
- Targeted outreach improves conversion while reducing marketing costs

## Business Recommendations
- Focus on high-probability customer segments
- Reduce repeated contact attempts
- Use predictive modeling to guide campaign prioritization

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Author
Sreya
