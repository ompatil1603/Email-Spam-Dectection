📧 Spam Detection Project using NLP & Machine Learning
A machine learning-based spam detection system built using Natural Language Processing (NLP) techniques to classify emails/messages as spam or ham (non-spam).

🚀 Project Overview
This project applies NLP techniques and machine learning algorithms to detect spam messages from a dataset of emails or SMS messages. It involves:

Text preprocessing

Feature extraction

Model training and evaluation

Performance comparison between algorithms

📂 Dataset
Source: Public datasets / Gmail MBOX / Custom email exports

Size: 55,000+ emails collected from 12 users

Format: .eml, .mbox, or converted .csv/.xlsx

Features:

Date

From

To

Subject

Body

Label (0 = Ham, 1 = Spam)

🛠️ Tech Stack
Programming Language: Python

Libraries:

pandas, numpy – Data handling

nltk, re – Text preprocessing

sklearn – ML models

matplotlib, seaborn – Visualization

🔎 NLP Preprocessing
Lowercasing

Tokenization

Stopword removal

Punctuation removal

Stemming and Lemmatization

Feature Engineering:

Subject length

Word count

Special character count

Link detection

🧠 Machine Learning Models Used
Naive Bayes

Logistic Regression

Random Forest

Support Vector Machine (SVM)

📊 Model Evaluation
Metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Model	Accuracy
Naive Bayes	63%
Logistic Regression	89%
Random Forest	91%
SVM	88%

📈 Results & Visualization
Confusion Matrix for each model

Bar charts comparing model performance

Word clouds of most common spam vs. ham keywords
