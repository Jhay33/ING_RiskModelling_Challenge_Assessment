# ING_RiskModelling_Challenge_Assessment
# Credit Risk Modeling for Credit Default Prediction - ING Bank Interview

As part of an interview challenge for ING Bank, I developed and implemented two machine learning models to predict the probability of credit default for retail customers applying for term loans. The project involved building a logistic regression model and a challenger model using Python, both designed to replace an underperforming predictive tool for estimating default risk.

## Key Features of the Project:
### Task 1: Logistic Regression Model Development
##### Data Analysis & Preprocessing:

Analyzed two datasets: development data for model training and testing data for evaluation.
Performed descriptive statistical analysis, managed missing values, and examined the target default rate.
Conducted feature engineering by creating new predictive variables and handling raw attributes.
##### Model Selection & Feature Engineering:

Selected features using correlation analysis and expert domain knowledge to identify the most relevant predictors for default risk.
Applied transformations and scaling where necessary to meet model assumptions.
##### Model Building & Interpretation:

Built a logistic regression model to estimate the probability of default.
Provided business interpretation of the coefficients to understand the impact of variables like income, loan amount, and credit score on the default probability.
Ensured the logistic regression assumptions (e.g., linearity in the logit, absence of multicollinearity) were checked and fulfilled.

##### Performance Metrics:
Evaluated the model's performance using accuracy, precision, recall, F1 score, and ROC-AUC.
Presented and explained the ROC curves to assess the model’s discriminatory power on both training and testing data.

### Task 2: Challenger Model Development
##### Alternative Model Selection:
Developed a Random Forest Classifier as the challenger model, leveraging its ability to capture non-linear relationships between variables and handle imbalanced data more effectively than logistic regression.

##### Model Comparison:
Compared the results of the Random Forest model with the logistic regression in terms of performance metrics (accuracy, precision, recall, F1 score, AUC) on both training and testing datasets.
Highlighted key advantages of the Random Forest model, such as its ability to manage outliers and provide feature importance scores for better insight into the most influential variables.

##### Challenges & Implementation Considerations:
Discussed challenges associated with both models, including interpretability of the Random Forest model vs. the simplicity of logistic regression, and the potential for overfitting in more complex models.
Addressed issues such as scalability, computation time, and the importance of balancing interpretability and performance when implementing models in a real-world banking environment.

##### This project exemplifies my expertise in predictive modeling, data preprocessing, feature engineering, and model evaluation. It also highlights my ability to critically assess model performance, balance complexity with interpretability, and present actionable insights for decision-making in credit risk management.
