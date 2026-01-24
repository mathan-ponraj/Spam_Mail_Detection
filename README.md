# Spam Mail Detection using Logistic Regression

## Case Study

### Problem
Email spam causes security risks, productivity loss, and poor user experience. An automated system is needed to accurately classify emails as **spam** or **ham (not spam)**.

### Context
This project uses a real-world SMS/email dataset and applies **Natural Language Processing (NLP)** with **TF-IDF vectorization** and **Logistic Regression** to build a spam detection system.

### Impact
- Achieved **~95% accuracy on test data**
- Successfully classified unseen emails in real time
- Built a lightweight and interpretable NLP classification pipeline

### Why It Matters
Spam detection is critical for email providers, enterprises, and cybersecurity systems to filter malicious or unwanted messages efficiently.

---

## What I Did

- Built an end-to-end **text classification pipeline**
- Preprocessed raw email text data
- Converted text data into numerical features using **TF-IDF**
- Trained and evaluated a **Logistic Regression** classifier
- Deployed a prediction system for new email inputs

---

## How I Did It (STAR Method)

### Situation
The dataset contained raw text messages labeled as **spam** or **ham**, requiring text preprocessing and feature extraction.

### Task
Develop a machine learning model capable of accurately detecting spam emails from text content.

### Action
- Loaded and inspected the dataset using Pandas
- Handled missing values by replacing null entries with empty strings
- Encoded target labels (spam = 0, ham = 1)
- Analyzed class distribution
- Split the dataset into training and testing sets (80/20)
- Converted text data into numerical vectors using **TF-IDF Vectorizer**
- Trained a **Logistic Regression** model on training data
- Evaluated model performance using accuracy score
- Built a prediction system for classifying new email messages

### Result
- **Training Accuracy:** ~96.8%
- **Test Accuracy:** ~95.2%
- Model generalized well with minimal performance drop
- Successfully detected spam emails from unseen text input

---

## Tech Stack

- **Programming Language:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn
- **NLP Technique:** TF-IDF Vectorization
- **Model:** Logistic Regression
- **Evaluation Metric:** Accuracy Score
- **Environment:** Jupyter Notebook

---

## Key Results / Business Impact

- Delivered a high-accuracy spam detection system
- Demonstrated practical NLP application using classical ML
- Built an interpretable and efficient text classification model
- Created a strong baseline for advanced NLP models (Naive Bayes, SVM, Deep Learning)

---

## Example Prediction

```text
Input: "Congratulations! You have won a free car. Claim now!"
Output: Spam
```
