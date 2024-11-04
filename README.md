# Fake-News-Detector-using-ML-NLP
Overview:
This project aimed to build a reliable system for classifying news articles as “Real” or “Fake” using Natural Language Processing (NLP) and machine learning. By leveraging Logistic Regression, the model achieved high accuracy, demonstrating the power of effective data preprocessing and feature engineering.

🔍 Exploration:
Working with a dataset of 20,800 records, each with attributes like title, author, and text, I explored data quality and handled missing values. Key fields were combined into a content column, simplifying the input for NLP analysis.

🔹 Key Steps:

Data Cleaning 🧹: Addressed missing values and merged title and author fields to enrich text data.
Preprocessing & Stemming ✂️: Employed NLTK’s PorterStemmer and removed stop words, enhancing the model's ability to capture core content.
Feature Extraction with TF-IDF 🔢: Used TfidfVectorizer to convert text data into numerical vectors, focusing on word significance within each document.
Model Training & Evaluation 📊: The Logistic Regression model was trained on 80% of the data and tested on 20%, achieving 98.6% training accuracy and 97.9% test accuracy, proving its reliability in real-world scenarios.
🔧 Modules Used:

Pandas & NumPy for data manipulation
NLTK for text preprocessing and stemming
TfidfVectorizer for converting text to vectors
Scikit-Learn for model selection, training, and evaluation
✅ Conclusion:
This project successfully demonstrated the impact of clean data and powerful NLP techniques in combatting misinformation. The high accuracy rates highlighted how combining Logistic Regression with TF-IDF vectorization and thorough preprocessing creates effective classification models. This experience refined my skills in NLP, data cleaning, and machine learning, showing the potential of AI-driven solutions in addressing critical challenges.
