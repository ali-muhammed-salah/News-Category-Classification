# 📰 News Category Classification – NLP Task

### 🚀 **ELEVVO Internship Project**

* 👤 **Author:** Ali Muhammed  
* 🧠 **Task Level:** 1  
* 🚀 **Task Number:** 2  

---

## 🎯 **Objective**

Develop a machine learning and neural network model to classify **news articles** into **multiple categories** using NLP and deep learning techniques.

---

## 📁 **Dataset**

* **Files:** `train.csv`, `test.csv`
* **Columns Used:**
  * `TITLE` (News headline)
  * `DESCRIPTION` (News summary)
  * `CATEGORY` (Target class)

* **Classes:** Multiple news topics (Politics, Sports, business, Science Technology)

---

## 🛠 **Tools & Libraries**

* 🐍 Python  
* 📊 Pandas  
* 🔡 re (Regular Expressions)  
* ✂️ NLTK  
* 🔢 Collections  
* 📈 Matplotlib  
* ☁️ WordCloud  
* 🤖 Scikit-learn  
* 🔥 XGBoost  
* 🧠 TensorFlow / Keras  

---

## 🔄 **Workflow Overview**

### 🧹 **1. Data Cleaning & Preprocessing**
* 🔡 Converted text to lowercase  
* 🚫 Removed punctuation, symbols, and stopwords  
* ✂️ Tokenized and joined cleaned words for training  

---

### ✨ **2. Feature Extraction**
* Used **TF-IDF Vectorizer** for classical models
* Used **Label Encoder** and **One Hot Encoder** for neural networks  
---

### 🧠 **3. Model Building**

#### Classical Approach:
* **Logistic Regression Classifier**
* **Random Forest Classifier**
* **Naive Bayes Classifier**
* **XGBoost Classifier**

#### Neural Network Approach:
* Feedforward **Keras Sequential Model**  
* Input: Padded Sequences  
* Output: Multi-class Softmax  

---

### 📊 **4. Model Evaluation**

* Used metrics like **Accuracy**, **Confusion Matrix**, and **Classification Report**  
* Tracked **training/validation loss** and accuracy curves  

---

### 🎨 **Visualizations**

#### ✅ WordCloud:
* Generated WordCloud showing the **most frequent words** in news articles.

---

## 📊 **Model Insights**

| **💡 Model**         | **🧩 Type**          | **🎯 Accuracy** |
| ----------------- | ----------------- | ------------ |
| 📈 Logistic Regression        | Classical ML      | ~89% ✅         |
| 🌲 Random Forest        | Classical ML      | ~87% ✅         |
| 🔬  Naive Bayes        | Classical ML      | ~89% ✅         |
| 🚀 XGBoost        | Classical ML      | ~86% ✅         |
| 🤖 Neural Network | Deep Learning     | ~86% ✅         |

---

## 💡 **Key Learnings**

* Multi-class classification using both classical and deep learning methods  
* Text preprocessing and feature engineering  
* Evaluating and visualizing NLP models  

---

> **Note:** This task introduced **deep learning** via Keras while reinforcing core NLP skills learned.

