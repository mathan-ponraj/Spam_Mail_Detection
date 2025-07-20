# Spam Mail Detection

## Project Overview
This project implements a spam mail detection system using Logistic Regression for binary classification of emails. The model identifies whether an email is spam or not. The primary focus is on text preprocessing techniques such as tokenization, stopword removal, and lemmatization. The features are extracted from the email content using TF-IDF vectorization, and the Logistic Regression model is used to classify the emails.

## Features
- **Preprocessing:** Tokenization, stopword removal, and lemmatization of email content.
- **Vectorization:** Text vectorization using TF-IDF.
- **Classification:** Logistic Regression for spam classification.
- **Evaluation:** Model evaluation using accuracy-score.

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `nltk`, `matplotlib`, `seaborn`

### Installation

1. Clone this repository:
    ```
    git clone https://github.com/yourusername/spam-mail-detection.git
    cd spam-mail-detection
    ```

2. Install the required libraries:
    ```
    pip install -r requirements.txt
    ```

### Usage
To train the model and evaluate its performance, run the following command in your terminal:
```
python train_and_evaluate.py
```
---
## Results
The model achieved an accuracy of 95% respectively. These metrics demonstrate the model's ability to accurately detect spam emails.

## Contributing
Feel free to fork the repository and submit pull requests with improvements or new features!
