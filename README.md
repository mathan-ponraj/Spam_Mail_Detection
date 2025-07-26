# Spam Mail Detection using Logistic Regression

This project implements a Spam Mail Detection system using Logistic Regression for binary classification. The model determines whether an email is spam or not, focusing on essential text preprocessing techniques and TF-IDF vectorization.

---

## Project Overview

The primary objective of this project is to classify emails as spam or non-spam based on their content. The workflow involves text preprocessing (tokenisation, stopword removal, lemmatisation), transforming the processed text into numerical vectors using TF-IDF, and applying Logistic Regression for classification.

---

## Features

- **Preprocessing**  
  Tokenisation, stopword removal, and lemmatisation of email text data to clean and standardise input.

- **Vectorization**  
  Utilised TF-IDF vectorisation to convert text into feature vectors suitable for model training.

- **Classification**  
  Implemented a Logistic Regression model for binary classification of emails.

- **Evaluation**  
  Model performance was evaluated using accuracy score to assess its effectiveness.

---

## Technologies Used
- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Results
The model achieved an accuracy of **95%**, demonstrating its effectiveness in detecting spam emails through text analysis and classification techniques.

---

## Conclusion
This project showcases the use of Logistic Regression combined with NLP preprocessing and TF-IDF vectorisation to build a simple yet effective spam detection model. It serves as a baseline for exploring more advanced models in email classification tasks.
