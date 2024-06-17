SMS Spam Classifier
This project is an SMS spam classifier that uses a Multinomial Naive Bayes model to classify SMS messages as either spam or non-spam. The project involves data preprocessing, text vectorization using TF-IDF, model training, and evaluation. Additionally, an interactive feature is provided to allow real-time predictions.

Dataset
The dataset used is a collection of SMS messages labeled as 'spam' or 'ham' (non-spam).

Steps Involved
Data Preprocessing: Cleaned and prepared the dataset.
Text Vectorization: Used TF-IDF Vectorizer to convert text data into numerical format.
Model Training: Trained a Multinomial Naive Bayes classifier on the vectorized data.
Model Evaluation: Evaluated the model's performance on the test set.
Saving Models: Saved the trained model and TF-IDF vectorizer for future use.
Interactive Feature: Added an input prompt for real-time spam prediction.
Files
spam.csv: The dataset file.
spam_classifier.pkl: The trained Naive Bayes model.
tfidf_vectorizer.pkl: The TF-IDF vectorizer.
sms_spam_classifier.ipynb: Jupyter Notebook with the complete code.
