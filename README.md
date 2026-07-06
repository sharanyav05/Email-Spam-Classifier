# 📧 Email Spam Classifier using Machine Learning

> **A Machine Learning and Natural Language Processing (NLP) project that classifies SMS messages as Spam or Ham (Not Spam) using text preprocessing and multiple classification algorithms.**

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![NLTK](https://img.shields.io/badge/NLTK-NLP-green?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=for-the-badge&logo=googlecolab)

---

# 📌 Project Overview

Email spam is one of the most common cybersecurity and communication challenges. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically classify SMS messages as **Spam** or **Ham (Not Spam)**.

The project includes text preprocessing, feature extraction using **TF-IDF Vectorization**, model training, evaluation, and custom message prediction.

---

# 🎯 Objective

The objective of this project is to build an intelligent spam detection system that accurately classifies SMS messages using machine learning algorithms and NLP techniques.

---

# 📂 Dataset Information

- **Dataset:** SMS Spam Collection Dataset
- **Total Messages:** 5,572
- **Classes:**
  - **Ham (0)** – Legitimate Messages
  - **Spam (1)** – Unwanted Promotional Messages

---

# 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Duplicate Value Check
- Spam vs Ham Distribution
- Character Count Analysis
- Word Count Analysis
- Sentence Count Analysis
- Histograms
- Correlation Heatmap

---

# 🧹 Data Preprocessing

The text data was cleaned using the following NLP techniques:

- Removed unnecessary columns
- Renamed columns
- Removed duplicate records
- Converted text to lowercase
- Removed punctuation
- Tokenization
- Stopword Removal
  
---

# 🧠 Feature Engineering

Additional numerical features were created for analysis:

- Character Count
- Word Count
- Sentence Count

Text data was converted into numerical format using:

- **TF-IDF (Term Frequency–Inverse Document Frequency)**

---

# 🤖 Machine Learning Models

The following models were trained and evaluated:

- Multinomial Naive Bayes
- Logistic Regression
- Random Forest Classifier

The performance of all models was compared to identify the best-performing classifier.

---

# 📊 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

# 📨 Custom Prediction

The trained model can predict whether a user-entered SMS message is:

- 📩 Ham (Not Spam)
- 🚫 Spam

---

# 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- WordCloud
- Scikit-learn

---

# 📁 Project Structure

```text
Email-Spam-Classifier/
│
├── Email_Spam_Classifier.ipynb
├── spam.csv
├── README.md
├── LICENSE
└── images/
      ├── spam_distribution.png
      ├── wordcloud_spam.png
      ├── wordcloud_ham.png
      ├── confusion_matrix.png
      └── model_comparison.png
```

---

# 🚀 Future Scope

- Improve prediction accuracy using advanced NLP models
- Deploy the model as a web application using Streamlit or Flask
- Integrate with real-time email filtering systems
- Explore Deep Learning models for spam detection

---

# 👩‍💻 Developed By

**Sharanya Vashisht**

🎓 B.Tech – Computer Science Engineering (AI & ML)

📌 CodTech AI Internship Project

---

## ⭐ If you found this project useful, don't forget to star this repository!
