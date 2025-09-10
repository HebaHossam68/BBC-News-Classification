# 📰 BBC News Text Classification

This project implements **Text Classification** on the BBC News dataset using multiple AI models, starting from traditional ML to Deep Learning and Transformers.

---

## 📌 Dataset
- **BBC News Dataset (CSV)**  
  Each row contains:
  - `Category` → The label (business, politics, sport, tech, entertainment).
  - `Text` → The news article content.

---

## 🛠️ Preprocessing
1. Lowercasing text.  
2. Removing punctuation, numbers, and stopwords.  
3. Tokenization and Lemmatization.  
4. Splitting into train/test sets.  

---

## 🤖 Models Implemented
1. **Baseline (ML Models)**  
   - TF-IDF + Logistic Regression / Naive Bayes / SVM.  

2. **Deep Learning (DL Models)**  
   - LSTM with word embeddings.  

3. **Transformers (State-of-the-art)**  
   - BERT / DistilBERT fine-tuned on the dataset.  

---
# Author
# Heba Hossam
## 🚀 How to Run

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
