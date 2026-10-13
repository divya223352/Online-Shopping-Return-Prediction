# Online-Shopping-Return-Prediction
# Online Shopping Return Prediction & Customer Behavior Analysis

## 📌 Project Overview

The **Online Shopping Return Prediction & Customer Behavior Analysis** project uses Machine Learning to analyze online retail transactions and identify patterns related to product returns and cancellations.

The project explores customer transaction behavior, analyzes return/cancellation rates across countries, visualizes monthly transaction trends, and compares machine learning models to understand how well they classify transactions as return/cancellation or normal.

## 🎯 Objectives

- Analyze online retail transaction data.
- Clean and preprocess the dataset.
- Study customer purchasing and transaction patterns.
- Analyze return/cancellation rates by country.
- Visualize monthly transaction trends.
- Build and compare Logistic Regression and Decision Tree classification models.
- Evaluate models using Accuracy, Precision, Recall, F1 Score, ROC-AUC, and confusion matrices.
- Identify important features influencing model classification.

## 🛠️ Tools and Technologies Used

- **Python:** Main programming language for data analysis and machine learning.
- **Google Colab:** Cloud-based environment for writing and executing Python code.
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical operations.
- **Matplotlib:** Data visualization.
- **Seaborn:** Statistical visualization.
- **Scikit-learn:** Data preprocessing, model training, and evaluation.
- **UCI Machine Learning Repository:** Source of the Online Retail dataset.

## 📊 Dataset

**Dataset Name:** Online Retail

**Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains online retail transactions from December 2010 to December 2011. It includes information such as invoice numbers, product stock codes, quantities, invoice dates, unit prices, customer IDs, and countries.

## ⚙️ Project Workflow

1. **Data Collection:** Download the Online Retail dataset using the `ucimlrepo` library.
2. **Data Preprocessing:** Clean transaction data, convert data types, and handle missing values.
3. **Return/Cancellation Identification:** Use invoice numbers beginning with `C` and negative quantities as indicators of returns or cancellations.
4. **Exploratory Data Analysis:** Examine transaction volumes, country-wise patterns, and monthly trends.
5. **Feature Engineering:** Create invoice-level features, including product counts, quantities, prices, transaction values, month, day of the week, and hour.
6. **Model Training:** Train Logistic Regression and Decision Tree classifiers.
7. **Model Evaluation:** Compare model performance using classification metrics and confusion matrices.
8. **Feature Importance:** Analyze the features used by the Decision Tree classifier.
9. **Result Export:** Save analysis tables and model comparison results as CSV files.

## 🤖 Machine Learning Algorithms

### 1. Logistic Regression

A classification algorithm used as a baseline model for distinguishing return/cancellation transactions from other transactions.

### 2. Decision Tree Classifier

A tree-based classification algorithm used to identify patterns in transaction features and estimate which features are most useful for classification.

## 📈 Outputs

The project generates the following outputs:

- Dataset preview and data-cleaning summary.
- Country-wise transaction analysis.
- Return/cancellation rate analysis.
- Monthly transaction trend graph.
- Model performance comparison table.
- Confusion matrices for both classifiers.
- Decision Tree feature-importance table and graph.
- `invoice_analysis.csv`
- `country_analysis.csv`
- `model_comparison.csv`
- `feature_importance.csv`

## 📏 Evaluation Metrics

- **Accuracy:** Overall proportion of correctly classified transactions.
- **Precision:** Proportion of predicted return/cancellation transactions that are correctly classified.
- **Recall:** Proportion of actual return/cancellation transactions correctly identified.
- **F1 Score:** Harmonic mean of precision and recall.
- **ROC-AUC:** Measures how well the model distinguishes between the two classes.

Actual metric values should be taken from the executed notebook results.

## ⚠️ Project Limitation

The dataset does not directly link an original purchase to a subsequent return. Therefore, this project uses cancellation invoice indicators and negative quantities as a proxy for return/cancellation classification.

The results should be interpreted as analysis and classification of observed transactions, not as a validated prediction of future returns for new purchases.

## 🏁 Conclusion

This project demonstrates how Python, exploratory data analysis, data visualization, and machine learning can be applied to online retail transaction data. By comparing Logistic Regression and Decision Tree models, the project evaluates different approaches to classifying return/cancellation transactions and identifies useful transaction patterns.

The analysis can help demonstrate the role of data-driven methods in understanding online retail behavior, while recognizing the limitations of the available dataset.

## 👩‍💻 Author

**Divya**

GitHub: https://github.com/divya223352

LinkedIn: https://www.linkedin.com/in/divya-sri-3a544a331/

## 📄 License and Dataset Attribution

Dataset: Online Retail, UCI Machine Learning Repository.

Chen, D. (2015). *Online Retail* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33

The dataset is provided under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. Refer to the dataset source for its terms of use.
