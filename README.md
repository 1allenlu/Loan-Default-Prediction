Project Title

Loan Default Prediction using Supervised Learning Models

Project Description

This project was completed for CS-UY 4563 (Machine Learning) at NYU.
The goal of the project was to predict whether a borrower would default on a loan, based on their financial, demographic, and credit-related features.

We used the Credit Risk Dataset, which contains variables such as applicant income, loan amount, employment length, home ownership status, and more.

⸻

Methods and Models Used
	•	Data Preprocessing:
	•	Handled missing values using median imputation.
	•	Applied one-hot encoding to categorical variables.
	•	Standardized numerical features with StandardScaler.
	•	Unsupervised Analysis:
	•	Conducted PCA for dimensionality reduction and variance analysis.
	•	Visualized feature distributions.
	•	Built a correlation matrix to detect feature relationships.
	•	Supervised Learning Models:
	•	Logistic Regression (with original, polynomial, and interaction-only transformations)
	•	Support Vector Machines (SVM) (tested linear and RBF kernels)
	•	Neural Networks (MLPClassifier) (tested various architectures, activation functions, and regularization settings)

⸻

Key Results
	•	The Neural Network with logistic activation and two hidden layers (128 and 64 neurons) achieved the highest accuracy (92.05%) and highest F1 Score (79.54%).
	•	Logistic Regression with polynomial features (degree 2) also performed strongly with over 90% accuracy.
	•	SVM models achieved reasonable accuracy but did not outperform logistic regression or neural networks.
	•	Feature transformations and regularization were critical in improving model generalization.

⸻

How to Run
	•	Run main.ipynb or model_training.py (whichever you submit) to see data preprocessing, unsupervised analysis, model training, and evaluation.
	•	Requirements:
	•	Python 3.8+
	•	scikit-learn
	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn

⸻

Future Improvements
	•	Train on a larger dataset (e.g., 100,000+ samples) to improve model generalization.
	•	Incorporate macroeconomic indicators (e.g., unemployment rate, GDP growth, interest rates) as additional features to capture broader economic effects on loan default risk.

⸻
