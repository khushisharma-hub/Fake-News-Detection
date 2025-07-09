# 📰 Fake News Detection using Machine Learning

This project is part of the **Tamizhan Skills Rise Internship (Domain: Machine Learning & AI)**. It uses Natural Language Processing (NLP) techniques and machine learning models to detect whether a news article is **real** or **fake**.

---

## 🎯 Objective

To build an AI-powered classifier that distinguishes between fake and real news using TF-IDF text vectorization and a Passive Aggressive Classifier. This solution supports digital awareness initiatives by automating fake news detection.

---

## 🧠 Technologies & Tools Used

- Python (Google Colab)
- pandas, numpy
- scikit-learn
- nltk
- matplotlib, seaborn

---

## 📁 Files in the Repository

| File | Description |
|------|-------------|
| [`Fake_News_Detection.ipynb`](https://github.com/khushisharma-hub/Fake-News-Detection/blob/main/Fake_News_Detection.ipynb) | Jupyter Notebook with full implementation |
| [`fake_news_data.csv`](https://github.com/khushisharma-hub/Fake-News-Detection/blob/main/fake_news_data.csv) | Dataset with 200 sample news entries (100 real, 100 fake) |

---

## 📊 Model Summary

- **Model Used:** Passive Aggressive Classifier
- **Vectorizer:** TF-IDF
- **Accuracy Achieved:** ~92%
- **Evaluation Metrics:** Accuracy, Confusion Matrix, F1-Score

---

## 🧪 Features

- Text preprocessing: lowercase, punctuation removal, stopword filtering
- TF-IDF feature extraction
- Passive Aggressive classifier training
- Model evaluation using classification report and confusion matrix
- Real-time prediction on custom input

---

## 💻 Sample Prediction

```python
predict_news("Breaking: WHO approves new vaccine for pandemic response.")
Output:
🧠 The news is predicted to be: real

📽️ Demo Video
🎥 Click to Watch Demo Video

🙋‍♀️ Developed By
Khushi Sharma
Intern ID: TS-RISE-MLAI-2514
Internship Program: Tamizhan Skills Rise – Machine Learning & AI

🔗 GitHub Repository
👉 https://github.com/khushisharma-hub/Fake-News-Detection
