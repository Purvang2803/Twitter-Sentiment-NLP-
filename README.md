# Twitter Sentiment Analysis

## 📌 Overview
This project performs **sentiment analysis** on Twitter data using **Natural Language Processing (NLP)** techniques. The goal is to classify tweets as **Positive, Negative, or Neutral** by applying various **preprocessing, feature extraction, and machine learning models**.

## 🚀 Features
- **Data Preprocessing:** Cleaning and normalizing text by removing URLs, special characters, and stopwords.
- **Emoji Processing:** Replacing positive and negative emojis with text labels.
- **Lemmatization:** Reducing words to their base form.
- **Stopword Removal:** Eliminating common words that do not add meaning.
- **Feature Extraction:** Using **TF-IDF, Word2Vec, and FastText embeddings**.
- **Sentiment Classification:** Applying **Naïve Bayes, Logistic Regression, and VADER sentiment analysis**.
- **Visualization:** Generating **word clouds, pie charts, and TF-IDF score tables**.

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have **Python 3.x** installed, then install the required libraries:
```bash
pip install pandas numpy nltk sklearn matplotlib wordcloud gensim vaderSentiment
```

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis
```

### 3️⃣ Download NLTK Resources
```python
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('vader_lexicon')
```

### 4️⃣ Run the Notebook
Open the **Jupyter Notebook** and execute the cells in sequence to perform sentiment analysis.

## 📊 Steps in the Analysis

### 🔹 Data Preprocessing
- **Cleaning Tweets**: Removing links, special characters, digits, and unnecessary spaces.
- **Handling Emojis**: Mapping emoticons like 🙂 to 'positiveemoji' and ☹️ to 'negativeemoji'.
- **Lemmatization**: Converting words to their base forms for consistency.

### 🔹 Feature Extraction
- **TF-IDF**: Converts text into numerical values based on word importance.
- **Word2Vec & FastText**: Generates word embeddings for better context understanding.

### 🔹 Sentiment Classification
- **VADER Sentiment Analysis**: Computes sentiment scores for each tweet.
- **Naïve Bayes Classifier**: Uses word frequencies to predict sentiment.
- **Logistic Regression**: Implements a classification model based on cleaned text.

### 🔹 Evaluation & Visualization
- **Confusion Matrix**: Shows model performance.
- **Word Cloud**: Highlights frequently occurring words in tweets.
- **Pie Chart**: Displays distribution of sentiments in the dataset.

## 📌 Results
- Achieved an accuracy of **X%** using **Logistic Regression**.
- Word embeddings helped in understanding tweet context better.
- VADER performed well on informal and short texts.

