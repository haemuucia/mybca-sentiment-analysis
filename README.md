# 📊 MyBCA App Sentiment Analysis

This project focuses on performing **sentiment analysis** on user reviews of the MyBCA mobile application from the Google Play Store. The goal is to understand user feedback, identify common issues, and extract insights that can help improve the application.

---

## 🚀 Project Overview

User reviews are a valuable source of feedback for mobile applications. In this project, I:

* Scrape user reviews from the Google Play Store
* Clean and preprocess text data
* Perform sentiment analysis using Natural Language Processing (NLP)
* Classify reviews into sentiment categories (positive, negative, neutral)
* Analyze trends and patterns in user feedback

---

## 📁 Project Structure

```
├── mybca_reviews.csv
├── scraping.ipynb
├── sentiment_analysis.ipynb
├── requirements.txt     
└── README.md
```

---

## 🧠 Methodology

### 1. Data Collection

* Reviews are scraped from the Google Play Store using automation tools.

### 2. Data Preprocessing

* Lowercasing text
* Removing punctuation, numbers, and stopwords
* Tokenization
* Normalization (slang handling too!)

### 3. Sentiment Labeling

* Sentiment is categorized into:

  * **Positive**
  * **Negative**
  * **Neutral**

### 4. Modeling

* NLP techniques used include:

  * TF-IDF Vectorization
  * Machine Learning models (e.g., Logistic Regression, Naive Bayes)
  * Deep Learning / fine-tuned models

### 5. Evaluation

* Model performance evaluated using:

  * Accuracy

---

## 📊 Example Output

| Review                         | Sentiment |
| ------------------------------ | --------- |
| "Aplikasinya sangat membantu!" | Positive  |
| "Sering error dan lambat"      | Negative  |

---

## ⚙️ Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/mybca-sentiment-analysis.git
cd mybca-sentiment-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run Jupyter Notebook

```bash
jupyter notebook
```

* Open:

  * `scraping.ipynb` → for scraping data
  * `sentiment_analysis.ipynb` → for analysis & modeling

---

## 🛠️ Tech Stack

* Python
* Pandas & NumPy
* Scikit-learn
* NLTK / Sastrawi (for Indonesian NLP)
* Jupyter Notebook

