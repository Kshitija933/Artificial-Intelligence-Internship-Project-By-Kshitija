# # 📩 Spam Email Classifier – Step-by-Step Guide

## 📁 Dataset Used
- File: `spam.csv` (SMS Spam Collection Dataset)
- Source: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

## 🧪 Objective
Train a machine learning model to detect spam emails using textual content from SMS messages.

## 🔧 Technologies
- Python
- pandas, scikit-learn

## 🧰 Libraries to Install
```bash
pip install pandas scikit-learn
```

## 🚀 Project Steps

### ✅ Step 1: Import Libraries
Import all required Python libraries for data manipulation and machine learning.

### ✅ Step 2: Load Dataset
Load `spam.csv` using `pandas`, and inspect the first few rows.

### ✅ Step 3: Data Cleaning
Keep only required columns and convert labels (`ham` = 0, `spam` = 1).

### ✅ Step 4: Vectorize Text
Use `CountVectorizer` to transform text messages into numeric feature vectors.

### ✅ Step 5: Split Dataset
Split the data into 80% training and 20% test using `train_test_split`.

### ✅ Step 6: Train Model
Use `MultinomialNB()` from `sklearn.naive_bayes` to train the spam classifier.

### ✅ Step 7: Evaluate
Use `classification_report` to display model accuracy, precision, recall, and F1-score.

## ✨ Results
- ~98% accuracy using Naive Bayes.
- Optionally improve with TF-IDF or SVM.

---

**Author:** Kshitija Kalyan Karpe 
**Email:** kshitijakarpe2201@gmail.com
