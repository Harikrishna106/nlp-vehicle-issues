

# 🚗 Vehicle Issue Classification using NLP

This beginner-friendly NLP project classifies customer complaints into categories like **engine problems**, **electrical faults**, and more. It uses a real-world dataset and covers the full NLP pipeline — ideal for practicing data cleaning, text processing, sentiment analysis, and classification.

## 📁 Dataset

> A sample dataset of customer vehicle complaints including text description and issue category.  
## 🔍 Objective

- Clean and preprocess text data
- Perform sentiment analysis
- Use Named Entity Recognition (NER)
- Build and evaluate a classification model (Logistic Regression)

## 📚 Steps Covered

### 1. Data Preprocessing
- Remove special characters, punctuation
- Convert to lowercase
- Tokenize
- Remove stopwords
- Lemmatization

### 2. Sentiment Analysis
- Using `TextBlob` to detect positive/negative tone in complaints

### 3. Named Entity Recognition (NER)
- Using `spaCy` to extract vehicle parts, brands, etc.

### 4. Feature Engineering
- Vectorization using TF-IDF

### 5. Model Building
- Classification using **Logistic Regression**
- Train-test split

### 6. Evaluation
- Accuracy, precision, recall, F1-score
- Classification report from `sklearn`

## 📦 Libraries Used

- `pandas`, `numpy`, `re`, `string`
- `nltk`, `spaCy`, `TextBlob`
- `scikit-learn`

## 🚀 How to Run
# Install required libraries
pip install pandas numpy nltk spacy textblob scikit-learn

# Download NLTK data
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

# Run the notebook
jupyter notebook nlp.ipynb
