# Spam Mail Detection using Logistic Regression

## Project Overview
This project is a **learning-focused text classification task** where I built a simple spam detection model using **TF-IDF vectorization** and **Logistic Regression**.

The goal was to understand the **basic NLP workflow**, including text preprocessing, feature extraction, model training, and evaluation.

---

## Problem Statement
Given a dataset of text messages labeled as **spam** or **ham (not spam)**, the task is to build a machine learning model that can classify new messages correctly.

---

## What I Worked On

- Loaded and explored a real-world spam message dataset
- Cleaned and prepared text data for analysis
- Converted text into numerical features using **TF-IDF Vectorizer**
- Split the data into training and testing sets
- Trained a **Logistic Regression** classifier
- Evaluated model performance using accuracy

---

## Dataset Information
- Type: Text (SMS / Email messages)
- Target Classes: Spam, Ham
- Features: Text content converted using TF-IDF

---

## Model Performance
- **Training Accuracy:** ~97%
- **Test Accuracy:** ~95%

The model showed good performance on unseen data with no major drop between training and test accuracy.

---

## Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TF-IDF Vectorizer  
- Jupyter Notebook  

---

## Key Learnings
- Basics of text preprocessing for NLP tasks
- How TF-IDF converts text into numerical features
- Applying Logistic Regression to text classification
- Importance of train-test split in model evaluation
- Building a simple prediction workflow for new text inputs

---

## Future Improvements
- Experiment with Naive Bayes and SVM models
- Try additional evaluation metrics such as precision and recall
- Improve text preprocessing techniques
