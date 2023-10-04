# Data Scientist Salary Prediction
## Project Overview
• Created a machine learning model that estimates salary of data scientist based on the features like rating, company_founded, etc.<br/>
• This project helps data scientist/analyst to negotiate their income for an existing or a new job.

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn.**<br/>
• Dataset by **Ken Jee**: https://github.com/PlayingNumbers/ds_salary_proj

## Exploratory Data Analysis (EDA) and Data Cleaning
• Plotted bargraphs and countplots for numerical and categorical features respectively for EDA<br/>
• Numerical Features (Rating, Founded): Replaced NaN or -1 values with mean or meadian based on their distribution<br/>
• Categorical Features: Replaced NaN or -1 values with 'Other'/'Unknown' category<br/>
• Removed unwanted alphabet/special characters from Salary feature<br/>
• Converted the Salary column into one scale i.e from (per hour, per annum, employer provided salary) to (per annum)

## Feature Engineering
• Creating new features from existing features e.g. job_in_headquaters from (job_location, headquarters), etc.<br/>
• Trimming columns i.e. Trimming features having more than 10 categories to reduce the dimensionality<br/>
• Handling ordinal and nominal categorical features<br/>
• Feature Selection using **information gain (mutual_info_regression) and correlation matrix<br/>
• Feature Scaling using StandardScalar

## Model Building, Hyperparameter Tuning and Evaluation
• Metric: Negative Root Mean Squared Error (NRMSE)<br/>
• Using Linear Regression, Support Vector Machines, Random Forest, Gradient Boosting to create model.<br/>
• Hyper Parameter Tuning using Grid Search CV.
• Saving Model using Joblib.

