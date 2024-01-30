# Financial Insights and Fraud Detection

## Project Overview

This project focuses on aiding customers in financial planning through regression analysis to predict their upcoming monthly spending. Additionally, it addresses fraud detection in financial transactions using classification techniques. The project aims to provide valuable insights to customers, enhance financial planning, and contribute to fraud prevention.

## Business Understanding

### Section 1: Aiding customers in financial planning by predicting their upcoming monthly spending (regression)

One of the critical business problems is to assist customers in better understanding and managing their finances. Regression analysis techniques are employed to predict customers' total spending amounts for the upcoming months. This predictive capability empowers customers to make informed decisions, enabling effective budgeting and financial planning.

### Section 2: Compliance Team in fraud detection by predicting the fraudulent nature of transactions (classification)

In the context of fraud detection, the objective is to reduce fraudulent transactions. The project translates this problem into a binary classification task, identifying and flagging potentially fraudulent transactions. The goal is to develop a model or system that can accurately identify and flag potentially fraudulent transactions, enabling proactive measures to prevent financial losses.

### Section 3: Aiding the Marketing Team in sending personalized marketing emails to customer groups exhibiting similar spending patterns (clustering)

This case involves an exploratory analysis to identify customer groups with similar demographic or purchasing characteristics. The project aims to uncover patterns that can help the marketing team send personalized marketing emails to specific customer groups, improving the targeting of financial products.

### Section 4: Assisting Customer Support in contacting customers with abnormal spending patterns (anomaly detection)

The objective here is to improve customer support services by proactively identifying and reaching out to customers with abnormal spending patterns. The result of this study can be used for enhanced customer support and fraud prevention.

## Data Preparation

The dataset undergoes specific steps to prepare for predicting the next month's spending, including conversion of Unix Time, age calculations, filtering out fraudulent transactions, grouping and aggregating data, and inclusion of customer demographics.

## Modeling

In regression analysis, seven models are developed and evaluated, including Baseline, Multivariate Regression, Lasso Regression, Ridge Regression, ElasticNet Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor. Standard scaling, one-hot encoding, and frequency encoding are applied to features. The best-performing model after hyperparameter tuning is the Gradient Boosting Regressor.

In classification analysis for fraud detection, six models are developed and evaluated, including Logistic Regression, Decision Tree, LightGBM with default parameters, LightGBM with data balancing, LightGBM using SMOTE, and XGBoost. The XGBoost model is selected as the final model due to its high F1 score and recall.

For clustering, K-Means, Mean Shift, and Hierarchical dendrogram analysis are performed to identify customer groups for targeted marketing.

Anomaly detection is conducted using Isolation Forest, Local Outlier Factor (LOF), and DBSCAN techniques.

## Evaluation

Model performance is evaluated using metrics such as mean absolute error (MAE), mean squared error (MSE), root mean square error (RMSE) for regression, and accuracy, recall, precision, and F1 score for classification. The best-performing models are selected based on these metrics.

## Contributing

Contributions are welcome! Feel free to report bugs, suggest features, or submit pull requests to improve the project.

