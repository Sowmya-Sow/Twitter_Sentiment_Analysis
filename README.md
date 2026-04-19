![Status](https://img.shields.io/badge/status-Completed-brightgreen)
![Tech](https://img.shields.io/badge/Python-NLP-blue)
![Dataset](https://img.shields.io/badge/Dataset-Sentiment140-orange)
![ML](https://img.shields.io/badge/ML-Scikit--Learn-yellow)

📌 Overview

Social media platforms generate massive volumes of unstructured, opinion-rich data. However, extracting meaningful insights from informal, noisy text remains a challenge.

This project builds a complete NLP pipeline that:

Cleans and preprocesses raw tweets

Converts text into numerical features

Trains and evaluates multiple ML models

Generates interpretable sentiment predictions

It demonstrates how raw text can be transformed into business-relevant insights using scalable and interpretable techniques.

🎯 Objectives

🔹 Preprocess noisy tweet data for analysis

🔹 Convert text into meaningful numerical features (TF-IDF)

🔹 Train and compare multiple classification models

🔹 Evaluate performance using accuracy and F1-score

🔹 Enable real-time sentiment prediction

🔹 Visualise sentiment distribution and model performance

⚙️ Key Capabilities

1. Text Preprocessing

Removes URLs, mentions, hashtags, and special characters

Stopword removal and text normalization

Handles noisy and informal tweet structures

2. Feature Engineering (TF-IDF)
   
Converts text into numerical vectors

Uses n-grams to capture context (e.g., “not good”)

3. Multi-Model Training

Three models are trained and compared:

Logistic Regression

Naive Bayes

Random Forest

4. Model Evaluation
   
Accuracy

Precision / Recall

F1-score

Confusion Matrix

5. Sentiment Prediction

Predicts sentiment for new tweets in real-time:

predict_sentiment("I love this product") → Positive

6. Data Visualization
   
Sentiment distribution

Model comparison

Confusion matrix heatmap

🧭 System Pipeline

Raw Tweets 
   ↓
Text Cleaning 
   ↓
TF-IDF Vectorization 
   ↓
Model Training 
   ↓
Evaluation 
   ↓
Prediction

🧰 Technology Stack

🔹 Python
🔹 Scikit-learn
🔹 NLTK
🔹 Pandas & NumPy
🔹 Matplotlib & Seaborn

🤖 Models Used

Model	Strength

Logistic Regression	Best overall performance

Naive Bayes	Fast and efficient

Random Forest	Handles noisy data well

📊 Dataset

Sentiment140 Dataset (Kaggle)

1.6 million labelled tweets

Labels:

0 → Negative

4 → Positive

For training efficiency:

100,000 stratified samples used

📈 Sample Results

Model	Accuracy	F1 Score

Logistic Regression	~78%	~0.78

Naive Bayes	~76%	~0.76

Random Forest	~72%	~0.72

💼 Use Cases

For Data Analysts

Analyze customer sentiment trends

Identify negative feedback patterns

Support decision-making with data insights

For Businesses

Monitor brand perception

Track campaign performance

Improve customer experience

🧪 Sample Predictions

"I absolutely love this!"  → Positive  

"Worst experience ever."   → Negative  

⚠️ Limitations

No neutral class in dataset

Limited sarcasm detection

Dataset is relatively old (2009 tweets)

Language evolution may affect accuracy

🧠 Key Takeaways

🔹 Effective NLP depends heavily on preprocessing quality

🔹 Classical ML models can perform strongly with proper feature engineering

🔹 TF-IDF + Logistic Regression provides a reliable and interpretable baseline

🔹 Converting text into insights is more valuable than just model accuracy
