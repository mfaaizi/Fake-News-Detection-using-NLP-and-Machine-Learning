📰 Fake News Detection using NLP and Machine Learning

This project aims to identify whether a given news article is real or fake using natural language processing (NLP) and machine learning techniques. It demonstrates a complete ML pipeline from data preprocessing to model evaluation.

🚀 Features

Preprocessing of text data (lowercasing, stopword removal, punctuation cleaning)

TF-IDF vectorization to extract numerical features from news content

Multiple ML models evaluated, including:

Logistic Regression

Passive Aggressive Classifier

Model evaluation using accuracy, confusion matrix, and precision-recall metrics

Clear visualizations to interpret model performance

🧠 Tech Stack

Python

Scikit-learn

NLTK

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

📁 Dataset

Dataset used: Fake News Dataset from Kaggle
It contains the title, text, and label (Fake or Real) for thousands of news articles.

🧪 How It Works

Load the dataset and inspect label distribution

Preprocess the text (clean, tokenize, remove stopwords)

Convert text to vectors using TF-IDF

Train ML classifiers and evaluate performance

Visualize confusion matrix and accuracy

📊 Results

Logistic Regression achieved high accuracy with good generalization

Passive Aggressive Classifier performed well for fast, online learning

Confusion matrices used to validate classification reliability

⚙️ How to Run

Clone the repository

Open the Jupyter notebook

Run each cell in order

Modify model or preprocessing logic to experiment with improvements
