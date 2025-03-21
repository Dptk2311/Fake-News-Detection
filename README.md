# Fake-News-Detection
Fake News Classifier based using Bidirectional LSTM

# 📰 Fake News Detection using LSTMs  

This project classifies news articles as **real or fake** using **Natural Language Processing (NLP)** techniques and a **BiLSTM (Bidirectional Long Short-Term Memory) model**. It processes textual data using tokenization, word embeddings, and deep learning to distinguish between genuine and fake news.

---

## 🚀 Getting Started  

### 📌 Dependencies
- Python 3.x
- TensorFlow 2.x
- NumPy, Pandas, Matplotlib, Seaborn
- NLTK (Natural Language Toolkit)
- Google Colab (Recommended for running)

### 📊 Model Summary
The model follows the BiLSTM architecture:

Embedding Layer: Converts words into vector representations.
Bidirectional LSTM: Captures long-term dependencies in text.
Dense layers with ReLU activation: Extracts deep features.
Sigmoid activation: Outputs final classification (real or fake).

### **Model Architecture**
Input (maxlen=40) → Embedding (64 units) → Bidirectional LSTM (128 units)
→ Dense (128 units, ReLU) → Dense (1 unit, Sigmoid)

### 🏆 Results

✅ Achieved an accuracy of  99.86636971046771 % on test data.

✅ Works well on unseen news articles.

### Dataset Link
**Train.csv** : https://drive.google.com/file/d/1ol_trXynKdvk8ycGpxJG4XUBwrKW08FO/view?usp=drive_link

**Fake.csv**  : https://drive.google.com/file/d/1rc2KjOaV46VqJ1HBGJO_AZebP4ZDINqp/view?usp=drive_link

**Notebook Link(Colab)** : https://colab.research.google.com/drive/1eUqkqSRzjyB12FUgYQjaARSZljPLZdqL?usp=sharing

### Author: Diptak Chattopadhyay
