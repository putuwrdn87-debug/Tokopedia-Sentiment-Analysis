# Tokopedia-Sentiment-Analysis
Sentiment Analysis of Tokopedia Product Reviews using TF-IDF, SMOTE, Logistic Regression and Random Forest

# Tokopedia Sentiment Analysis
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-green)
![SMOTE](https://img.shields.io/badge/SMOTE-Imbalanced%20Data-red)

## Project Overview

This project aims to classify customer reviews from Tokopedia into positive and negative sentiments using Natural Language Processing (NLP) and Machine Learning techniques.

The project applies text preprocessing, TF-IDF feature extraction, SMOTE for handling imbalanced data, and compares the performance of Logistic Regression and Random Forest classifiers.

---

## Dataset

Dataset: Tokopedia Product Reviews 2019

The dataset contains customer reviews and product ratings from various product categories on Tokopedia.

Sentiment labels are created as follows:

| Rating | Sentiment |
|----------|----------|
| 1 - 2 | Negative |
| 3 | Removed (Neutral) |
| 4 - 5 | Positive |

---

## Methodology

### Data Preprocessing

- Lowercase Conversion
- Text Cleaning
- Tokenization
- Stopword Removal

### Feature Extraction

- TF-IDF Vectorization
- Maximum Features: 5000

### Data Balancing

- SMOTE (Synthetic Minority Oversampling Technique)

### Classification Models

1. Logistic Regression
2. Random Forest

---

## Workflow

Dataset
→ Text Preprocessing
→ TF-IDF
→ SMOTE
→ Model Training
→ Evaluation

---

## Results

| Model | Accuracy | Macro F1-Score |
|----------|----------|----------|
| Logistic Regression | 89.24% | 60.12% |
| Random Forest | 96.15% | 66.72% |

### Best Model

Random Forest achieved the best performance with:

- Accuracy: 96.15%
- Macro F1-Score: 66.72%

---

## Visualizations

### Positive Sentiment Word Cloud

![Positive Word Cloud](images/wordcloud_positive.png)

### Negative Sentiment Word Cloud

![Negative Word Cloud](images/wordcloud_negative.png)

### SMOTE Distribution

![SMOTE Distribution](images/Distibusi_Sentimen_Sebelum_vs_Setelah_SMOTE.png)

### Confusion Matrix

![Confusion Matrix](images/Confusion_Matrix_RF_vs_LR.png)

---

## Technologies Used

- Python
- Pandas
- NLTK
- Scikit-Learn
- Imbalanced-Learn
- Matplotlib
- Seaborn
- WordCloud

---

## Skills Demonstrated

- Natural Language Processing (NLP)
- Text Mining
- Data Preprocessing
- Feature Engineering
- Machine Learning
- Imbalanced Data Handling
- Data Visualization
- Model Evaluation

---

## Author

Putu Wardani
