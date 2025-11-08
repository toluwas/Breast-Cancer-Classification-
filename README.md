# Breast-Cancer-Classification-
ML Classification models for breast cancer diagnosis using Python and scikit-learn
Breast Cancer Data Preprocessing and Machine Learning Pipeline

PROJECT OVERVIEW
This project was developed as part of my M.Sc research, focusing on data preprocessing and machine learning techniques for breast cancer diagnosis.
The goal is to build a clean and reliable preprocessing pipeline that prepares raw breast cancer data for accurate classification and predictive modeling.

🎯 Objectives

Handle missing values and inconsistent data entries effectively.

Normalize and encode features for compatibility with machine learning algorithms.

Explore correlations among clinical and molecular features.

Prepare the dataset for training classification models (e.g., Logistic Regression, Random Forest, ANN, Decision tree, KNN, XGboost, Naive Bayes, SVM).

🧠 Dataset Information

The project uses breast cancer diagnostic data, which includes:

Patient demographics

Tumor characteristics

Biopsy/FNA (Fine Needle Aspiration) data

Molecular and genetic biomarker results

📍 Note: The dataset has been cleaned and anonymized for research purposes.

⚙️ Preprocessing Techniques Applied

Missing value imputation (mean, mode, or model-based methods)

Feature scaling using normalization and standardization

Label encoding and one-hot encoding for categorical data

Outlier detection using statistical thresholds

Train-Validation-test split for model evaluation readiness

K - Fold cross validation where K = 5 FOLDS

SMOTE (Synthetic Minority Oversampling Technigue) was introdued to oversampled the minority class label of the dataset to balance the dataset for training to avoid bias and overfitting

🧰 Technologies Used

Python 3.x

Jupyter Notebook

Pandas – data manipulation

NumPy – numerical computations

Scikit-learn – preprocessing and ML utilities

Matplotlib / Seaborn – data visualization
