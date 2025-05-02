# Fake-News-Prediction

# 📰 Fake News Prediction using Machine Learning

## 📌 Overview

This project aims to detect and classify **fake news** using natural language processing (NLP) and machine learning techniques. It helps users verify the authenticity of news articles based on their textual content.

---

## 📁 Dataset

The dataset used is sourced from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) and consists of:

- **train.csv**: Contains the training data with the following columns:
  - `title`: The title of the news article
  - `text`: The full text of the article
  - `label`: 0 for **real** news, 1 for **fake** news

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **NLTK**
- **TfidfVectorizer**
- **Logistic Regression** / Naive Bayes / Random Forest
- **Jupyter Notebook**

---

## 🚀 Features

- Preprocessing of textual data
- Tokenization and vectorization using TF-IDF
- Model training using supervised learning algorithms
- Evaluation using accuracy, precision, recall, and confusion matrix
- Prediction of new input headlines/articles

---

## 🔍 How It Works

1. **Data Cleaning**:
   - Remove nulls, punctuation, and stopwords
   - Apply lowercase formatting

2. **Feature Engineering**:
   - Convert text to numerical vectors using TF-IDF

3. **Modeling**:
   - Train models like Logistic Regression and compare their performance

4. **Evaluation**:
   - Use metrics like accuracy, confusion matrix, and classification report

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/fake-news-prediction.git
   cd fake-news-prediction

2. Install dependencies:

   pip install -r requirements.txt

3. Run the notebook:

   jupyter notebook FND.ipynb

## 📊 Results

- Achieved high accuracy in detecting fake news

- Confusion matrix and precision/recall scores indicate robust performance

## 📈 Future Work

- Deploy the model as a web application using Flask/Streamlit

- Enhance the dataset with real-time news feeds

- Experiment with deep learning models like LSTM or BERT

## 📄 License

- This project is licensed under the MIT License 



