# Detecting-Credit-Card-Fraud-Using-Machine-Learning

# Overview
This project aims to detect fraudulent and non fraudulent transactions in credit card data using machine learning algorithms. The model's performance is evaluated using precision, recall, and F1-score metrics to assess its effectiveness in identifying fraudulent activities.
# DataSet
/ https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud / 

#Classification Metrics
The classification metrics for the model are as follows:

# Class	Precision	Recall	
F1-Score
Not Fraud	0.88	1.00	0.94
Fraud	1.00	0.86	0.92
Accuracy			0.93
Macro Avg	0.94	0.93	0.93
Weighted Avg	0.94	0.93	0.93
Precision: Precision measures the accuracy of positive predictions. In this context, it represents the proportion of correctly identified fraud cases among all transactions flagged as fraud.
Recall: Recall measures the ability of the model to correctly identify all positive instances (fraudulent transactions). It indicates the proportion of actual fraud cases that were correctly identified by the model.
F1-Score: The F1-score is the harmonic mean of precision and recall. It provides a balance between precision and recall, offering a single metric to evaluate the model's performance.
Accuracy: Accuracy represents the overall correctness of the model's predictions.
Macro Avg: Macro average calculates the unweighted mean of precision, recall, and F1-score across all classes. It gives equal weight to each class.
Weighted Avg: Weighted average calculates the average of precision, recall, and F1-score weighted by the number of true instances for each class. It considers class imbalance.
Conclusion
The model demonstrates strong performance in detecting fraudulent transactions, with high precision and recall scores. However, further analysis may be required to address any specific business requirements or constraints.

Feel free to customize this README according to your project's specifics and any additional information you'd like to include!






