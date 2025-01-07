# Nasdaq-Analysis
Data Ingestion:

The process starts with a raw dataset file. In this case, it's TelcoCustomerChurn.csv that's downloaded from Kaggle.
The workflow will read this CSV file.
Data Preprocessing and Cleaning:

Handling Missing Values: The notebook identifies and replaces missing values in certain columns.
Dropping Unnecessary Columns: Columns deemed irrelevant for analysis are dropped.
Data Type Checks: The code includes data type inspection.
Exploratory Data Analysis (EDA):

Visualization: Histograms, box plots, count plots, and correlation matrices are used to explore the data.
Insights Generation: Observations are made about customer behavior, churn patterns, and correlations between features.
Feature Engineering:

Categorical Feature Encoding: Techniques like one-hot encoding, label encoding, and dummy variable creation are applied.
Numerical Feature Scaling: Standard scaling is used for numerical features.
Feature Selection: Chi-squared test is used to select the most relevant features.
Machine Learning Model Building:

Data Splitting: The dataset is split into training and testing sets.
Data Balancing: SMOTE (Synthetic Minority Over-sampling Technique) is used to address class imbalance.
Model Training: Logistic Regression and Decision Tree models are trained.
Model Evaluation: Confusion matrices, classification reports, and accuracy scores are used for evaluation.
Results Storage/Reporting:

The final model's performance metrics and potentially the processed dataset are saved as files for later review.
