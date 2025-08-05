# Presonalised-Medicine-using-ML
# Personalized Medicine using Machine Learning

## 📌 Project Overview
This project applies **Machine Learning** to enable **Personalized Medicine**, with a focus on predicting optimal treatments based on patient-specific data. The approach uses the **Max Voting ensemble technique** to combine predictions from multiple classifiers and make a robust final decision. This helps enhance the accuracy and reliability of medical predictions, such as disease subtype classification or drug response.

## 🧠 Objective
To build a machine learning pipeline that:
- Analyzes patient data (e.g., genomic, phenotypic, or clinical)
- Predicts the most suitable treatment or disease classification
- Uses **Max Voting** to improve prediction performance across multiple models

## 🛠️ Tech Stack
- **Python** 🐍
- **Pandas**, **NumPy** – Data preprocessing
- **Scikit-learn** – ML models & evaluation
- **Matplotlib**, **Seaborn** – Visualization
- **Jupyter Notebook** – Development environment

## 🧬 Machine Learning Models Used
The following base models were used:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

The predictions from the above models were combined using the **Max Voting Ensemble Strategy**, which selects the class label predicted by the majority of models.

## 🔁 Max Voting Algorithm
**Max Voting** is an ensemble technique where:
- Multiple base classifiers are trained
- Each model votes on the final output
- The class receiving the highest number of votes is selected

This method is particularly useful for reducing model variance and increasing generalizability.

## 📊 Evaluation Metrics
- Accuracy
- Confusion Matrix
- ROC Curve (for binary classification)
