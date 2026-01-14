# Text Classification: SMS Spam Detection

## Overview
This project is a **text classification model** to detect **spam messages** in SMS data.  
The goal is to classify messages as **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** techniques and **Machine Learning**.

---

## Dataset
- The dataset used is [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) (`spam.csv`).
- Columns:
  - `v1` → label (`ham` or `spam`)
  - `v2` → message text
- Preprocessing steps:
  - Convert text to lowercase
  - Remove punctuation
  - Remove numbers

---

## Features
- **Text cleaning**: Lowercasing, removing punctuation and digits
- **Vectorization**: TF-IDF (`TfidfVectorizer`) with English stopwords
- **Machine Learning Model**: Logistic Regression
- **Evaluation**: Accuracy, Precision, Recall, F1-Score

---

## Model Performance
| Metric       | Score  |
|-------------|--------|
| Accuracy    | 95.5%  |
| Spam F1-score | 0.80 |
| Ham F1-score  | 0.97 |

**Sample Predictions:**

| Message                               | Prediction |
|---------------------------------------|------------|
| "Congratulations! You won a free ticket" | Spam       |
| "Hey, are we meeting today?"           | Ham        |
| "Urgent! Claim your prize now"         | Spam       |
| "Let's study together tomorrow"        | Ham        |

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Bhoomi916/Text-Classification.git
