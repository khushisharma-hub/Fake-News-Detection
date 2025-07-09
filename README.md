# 📰 Fake News Detection using Machine Learning

This project is part of the **Tamizhan Skills Rise Internship (Domain: Machine Learning & AI)** and focuses on detecting whether a given news article is **real** or **fake** using Natural Language Processing (NLP) and supervised learning techniques.

## 🎯 Objective

To build an intelligent system that can classify news articles into `real` or `fake` categories using **TF-IDF vectorization** and **Passive Aggressive Classifier** — a model suitable for large-scale binary classification tasks.

---

## 🧠 Technologies & Libraries Used

- **Python**
- **Google Colab**
- **scikit-learn**
- **NLTK** (stopwords)
- **TF-IDF Vectorizer**
- **Passive Aggressive Classifier**
- **Matplotlib** & **Seaborn**

---

## 📁 Project Files

| File | Description |
|------|-------------|
| [`Fake_News_Detection.ipynb`](https://github.com/khushisharma-hub/Fake-News-Detection/blob/main/Fake_News_Detection.ipynb) | Complete Colab notebook with step-by-step code and explanation |
| [`fake_news_data.csv`](https://github.com/khushisharma-hub/Fake-News-Detection/blob/main/fake_news_data.csv) | Dataset used to train and test the fake news classifier |

---

## 📝 Features of the Project

- Upload and preprocess real-world text data
- Clean news text (removing punctuation, stopwords, lowercase conversion)
- Convert text to numerical vectors using TF-IDF
- Train a Passive Aggressive Classifier
- Evaluate model using **accuracy**, **confusion matrix**, and **F1-score**
- Test on custom input news to predict whether it's real or fake

---

## 📊 Model Performance

- **Classifier Used:** Passive Aggressive Classifier  
- **Test Accuracy:** ~92%  
- **Evaluation Metrics:** Accuracy Score, Confusion Matrix, F1 Score

---

## 💡 Example Usage

```python
predict_news("Breaking: Government announces major reforms in the education sector.")
