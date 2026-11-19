# Stroke Prediction AI Using Machine Learning

## 1. Project Overview
This project focuses on developing an Artificial Intelligence (AI) solution using machine learning to classify patients into stroke and non-stroke categories. The project uses Python and the Logistic Regression algorithm to analyse patient information and identify patterns associated with stroke cases.

## 2. Project Objectives
- Review and clean the dataset.
- Identify and handle missing values.
- Prepare the dataset for machine learning.
- Develop a Logistic Regression classification model.
- Test and evaluate the AI solution.
- Refine the model to improve its performance.

## 3. Dataset Description
The project uses the Stroke Prediction Dataset, which contains patient information, including:
- Gender
- Age
- Hypertension
- Heart disease
- Average glucose level
- Body mass index (BMI)
- Smoking status
- Stroke history

The target variable is `stroke`:
- 0 = No stroke
- 1 = Stroke

## 4. Tools and Technologies
The following tools and libraries were used:
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 5. Data Cleaning and Preparation
The dataset was prepared using the following activities:
- Checking and removing duplicate records.
- Identifying missing values.
- Replacing missing BMI values using median imputation.
- Removing the unnecessary ID column.
- Encoding categorical variables into numerical values.
- Scaling numerical features.
- Examining class imbalance.

## 6. Machine Learning Model
Logistic Regression was selected because this project involves binary classification.

The dataset was divided into training and testing sets. The training data was used to train the model, while the testing data was used to evaluate its performance.

Class weighting was also applied to help address the imbalance between stroke and non-stroke cases.

## 7. Model Evaluation
The model was evaluated using the following performance measures:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These evaluation methods helped assess how effectively the model classified stroke and non-stroke cases.

## 8. Project Files
- `Stroke_Prediction.ipynb` – Contains the Python code, data preparation, model development, charts and evaluation results.
- `README.md` – Provides information about the project.
- `requirements.txt` – Lists the Python libraries required to run the project.

## 9. Conclusion
This project demonstrates how machine learning can be applied to healthcare data to classify stroke and non-stroke cases. It also highlights the importance of data cleaning, preparation, model training, testing and evaluation when developing an AI solution.

## 10. Disclaimer
This project is for educational purposes only. The model is not intended to replace professional medical advice or diagnosis.
