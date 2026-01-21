# 📘 Modeling of Mental Health Discussions on Alodokter

This repository contains a text mining project focused on analyzing mental health discussions from the **Alodokter** online forum. The study emphasizes three major mental health topics: **Depression, Anxiety, and Stress**, using both **topic modeling** and **text classification** approaches.

---

## 🎯 Project Objectives
- Explore discussion patterns related to mental health issues.
- Identify dominant themes within forum conversations.
- Build and evaluate text classification models to automatically categorize discussions into **depression, anxiety, and stress**.
- Compare multiple feature extraction techniques and machine learning algorithms.

---

## 📂 Repository Structure
```
Modeling-of-Mental-Health-Discussions-on-Alodokter/
│
├── Topic Modeling/
│   ├── Data scraping and preprocessing
│   ├── Topic modeling using LDA
│   ├── Visualization (WordCloud, pyLDAvis)
│   └── README.md
│
├── Text Classification/
│   ├── Feature extraction (BoW, N-gram, Bigram, GloVe)
│   ├── Machine learning models and evaluation
│   └── README.md
│
└── README.md
```

---

## 🔍 Project 1: Topic Modeling
The **Topic Modeling** folder focuses on uncovering latent themes in mental health discussions.

General workflow:
- Forum data scraping using **Scrapy**
- Text preprocessing (cleaning, tokenization, stopword removal)
- Topic extraction using **Latent Dirichlet Allocation (LDA)**
- Identification of dominant topics such as:
  - Depression
  - Anxiety
  - Stress
- Visualization of results using:
  - **WordCloud**
  - **pyLDAvis**

📌 Detailed methodology and results are available in `Topic Modeling/README.md`.

---

## 🧠 Project 2: Text Classification
The **Text Classification** folder focuses on automatically classifying forum discussions into mental health categories.

General workflow:
- Text classification into:
  - Depression
  - Anxiety
  - Stress
- Feature extraction techniques:
  - Bag of Words (BoW)
  - N-gram and Bigram
  - GloVe Embeddings
- Machine learning models applied:
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Decision Tree
  - Support Vector Machine (SVM)
  - Neural Network
  - Gradient Boosting
- Model evaluation using:
  - Train–test split
  - Cross-validation
  - Confusion Matrix
  - Precision, Recall, F1-Score, and Support

📌 Detailed experiments and evaluation results are documented in `Text Classification/README.md`.

---

## 🛠️ Tools & Technologies
- Python
- Scrapy
- scikit-learn
- Gensim
- NLTK / spaCy
- pyLDAvis
- WordCloud
- Pandas & NumPy
- Matplotlib / Seaborn

---

## 📌 Disclaimer
This repository is intended for **academic and exploratory purposes only**.  
The analysis results are **not meant to serve as medical diagnosis or professional mental health advice**.
