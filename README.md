# 📧 Email Classification using NLP

## 📌 Overview
This project builds a machine learning model to classify emails into **Spam** and **Ham (Not Spam)** using Natural Language Processing (NLP) techniques. It demonstrates the full pipeline from raw text processing to model prediction.

---

## 🚀 Features
- Text preprocessing and cleaning
- Feature extraction using TF-IDF / Bag of Words
- Training a classification model (Naive Bayes)
- Model evaluation with standard metrics
- Predicting new/unseen emails

---

## 🧠 Workflow

### 1. Data Preprocessing
- Convert text to lowercase  
- Remove punctuation  
- Remove stopwords  
- Tokenization  

### 2. Feature Engineering
- Convert text into numerical vectors using:
  - Bag of Words (BoW)
  - TF-IDF Vectorization  

### 3. Model Training
- Train a classifier:
  - Multinomial Naive Bayes  

### 4. Evaluation
- Accuracy  
- Precision  
- Recall  
- F1 Score  

### 5. Prediction
Final pipeline:
Input Email → Preprocessing → Vectorization → Model → Output (Spam / Ham)

---

## 📂 Project Structure
Email-classification-NLP/

├── main.ipynb          # Main notebook  
├── dataset/            # Dataset files  
├── models/             # Saved models (if any)  
├── requirements.txt    # Dependencies  
└── README.md  

---

## ⚙️ Installation

### Clone the repository
git clone https://github.com/OmarEssam-20/Email-classification-NLP.git  
cd Email-classification-NLP  

### Install dependencies
pip install -r requirements.txt  

---

## ▶️ Usage
- Open `main.ipynb`
- Run all cells step by step
- Modify input text to test predictions

---

## 📊 Results
- Naive Bayes performs well for spam detection
- TF-IDF improves accuracy compared to raw text

---

## 🛠️ Technologies
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- NLTK  

---

## 🔮 Future Improvements
- Deep Learning models (LSTM, Transformers)
- Web deployment (Streamlit / Flask)
- Real-time email filtering API

---

## 👤 Author
**Omar Essam**  
GitHub: https://github.com/OmarEssam-20
