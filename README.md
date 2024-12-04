# fake-news-prediction-logistic-regression-
logistic regression algoritham -fake news prediction

This project implements a Logistic Regression model to predict the authenticity of news articles using Python and machine learning libraries. The model is trained to classify news as either real or fake.
Features
Data Preprocessing:

Handles missing values in the dataset.
Combines the author name and news title to create a unified content field.
Converts text data into its root form using stemming (e.g., actor, actress, acting → act).
Text Vectorization:
Converts textual content into numerical features using TF-IDF Vectorizer.

Model Training and Evaluation:
Trains a logistic regression model to classify the news.
Provides accuracy scores for both training and testing datasets.

Prediction System:
A simple prediction system to classify whether a piece of news is real or fake.

Dataset
The dataset contains the following:

News articles labeled as real (0) or fake (1).
Features include author name, title, and content.
Null values are replaced with empty strings during preprocessing.

Key Libraries Used
Numpy & Pandas: Data manipulation and analysis.
NLTK: Text preprocessing (e.g., stopwords, stemming).
Scikit-learn: Machine learning model implementation and evaluation.


Results

Training Accuracy: 0.9863581730769231

Testing Accuracy: 0.9790865384615385


