# Fake-News-Detection-Project
# 📰 Fake News Detection using NLP & Machine Learning

This project uses Natural Language Processing (NLP) and machine learning techniques to classify news articles as **Fake** or **Real**. The goal is to help users and organizations quickly identify misinformation in digital media.

## 📌 Project Overview

- **Objective**: Classify news articles as fake or real.
- **Dataset**: Labeled dataset sourced from Kaggle.
- **Tech Stack**:
  - Python
  - Pandas, NumPy
  - NLTK (Natural Language Toolkit)
  - Scikit-learn (Sklearn)
  - Streamlit (for web interface)

---

## 🧠 Approach

### 1. Data Preprocessing
- Remove punctuation, numbers, and special characters
- Convert text to lowercase
- Remove stopwords
- Apply tokenization and stemming

### 2. Feature Extraction
- TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text into numerical features

### 3. Model Training
- Trained using:
  - **Logistic Regression**
  - **Multinomial Naive Bayes**
- Evaluation Metrics:
  - Accuracy
  - F1-score
  - Precision
  - Recall

###PROJECT STRUCTURE
├── fake_news_detector.py # Model training and prediction code
├── utils.py              # Text preprocessing functions
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
└── data/
    └── fake_or_real.csv  # Input dataset




### Clone the repository
```bash
git clone https://github.com/yuvashnee/fake-news-detection.git
cd fake-news-detection
