# Text Classification of Mental Health Discussions on Alodokter

This folder focuses on the automatic classification of mental health discussions from the **Alodokter** forum into predefined categories using **Natural Language Processing (NLP)** and **machine learning** techniques. The classification task aims to distinguish discussions related to **Depression, Anxiety, and Stress**.

---

## 📁 Folder Structure

### 1. Klasifikasi - Modeling
This folder contains all modeling experiments for text classification.

It consists of two main subfolders:

- **Eksperimen dengan Algoritma-NB_KNN_RF_NN**  
  Classification experiments using:
  - Naive Bayes (NB)
  - K-Nearest Neighbors (KNN)
  - Random Forest (RF)
  - Neural Network (NN)

- **Eksperimen dengan Algoritma lain (SVM, DT, GB)**  
  Classification experiments using:
  - Support Vector Machine (SVM)
  - Decision Tree (DT)
  - Gradient Boosting (GB)

Each experiment includes feature extraction, model training, and evaluation.

---

### 2. Result
This folder stores the final outputs of the classification process, including:

- Model performance summaries
- Evaluation results for each algorithm
- Comparison of classification metrics across models

---

### 3. Snippet
This folder contains visual documentation such as screenshots of code execution, outputs, and experiment results for reference and validation.

---

### 4. Dataset File

- **datamodel_klasifikasi_clean.csv**  
  A cleaned and labeled dataset used as the main input for all text classification experiments.

---

## 🔍 Classification Overview

### Target Classes
The discussions are classified into the following mental health categories:
- Depression
- Anxiety
- Stress

---

### Feature Extraction Techniques
Several text representation methods are explored:
- Bag of Words (BoW)
- N-gram and Bigram
- GloVe Embeddings

---

### Machine Learning Models
The following algorithms are implemented and compared:
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)
- Neural Network
- Gradient Boosting

---

## 📊 Model Evaluation
Model performance is evaluated using:
- Train–test split
- Cross-validation
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Support

---

## ⚙️ Workflow Pipeline

1. **Data Preparation**  
   Load and preprocess `datamodel_klasifikasi_clean.csv`.

2. **Feature Extraction**  
   Transform text data using BoW, N-gram/Bigram, or GloVe embeddings.

3. **Model Training**  
   Train classification models using different algorithms.

4. **Evaluation & Comparison**  
   Evaluate model performance and compare results across algorithms, with outputs stored in the *Result* folder.
